# cpp_regex_bench
C++ STL and Boost Regular Expression Benchmark

## Benchmark Results

1st column is the timing and 2nd column is number of matches. Not sure why Boost has 5302 matches which is one more than the STL regex.

```
VC++ STL regex
3714.06 - 92
4936.43 - 5301
6576.43 - 5

VC++ boost regex
60.5332 - 92
58.7846 - 5302
12.4496 - 5

clang++ STL regex
364.706 - 92
309.587 - 5301
253.16 - 5

g++ STL regex
398.028 - 92
336.095 - 5301
292.76 - 5
```
