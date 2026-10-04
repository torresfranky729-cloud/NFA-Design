# NFA Design

## Problems Completed

I completed Problems 6, 7, 9, 10, and 13 using JFLAP.

## What I Learned

I learned how NFAs read strings and move between states. I also learned the difference between an NFA and a DFA. A DFA needs one transition for every possible input at each state, while an NFA can have multiple transitions or no transition for an input.

Problem 7 helped me understand NFA branching because the machine can stay at q0 or move to q1 when it reads a 1.

Problem 13 helped me understand how states can remember information. I used q0 for zero 1's, q1 for one 1, and q2 for at least two 1's.

## Challenges and Gold-st-rings

I did not encounter any unexpected test results or gold-st-rings while testing my NFAs. I used Multiple Run and Step by State in JFLAP to check that my machines accepted and rejected the expected strings.

## Other Comments

The problems helped me understand that each state can represent what the machine needs to remember about the input it has already read. Testing different strings also helped me understand why a string must finish in a final state to be accepted.	