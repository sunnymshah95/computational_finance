# Computational Finance bootcamp

Hello! I hope you're doing well. This is my bootcamp, where I try to revise my mathematical finance concepts such as derivatives-pricing, finite difference methods, solving the Black-Scholes PDE, etc. I do this in conjunction with brushing over my C++ skills, something that is in demand in the field of computational finance. I follow the book [*C++ for Quantitative Finance*](https://www.quantstart.com/cpp-for-quantitative-finance-ebook/) by Halls-Moore. 

# About me:
I'm a MS student at Stanford University, studying Computational and Mathematical Engineering within the [Institute for Computational and Mathematical Engineering](https://icme.stanford.edu/). My concentration is __Mathematical and Computational Finance__. I've already taken several classes on C++ (CME 211 + 212), Quantitative Finance (MATH 238, STATS 240, MS&E 448) and some statistics (CME 308, STATS 240). You can find more about me [here](https://github.com/sunnymshah95).

CME 211 - *Scientific Computing for Scientists and Engineers* (teaches Python and C++)   
CME 212 - *Software Development in C++*    
MATH 238 - *Mathematical Finance*    
STATS 240 - *Statistical Methods in Finance*    
MS&E 448 - *Big Financial Data and Algorithmic Trading*    
CME 308 - *Stochastic Methods in Engineering*    

## Topics Covered So Far:
1. Vanilla/European Option Pricer
     * Covered the derivation of the Black-Scholes pricing for call and put options
     * Covered the C++ concepts of creating classes and then header and source files
2. Pay-Off Functions
     * Covered the different pay-off functions for different options
     * Covered inheritance and polymorphism
     * Covered the use of the keyword *virtual* in C++ function prototypes and destructors
3. Constructing a Simple Matrix class
     * Covered generic, templated programming
     * Covered the std::vector and std::pair data structures   
4. Constructing a Matrix class   
     * Implemented the matrix-matrix, matrix-scalar, matrix-vector operations
     * linking templated classes
5. Introduction to the [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page) library
     * Created a few _main_ files to learn how to use Eigen (previously used MTL4 and Boost for numerical linear algebra, not Eigen)
     * Used:
        - matrix-matrix, matrix-scalar, matrix-vector operations
        - reduction operations (sum of all elements, product of all elements, minimum/maximum element, trace of a square matrix)
6. Numerical Linear Algebra
     * Used the _Eigen_ library to compute the LU decomposition of a <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;4&space;\times&space;4" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\inline&space;4&space;\times&space;4" title="4 \times 4" /></a> matrix and output the <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;L" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\inline&space;L" title="L" /></a> and <a href="https://www.codecogs.com/eqnedit.php?latex=\inline&space;U" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\inline&space;U" title="U" /></a> triangular matrices
     * Implemented the [Thomas algorithm](https://www.cfd-online.com/Wiki/Tridiagonal_matrix_algorithm_-_TDMA_(Thomas_algorithm)) to solve a discretized 1D heat equation (for one time step)
     * Used the _Eigen_ library to compute the Cholesky decomposition of a matrix; also brushed up on Cholesky decomposition
     * Used the _Eigen_ library to compute the QR decomposition of a matrix; also reviewed QR decomposition
7. Using Monte Carlo methods to price European Options
     * Implemented the analytical method to compute the price of an European option (call and put)
     * Implemented the Monte Carlo method to compute the price of an European option (call and put)
     * Covered the [Box-Muller algorithm](https://en.wikipedia.org/wiki/Box%E2%80%93Muller_transform) to generate a random Normal number
     * Reviewed the risk-neutral pricing of a call option
8. Using 3 different methods to compute the Greeks
     * Implemented the [analytical formulas for the Greeks](https://en.wikipedia.org/wiki/Greeks_(finance)) (European, both call and put)
     * Implemented the analytical formulas for the prices of the call/put options and the finite difference method to compute the Greeks
     * Implemented the Monte Carlo methods to compute prices of the call/put options and the finite differences method to compute the Greeks
9. Computing the price of an Asian option
     * Implemented polymorphism
     * Used Monte Carlo to compute the price of an arithmetic Asian call option
     * Covered Asian options
10. Calculating the implied volatility of an European option
     * Reviewed the [Newton-Raphson](https://en.wikipedia.org/wiki/Newton%27s_method) and [bisection](https://en.wikipedia.org/wiki/Bisection_method) methods
     * Coded up the programs to compute the volatility that would result in the option being priced at the given market price (implied volatility)
     * Covered function pointers in C++
11. Random Number Generators and Statistical Distributions
     * Covered how to generate a random uniform number, using a linear congruential generator
     * Covered how to generate a standard normal distribution (using polymorphism and inheritance)
12.
13.
14.
