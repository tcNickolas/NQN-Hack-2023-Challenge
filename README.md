# Welcome to the Northwest Quantum Nexus Hackathon 2022!

<p align="left">
  <a href="https://nwquantum.com/" target="_blank"><img src="https://nwquantum.com/wp-content/uploads/2020/09/NQN_Logo_03042019_65px.png" style="padding-left: 5%"/> </a>
  <a href="https://azure.microsoft.com/en-us/solutions/quantum-computing/" target="_blank"><img src="https://user-images.githubusercontent.com/10100490/151488491-609828a4-cd1f-4076-b5b2-a8d9fc2d0fa4.png" width="30%"/> </a>
  <a href="https://ionq.com/" target="_blank"><img src="https://user-images.githubusercontent.com/10100490/151488159-da95eb05-9277-4abe-b1ba-b49871d563ed.svg" width="20%" style="padding: 1%;padding-left: 5%"/></a>
</p>

## Challenge overview

Quantum computing has many exciting applications in chemistry, machine learning, and optimization – but we've only scratched the surface of the possibilities as a civilization, just like classical computing in the 1950s. We hope you all go on to do quantum algorithms research that will revolutionize every aspect of society for the better!

This time, though, we've got just a bit over two days, and we'd like you to focus on one task: **exploring the limits of running programs on IonQ quantum hardware**!

The current quantum devices are still NISQ (noisy intermediate-scale quantum devices), so both the number of the qubits available and the noise introduced during a computation are significant factors you have to consider when running your programs. 
In this challenge, we invite you to explore running programs on quantum hardware with a problem of your choice!

1.	Come up with a problem you’d like to explore using a quantum computer. It can be a textbook protocol or a solution to a classical problem using a quantum algorithm – the key is that you have to be able to solve multiple instances of the problem of different “sizes”.
2.	Implement the solution in a quantum programming language. You can develop your project using any language supported by Azure Quantum: Q#, Qiskit, or Cirq.
3.	Explore your solution’s behavior on the noiseless cloud simulator and then on real ion trap quantum computers provided by IonQ, Harmony and Aria.

What is the largest problem instance for your problem which you can solve on a quantum computer and get the correct result without it being overtaken by the noise? For different problems, you’ll run either into the limit of the number of qubits or into the results becoming too noisy first.

*Check out the examples of projects that explore running programs of increasing size on IonQ devices in the Resources section to get started!*

## Submitting your project

**Project submissions are due on Sunday, January 22nd, at 5 pm PST.**

Your project:

* Must include a problem description and instructions on running the project in README.md file.
* Must solve a small instance of the problem without any user input, or with a well-documented user input. If your solution requires an input, its format should be documented in README.md, including an example.
* Must use IonQ simulator and IonQ QPU (Harmony and/or Aria) to solve a small instance of the problem, and include the results. 
* If you use resource estimation tools to evaluate the scaling behavior of your solution, include the results produced by resource estimation too.
* Must produce an output presenting the instance of the problem solved and the solution in human-readable format.
* Must be original.

To submit your project:

1. Create a GitHub repository.
2. Commit your work to your repository.  
   *Make sure to commit any files you consider relevant: the project itself, screenshots of results, any visualizations you've done, the project description, and so on.*
3. To submit your project, submit the link to your repository to https://aka.ms/NQNHack/ProjectSubmit.  
   *Your repository has to be made public at the time of the Hackathon end for us to be able to judge your solutions. We don't recommend making your work public early during the Hackathon, so as not to tempt other teams to borrow from your work. Let everybody enjoy their exploration!*

## Judging

We'll be evaluating the projects based on several criteria. Here is the list of criteria and example questions we'll consider when evaluating the projects:

* Technical depth (5 points). How complicated is the selected problem? How well is it solved? How does the project use IonQ simulator and hardware to solve the problem?
* Creativity (5 points). How original is the problem selection? How creative is the output presentation? Is the solution to the problem displayed using a clever visualization?
* Educational value (5 points): Is this project valuable for helping others learn? Did the team write a blog post about the project sharing their learnings with others? Is the project structured as a tutorial?

## Prizes

Up to (3) teams with the highest team scores will be chosen as the winners of the Hackathon.

**The winners will be announced on Tuesday, January 24th, at the NQN Summit.**

Each member of the winning teams will get:
* A Surface 2 headset
* A copy of ["Q# Pocket Guide"](https://www.oreilly.com/library/view/q-pocket-guide/9781098108854/) signed by the author
* An $50 gift card

Additionally, each winning team will get a 1-hour mentoring session with an Azure Quantum team leader (to be scheduled separately after the NQN Summit).

## Resources

### Hackathon resources

* [Hackathon kickoff slides (January 20)](https://github.com/tcNickolas/NQN-Hack-2023-Challenge/blob/main/2023_01_20_NQN_Hack_kickoff.pdf)
* [Project example 1: Find bit strings with alternating bits using Grover's search](https://github.com/tcNickolas/NQN-Hack-2023-Challenge/blob/main/GroverSearch_AlternatingBits.ipynb)
* [Project example 2: Solve a Sudoku puzzle using Grover’s search](https://github.com/tcNickolas/NQN-Hack-2023-Challenge/blob/main/GroverSearch_SolveSudoku.ipynb)
* [Discord server](https://discord.gg/yAAA8bdd)

### Azure Quantum resources

* [Azure Quantum and Microsoft Quantum Development Kit documentation](https://learn.microsoft.com/azure/quantum/)
* [Understanding job costs in Azure Quantum](https://learn.microsoft.com/azure/quantum/azure-quantum-job-costs)
* [Tracking limits and quotas](https://learn.microsoft.com/azure/quantum/azure-quantum-quotas)

### Learning resources

* [The Quantum Katas](https://github.com/Microsoft/QuantumKatas/) - a collection of tutorials and practice problems.
* Microsoft Learn learning path ["Quantum computing foundations"](https://docs.microsoft.com/learn/paths/quantum-computing-fundamentals/).
* [Q# developer blog](https://devblogs.microsoft.com/qsharp/).
