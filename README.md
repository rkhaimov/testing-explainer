Four pillars:
Protection against regressions: Low on false negatives
Resistance to refactoring: Low amount of false positives
Maintainability:
How hard it is to run the test
How hard it is to understand the test
How hard its is to write the test
Fast feedback: Fast tests allow noticing bugs quickly, reducing the cost of fixing them

Demonstrate confusion matrix on first two items (Probably add matrix such as recall and precision)

Tests should verify only the end result, not implementation detail. Which is meaningful to a client

Stubs vs Mocks
CQS
Mocks are commands
Stubs are queries

You should verify only the observable for client behaviour.
Usually it means verifying only interactions with mocks.
But there are cases when stubs should also be verified (for example when call order or call count or call args are important)

Styles of unit testing (Compare them using good test attributes):
Output based - the best
Communication based - meh
State based - worst

SUT and three sections of a test

The most important things are these two:
Protection against regressions: Low on false negatives
Resistance to refactoring: Low amount of false positives

Reread functional architecture 150 page
