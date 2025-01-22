# JS-UpperCase
Java Script code with an Upper Case First Letter

var name = prompt("What is your name : ")

var first =name.slice(0,1);

var upperCaseFirst = first.toUpperCase();

var restOfName=name.slice(1,name.length);

restOfName= restOfName.toLowerCase();

alert("Hello, " + upperCaseFirst+ restOfName);
