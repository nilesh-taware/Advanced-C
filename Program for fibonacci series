void generate_fibonaccis(int n, uint64_t *fib) {
    fib[0] = 1;
    fib[1] = 1;
    for (int i = 2; i < n; ++i) {
        fib[i] = fib[i - 2] + fib[i - 1];
    }
}

int main() {
    int n = 10;
    uint64_t fib[1000];
    generate_fibonaccis(n, fib);
    for (int i = 0; i < n; i++) {
        printf("%ju ", fib[i]);
    }
    return 0;
}
