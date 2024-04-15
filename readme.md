## Write short notes on string methods with code examples
## toLowerCase()
## toUpperCase()
## substring()
## replace()
## trim()
## split()
## slice()

## ANS:

## a. let str="hello WOrld"
## console.log(str.toLowerCase());

## b.let str="hello WOrld"
## console.log(str.toUpperCase());

## c:-let str="hello world"
## console.log(str.substring(0,3));

## d:- let str=" hello WOrld "
## console.log(str.replace("hello", "hi"));

## e:-let str=" hello world "
## console.log(str.trim());

## f:-let str=" hello world "
## console.log(str.split(" "));

## g:-let str=" hello world "
## console.log(str.slice(1,5));

## create a simple app that takes the user’s name and greets him/her after capitalizing the first letter of the user’s name and changing the rest of the letters into lowercase (toUpperCase(), toLowerCase(), slice(), length property, string concatenation)


## ANS:
## let yourname=prompt("enter your name")
## let fletter=yourname.slice(0,1)
## let ucase=fletter.toUpperCase()
## let sletter=yourname.slice(1,yourname.length)
## let lcase=sletter.toLowerCase()
## let fullname=ucase+lcase
## alert("Good Morning "+ fullname)