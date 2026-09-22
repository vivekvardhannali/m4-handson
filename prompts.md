part a)It gave the correct mistake just by giving two lines of stack trace ie the assert failure and it pointed out the exat bug ie replacing the conditional statement with >=5 instead of >5.

part b)the bug is in the conditional which changed >5 with >=5 and once done that.make test command ran without any tc's failing.