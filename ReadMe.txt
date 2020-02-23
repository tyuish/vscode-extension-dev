Tnis is a Readme for this project.

Here is a sample js code for creating a vc code extension that creates a simple helper utility

This goes into:

C:/Users/agars/AppData/Roaming/Code/User/snippets/{}javascript.json
{
	// Place your snippets for javascript here. Each snippet is defined under a snippet name and has a prefix, body and 
	// description. The prefix is what is used to trigger the snippet and the body will be expanded and inserted. Possible variables are:
	// $1, $2 for tab stops, $0 for the final cursor position, and ${1:label}, ${2:another} for placeholders. Placeholders with the 
	// same ids are connected.
	// Example:
	 "Print to shyam console": {
	 	"prefix": "log",
	 	"body": [
	 		"console.log('$1');",
	 		"$2"
	 	],
 		"description": "Log output to console"
	 },

	 "Declare Function simple": {
		"prefix": "fn",
		"description": "declare a function - simple ",
		"body": "function $1($2) { $3 }"
	},

	"Declare Function Advanced": {
		"prefix": "fn",
		"description": "declare a function - adv",
		"body": [
			"function ${1:functionName}(${2:var1}) {", 
			" $3 ",
			"}"
		]
	},
}