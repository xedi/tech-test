#XEDI Tech Test

This test is designed to provide us with an understanding of your level as a programmer. We'd like you to complete this test in either **JS** or **PHP** as these are the primary languages we use at XEDI.

Once you're done, send us an email with your work to `careers@xedi.com`. This can be either as a fork of this repo, hosted on your own server or in a `.zip` file.

If you have any issues with this test or its instructions, please [open an issue](https://github.com/xedi/tech-test/issues/new) or contact `careers@xedi.com`.

- **This test should take you no longer than 2 hours.**
- **Code style is important. For PHP, follow PSR-1 & PSR-2.**
- **No 3rd party packages/code is allowed.** 
- **You are welcome (and encouraged) to use new language features.**

### The Test

To complete this test you will be required to build a simple system for adding `Todo` objects to `TodoList` objects. `TodoListPrinter`s will be used to output the `TodoList`s. You should provide an example file showing the usage of this system.

##### Todo

`Todo`s should have the following properties:

- **title** _(string)_
- **completed** _(bool)_

They should have a public `toggle()` method which will switch the `completed` property between `true` and `false`.

##### TodoList

`TodoList`s should contain an `array` of todos and have the following public methods available:

- **add(_todo_)** -> Add a todo object
- **remove(_index_)** -> Remove the todo at the given index
- **get(_index_)** -> Return the todo at the given index
- **all()** -> Return all todos
- **completed()** -> Return the completed todos
- **active()** -> Return the incomplete todos

##### TodoListPrinter

`TodoListPrinter`s should have a single public method; `print(todoList)`. This method should output the given `todoList`. With PHP you should use `echo`, in JS use `console.log`. The format should be as follows.

	[/] A completed task
	[ ] An incomplete task
			
### Considerations

- Don't overthink, but don't over-simplify, the task.
- Consider writing tests. Automated or not, they will help justify your working.
- Be prepared to discuss and justify decisions you have made during this test.
- While not required. Consider encapsulation through getters/setters.

:coffee:
