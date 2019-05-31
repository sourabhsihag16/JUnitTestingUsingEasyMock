# JUnitTestingUsingEasyMock
Some sample code and methods to get a good understanding of Testing
# Why JUnit testing
You cannot test everything! Instead, think about:
     - boundary cases,
     - empty cases,
     - error cases
     - behavior in combination (but not to excess)
A unit test examines the behavior of a distinct unit of work. Within a Java application, the “distinct unit of work” is often (but not always) a single method. By contrast, integration tests and acceptance tests examine how various components interact. A unit of work is a task that isn’t directly dependent on the completion of any other task.

Every developer should perform some type of test to see if code works. Developers who use automatic unit tests can repeat these tests on demand to ensure that new code works and doesn’t break existing tests.

| Manual Testing | Automated Testing |
| ------- | ------ |
| Executing a test cases manually without any tool support is known as manual testing. | Taking tool support and executing the test cases by using an automation tool is known as automation testing. |
| Time-consuming and tedious − Since test cases are executed by human resources, it is very slow and tedious. | Fast − Automation runs test cases significantly faster than human resources. |
| Huge investment in human resources − As test cases need to be executed manually, more testers are required in manual testing. | Less investment in human resources − Test cases are executed using automation tools, so less number of testers are required in automation testing. |
| Less reliable − Manual testing is less reliable, as it has to account for human errors. | More reliable − Automation tests are precise and reliable. |
| Non-programmable − No programming can be done to write sophisticated tests to fetch hidden information. | Programmable − Testers can program sophisticated tests to bring out hidden information. |

The main advantage of JUnit is that it is automated rather than you manually having to check with your print outs. Each test you write stays with your system. This means that if you make a change that has an unexpected side effect your test will catch it and fail rather than you having to remember to manually test everything after each change.
