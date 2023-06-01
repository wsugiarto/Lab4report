# Lab Report 4

## Step 4
![](s4.png)
Typed `<ssh cs15lsp23iv@ieng6.ucsd.edu>` `<enter>`

Note: I did not have to put in the password because I had already set up the SSH keys and authorized keys in the remote setup.
 
## Step 5
![](s5.png) 
Typed `<git clone>` then `<CTRL C> <CTRL V>` (to paste https://github.com/wsugiarto/lab7)  `<enter>`

## Step 6
![](s6.png)
`<cd lab7>` `<enter>`

`<bash test.sh>`

Note: the test.sh file contained the following:
```
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests
```

## Step 7
![](s7.2.png)
`<vim ListExamples.java>` `<enter>`
`/ x 1` `<ENTER>` `9 n e a` `<BACKSPACE>` `2 : w q` `<enter>`
Note: the `/` started the search feature for the string x1, then `<enter>` to find x1. Afterwards instead of pressing n 9 times, type `9n` which goes to the next result of the search 9 times. `e a` where e is to go to the last letter of the word index1, a to append/enter insert mode. Then `<BACKSPACE>` to get rid of 1 and replace it with 2 by pressing 2. Then to save just do `w q <enter>`. 

## Step 8
![](s8.png)
`<up><up><up><enter>` (to get the javac for junit)
`<up><up><up><enter>` (to get the java for junit)

## Step 9
![](s9.png)
`<git add ListExamples.java>` `<enter>`
 
`<git commit -m hi>` `<enter>`
 
`<git push git@github.com:wsugiarto/lab7.git>` `<enter>`
