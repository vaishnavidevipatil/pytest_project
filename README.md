# pytest_project
unit test and pytest 

Pytest v/s unittest
Pytest is known for its simplicity, scalability, and powerful features such as fixture support and parameterization. It has a concise syntax and a rich plugin ecosystem. 
On the other hand, unittest is a built-in testing framework that follows the xUnit style and is part of the Python Standard Library

--unit_test--
Imports Python’s built-in unittest module.
Imports the Python function to be tested, <function_to_test> from the module in which it’s defined, <module>.

Creates a test class (TestClass) that inherits from unittest.TestCase class.
Each of the tests that should be run should be defined as methods inside the test class.

the unittest module to identify these methods as tests and run them, the names of these methods should start with test_.

The TestCase class in the unittest module provides useful assertion methods to check if the function under test returns the expected values.

Pytest-
Pytest is possibly the most widely used Python testing framework around - this means it has a large community to support you whenever you get stuck. It’s an open-source framework that enables developers to write simple, compact test suites while supporting unit testing, functional testing, and API testing.