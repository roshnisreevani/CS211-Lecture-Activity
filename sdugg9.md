Name: Hasini Duggirala
Major: Computer Science
Favourite CS Topic: Loops
Challenging Topic: Recursion

int nthFibonacci(int n) {
    // code here
    if(n == 0 || n==1){
        return n;
    }
    // I initially wrote an else, which is not required.
    // I also assigned f(n-1) + f(n-2) to f(n)(I used the actual function name instead of f())
     return nthFibonacci(n - 1) + nthFibonacci(n - 2);
}    