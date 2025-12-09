FizzBuzz is a very common programming challenge (often used in interviews!)

Here's how it works:

- Write a function called `fizzbuzz` that loops through from 1 up to but not including a number (in this case, we'll go to 20).
- If the number is divisible by 3, print "Fizz"
- If the number is divisible by 5, print "Buzz"
- If the number is divisible by both 3 and 5, print "FizzBuzz"
- If the number is not divisible by 3 or 5, print the number

For example:

```
> fizzbuzz()
```

```
1
```

```
2
```

```
Fizz
```

```
4
```

```
Buzz
```

```
Fizz
```

```
7
```

```
8
```

```
Fizz
```

```
Buzz
```

```
11
```

```
Fizz
```

```
13
```

```
14
```

```
FizzBuzz
```

```
16
```

```
17
```

```
Fizz
```

```
19
```

 

**Hint**: A number x is divisible by a number y if the answer to x / y has a remainder of 0. 

- For example, 10 is divisible by 2 because 10 / 2 = 5 with no remainder. 
- You can check if a number is divisible by another number by checking if x % y === 0.