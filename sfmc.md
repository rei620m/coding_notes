# sfmc

|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AMPscript&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|SSJS|
|-|-|-|
|Use case|Emails|・ CloudPage<br>・ SSJS makes execution of emails slow and hence should only be used when there are no functions to support in AMPscript|
|Declare code block|<code>%%[</code> AMPscript goes here <code>]%%</code>|<code><script runat=server></code> SSJS goes here <code></script></code>|
|Write value|oututline(v(@variable))|<code>Write(ContentBlockByKey('1a1a111a-0111-1111-a111-a111a111111a'))</code>|
|IF statement|SET @a = 1 <br><BR>IF @a == 1 THEN<br>&nbsp;&nbsp;&nbsp;&nbsp;SET @b = "true"<br>&nbsp;&nbsp;ELSE<br>&nbsp;&nbsp;&nbsp;&nbsp;SET @b = "false"<br>ENDIF|<code>var a = 1;</code><br><code>if (a == 1) {</code><br><code>   Write ("true");</code><br><code>) else (</code><br><code>   Write("false");</code><br><code>}</code>|
