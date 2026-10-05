# Agent Technology Project

Mini-project for the Agent Technology module (2024-2025): design and implementation of a multi-agent system in Java, covering agent interaction inside a single platform and between containers and platforms.

- Project statement: [`TA-Mini-Project 2024-2025.pdf`](TA-Mini-Project%202024-2025.pdf)
- Project report (French): [`Rapport Projet Tech Agent.pdf`](Rapport%20Projet%20Tech%20Agent.pdf)

## Repository structure

```
.
├── Code/                              # Java source code (parts 1 and 2)
├── Execution Images/                  # Screenshots of the executions
├── aima-python-master/                # AIMA Python code (Artificial Intelligence: A Modern Approach)
├── .vscode/                           # VS Code settings
├── Rapport Projet Tech Agent.pdf      # Project report
└── TA-Mini-Project 2024-2025.pdf      # Project statement
```

## Prerequisites

- Java JDK 8 or later
- The agent platform library used in the labs (JADE) on the classpath
- An IDE such as VS Code, IntelliJ IDEA or Eclipse

## How to run

### Part 1

Run `main.java`.

### Part 2

The second part has two scenarios.

**Inter-containers**: agents running in different containers of the same platform.

Run `main.java`.

**Inter-platforms**: agents running on two separate platforms, a seller and a buyer. Start the seller first, then the buyer:

1. Run `SellerPlatformMain.java`
2. Run `BuyerPlatformMain.java`

## Execution results

Screenshots of the runs are in the `Execution Images` folder, and the analysis is in the project report.
