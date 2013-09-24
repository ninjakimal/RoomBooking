# contentForLayout()

## Description
Includes content for the `body` section, which equates to the output generated by the view template run by the request.

## Function Syntax
	contentForLayout(  )



## Examples
	
		<!--- In `views/layout.cfm` --->
		<html>
		<head>
			<title>My Site</title>
		</head>
		
		<body>
		<cfoutput>#contentForLayout()#</cfoutput>
		</body>
		
		</html>