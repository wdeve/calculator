[![Board Status](https://dev.azure.com/wdeve/44680bd8-e24d-4f58-a7c1-88dfb50e5d00/105dfc51-0073-4f75-a891-200335232e34/_apis/work/boardbadge/bd4eb437-7816-49c7-95f8-8e466de2a07b)](https://dev.azure.com/wdeve/44680bd8-e24d-4f58-a7c1-88dfb50e5d00/_boards/board/t/105dfc51-0073-4f75-a891-200335232e34/Microsoft.RequirementCategory)
Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

[![Build Status](https://dev.azure.com/wdeve/Integrating%20External%20Source%20Control%20with%20Azure%20Pipelines/_apis/build/status/wdeve.calculator?branchName=master)](https://dev.azure.com/wdeve/Integrating%20External%20Source%20Control%20with%20Azure%20Pipelines/_build/latest?definitionId=8&branchName=master)

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

