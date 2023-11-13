# Logic Gates

Logic gates are fundamental building blocks of digital circuits and electronic systems. They are devices that perform logical operations on binary inputs (0s and 1s) to produce binary outputs. These gates are the basic components used to design and construct digital circuits that process information in the form of binary code.

There are several types of logic gates, each with a specific logical function:

1. **OR Gate:**
   - In an OR gate, the output of an OR gate attains state 1 if one or more inputs attain state 1.
   - Boolean Expression
   ```Y = A + B``` Read as Y equals A OR B

   - Truth table:

     ```
     A | B | Output
     --|---|-------
     0 | 0 |   0
     0 | 1 |   1
     1 | 0 |   1
     1 | 1 |   1
     ```

2. **AND Gate:**
   - In the AND gate, the output of an AND gate attains state 1 if and only if all the inputs are in state 1.
   - Boolean Expression
   ```Y = A . B``` Read as Y equals A AND B

   - Truth table:
     ```
     A | B | Output
     --|---|-------
     0 | 0 |   0
     0 | 1 |   0
     1 | 0 |   0
     1 | 1 |   1
     ```

3. **NOT Gate (Inverter):**
   - In a NOT gate, the output of a NOT gate attains state 1 if and only if the input does not attain state 1.
   - Boolean Expression
   ```Y = \overline{A}```
   - Truth table:
     ```
     A | Output
     --|-------
     0 |   1
     1 |   0
     ```

4. **NAND Gate:**
   - Output is LOW (0) only when all inputs are HIGH (1).
   - Boolean Expression
   ```Y = A + B```
   - Truth table:
     ```
     A | B | Output
     --|---|-------
     0 | 0 |   1
     0 | 1 |   1
     1 | 0 |   1
     1 | 1 |   0
     ```

5. **NOR Gate:**
   - Output is LOW (0) when at least one input is HIGH (1).
   - Boolean Expression
   ```Y = A + B```
   - Truth table:
     ```
     A | B | Output
     --|---|-------
     0 | 0 |   1
     0 | 1 |   0
     1 | 0 |   0
     1 | 1 |   0
     ```

6. **XOR Gate (Exclusive OR):**
   - Output is HIGH (1) when the number of HIGH inputs is odd.
   - Boolean Expression
   ```Y = A + B```
   - Truth table:

     ```
     A | B | Output
     --|---|-------
     0 | 0 |   0
     0 | 1 |   1
     1 | 0 |   1
     1 | 1 |   0
     ```

These logic gates can be combined and interconnected to create more complex digital circuits capable of performing various functions, such as arithmetic operations, memory storage, and data processing. Digital computers and many electronic devices rely on the principles of digital logic to perform their tasks.
