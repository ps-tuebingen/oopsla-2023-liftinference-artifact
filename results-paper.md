| **Benchmark**         | **Eff**               | **OCaml**            | **Koka**           | **Effekt**          | **Baseline**        |
|-----------------------|-----------------------|----------------------|--------------------|---------------------|---------------------|
| Countdown (200M)      | 72.0 (± 13.2)         | 1976.1 (± 26.6)      | 1598.0 (± 24.0)    | 44.5 (± 1.0)        | **44.5** (± 0.9)    |
| Fibonacci (42)        | **1093.6** (± 5.5)    | 1161.5 (± 12.0)      | 1222.6 (± 27.0)    | 1335.4 (± 12.0)     | 1335.4 (± 24.5)     |
| Product Early (100k)  | 535.7 (± 71.9)        | **113.0** (± 0.4)    | 1506.6 (± 20.0)    | 238.2 (± 33.4)      | 113.0 (± 0.9)       |
| Iterator (40M)        | 516.3 (± 17.6)        | 195.4 (± 1.3)        | 1082.0 (± 9.6)     | 92.5 (± 10.7)       | **13.7** (± 0.5)    |
| Queens (12)           | 262.2 (± 6.1)         | 635.6 (± 1.8)        | 2643.5 (± 26.6)    | 117.2 (± 0.3)       | **96.6** (± 1.0)    |
| Tree Explore (16)     | 161.1 (± 3.8)         | **142.9** (± 2.2)    | 278.4 (± 5.1)      | 187.1 (± 4.4)       | 179.1 (± 2.0)       |
| Triples (300)         | 125.0 (± 4.4)         | 315.5 (± 3.3)        | 2635.8 (± 11.4)    | 30.0 (± 0.5)        | **25.1** (± 0.4)    |
| Resume Non-tail (10k) | 182.4 (± 15.9)        | 190.4 (± 1.0)        | 1601.5 (± 16.6)    | 85.9 (± 3.5)        | **62.5** (± 3.0)    |
| Parsing (20k)         | 2061.7 (± 177.3)      | 1443.5 (± 14.6)      | 3220.4 (± 253.6)   | 88.6 (± 0.8)        | **88.1** (± 1.0)    |
