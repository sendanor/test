# @sendanor/test

This is a unit test environment for our TypeScript libraries.

Our own projects usually require just few dependencies, if any at all. Adding all testing tools would add 300+ 
dependencies into our projects. 

This way the testing environment is separated from the actual source code of our projects. 

It also makes it easier to run newer tests against older versions of the project in order to test backwards 
compatibility.

## Libraries

| Repository                                                      | Summary                  |
| --------------------------------------------------------------- | ------------------------ |
| [@sendanor/typescript](https://github.com/sendanor/typescript)  | The core library         |
| [@sendanor/ui](https://github.com/sendanor/ui)                  | The UI library           |
| [@sendanor/repository](https://github.com/sendanor/repository)  | The Repository library   |
