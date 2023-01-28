## My thoughts about the code:

> I think that the intention and the functionality of the code is good but it needs refactoring to reduce the lines of
> code and to optimize it. I also observe that some parts of the code are hard to read because of non descriptive variable naming.
> In addition to that, some of the type hinting and documentation of the code is not well written. It makes it a little hard for
> me to know what the parameter is.

If I would refactor I would:

- Clarify the documentation, add a short description of what the code does and specify what the return type of the method
- Use a form request to validate the post/patch or put requests from the client
- Ensure that a line of code would not be more than 120 characters to ensure readability
- Remove unused variables in some of the methods
- Remove the redaclared variables
- Improve the conditional statements
- Remove commented code that are not important
- Improve the declaration of some of the variables
- Remove some of the line by line comments where code is already clear (varibles are descriptive already)
