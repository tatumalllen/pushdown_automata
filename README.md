# pushdown_automata
A simple python code for a PDA

What is a PDA?
• A type of automation that extends
the capabilities of a finite
automation with an additional data
storage mechanism called a stack.
• Used in
• Compiler design
• Natural Language Processing
• Protocol Specification and
Verification
• Database Query Languages (SQL)

My Push Down Automata’s Requirements
• Can Recognize the Context-Free Language L= {𝑎𝑛𝑏𝑛 𝑛 ≥ 0}
• Has to be Deterministic
• It will be coded in Python
• It will take the following inputs: 𝑎2𝑏2$, 𝑎3𝑏3$, 𝑎4𝑏4$, 𝑎5𝑏5$, 𝑎7𝑏7$, 𝑎8𝑏8$, 𝑎9𝑏9$,
𝑎10𝑏10$, with 𝑎𝑏$ as the initial input
• Using Pandas Dataset to organize data

Stack
• Made a stack class to access
these important data
structures in DPDAs
• These work with both the input
stack and output stack that I
have in my project

__init__
• Used to init important values
used throughout the program
• Most importantly the stacks

process_input
• The meat of the project
• I converted the DPDA
statements into if statements
that work for each of the rules

Testing Data
• I started out with the initial
ab$, but then went onto doing
higher numbers such as
a^2b^2$ to see if everything
still worked
• I again did some more tests,
this time through the list and
wound up at a^10b^10$
