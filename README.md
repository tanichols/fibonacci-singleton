# Fibonacci
compute optimized utility to generate Fibonacci sequence(s). The library is implemented as a singleton and will not compute values that have already been computed.

## Usage

1. Import the utility into your codebase

```
import Fibonacci from 'fibonacci'
const Fibonacci = require('fibonacci')
```

2. Generate Sequences

```
Fibonacci.getSequence(7)
[0, 1, 1, 2, 3, 5, 8]

Fibonacci.getSequence(2)
[0, 1]
```
