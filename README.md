# Advanced Engineering Economics Calculator 👷‍♂️

This tool is designed to simplify complex economic calculations by allowing you to evaluate multiple expressions simultaneously. Unlike standard calculators that limit you to single-factor computations, this advanced calculator lets you combine various financial factors in any way that suits you.

Available at: [https://oliverfrost1.github.io/advanced-engineering-economics-calculator/](https://oliverfrost1.github.io/advanced-engineering-economics-calculator/)

## Features

- **Multiple Expressions**: Compute complex equations involving multiple financial factors.
- **Flexible Input**: Combine financial factors in any configuration.
- **Simple Interface**: Simple design for easy navigation and input.
- **Copy Functionality**: Quickly copy results with or without the original equation.

### Calculator Interface

<img width="550" alt="image" src="https://github.com/user-attachments/assets/029e2d1a-bd03-44a7-88d3-959e934da643">


## Supported Financial Factors and Formulas

The calculator supports a range of essential financial factors used in engineering economic analysis:

1. **Present Value Factor (P/F)**:
   - **Formula**: `P/F = 1 / (1 + i)^n`
   - **Description**: Calculates the present value of a future amount.

2. **Future Value Factor (F/P)**:
   - **Formula**: `F/P = (1 + i)^n`
   - **Description**: Calculates the future value of a present amount.

3. **Present Worth of Annuity Factor (P/A)**:
   - **Formula**: `P/A = [(1 + i)^n - 1] / [i * (1 + i)^n]`
   - **Description**: Computes the present worth of a series of equal payments.

4. **Capital Recovery Factor (A/P)**:
   - **Formula**: `A/P = [i * (1 + i)^n] / [(1 + i)^n - 1]`
   - **Description**: Determines the annuity payment required to recover a present amount.

5. **Future Worth of Annuity Factor (F/A)**:
   - **Formula**: `F/A = [(1 + i)^n - 1] / i`
   - **Description**: Calculates the future value of a series of equal payments.

6. **Equivalent Annual Cost Factor (A/F)**:
   - **Formula**: `A/F = i / [(1 + i)^n - 1]`
   - **Description**: Determines the annual cost equivalent of a future amount.

7. **Present Value of Gradient Factor (P/G)**:
   - **Formula**: `P/G = [(1 + i)^n - i * n - 1] / [i^2 * (1 + i)^n]`
   - **Description**: Calculates the present value of a gradient series.

8. **Gradient Series Factor (A/G)**:
   - **Formula**: `A/G = [(1 + i)^n - i * n - 1] / [i * ((1 + i)^n - 1)]`
   - **Description**: Determines the annual equivalent of a gradient series.

> **Note**: In all formulas, `i` represents the interest rate (expressed as a decimal), and `n` represents the number of periods.

## How to Use

1. **Enter Your Expression**:
   - Input your economic expression into the calculator. You can combine multiple financial factors and arithmetic operations.
   - **Example**: `1000*(P/A,5%,10) + 2000*(F/P,5%,10)`

2. **Calculate**:
   - Click the **Calculate** button or press **Enter** to compute the result.

3. **View Results**:
   - The calculator will display both formatted and unformatted results.
   - Use the **Copy** buttons to copy the results, with or without the original equation.

## Examples

Here are some sample expressions to help you get started:

1. **Present Value of a Future Amount**:
   - **Input**: `5000*(P/F,5%,5)`
   - **Explanation**: Calculates the present value of $5,000 received after 5 years at an annual interest rate of 5%.
   - **Output**: `3,917.63`

2. **Future Value with Additional Amount**:
   - **Input**: `2000 + 3000*(F/P,3%,10)`
   - **Explanation**: Adds $2,000 to the future value of $3,000 after 10 years at an annual interest rate of 3%.
   - **Output**: `6,031.75`

3. **Present Worth of an Annuity**:
   - **Input**: `1000*(P/A,4%,7)`
   - **Explanation**: Calculates the present worth of an annuity of $1,000 per year for 7 years at an annual interest rate of 4%.
   - **Output**: `6,002.05`

4. **Complex Expression Combining Multiple Factors**:
   - **Input**:
     ```
     (500*(A/P,6%,15) + 2000*(F/A,6%,15))
     ```
   - **Explanation**: Combines capital recovery and future worth of annuity factors.
   - **Output**: `46,603.42`


## Sample Calculation

![Sample Calculation](https://github.com/user-attachments/assets/45260ed7-3fb2-4d2d-80d2-04d8aceb9e17)

## Contributing

I welcome contributions, if you find any errors or see some possible improvements. Here is how to do it:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -am 'Add new feature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this software in accordance with the license terms.


**There is a slightly different version of the calculator available at: [Advanced Engineering Economics Calculator](https://frosttools.com/engineeringeconomicscalculator)**
