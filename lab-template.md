---
title: Python Lab
subtitle: Working with Functions
accent: #0D9488
locale: en
---

# Objective

In this lab you'll learn to define and call **functions** in Python.
Functions let you package logic so it can be reused. Complete each
step and run your code in the editor on the right.

# Steps

## Define a function

Define a function called `greet` that takes one parameter `name`
and prints `Hello, <name>!`.

```
def greet(name):
    print(f"Hello, {name}!")
```

## Call the function

Call `greet` with your own name as the argument.

```
greet("Ada")
```

## Return a value

Write a function `square(n)` that **returns** `n * n`,
then print `square(5)`. (No hint on this one.)

# Extensions

## Default arguments

Give `greet` a default value so calling it with no argument still works.

## Multiple returns

Write `min_max(numbers)` that returns both the smallest and largest values in a list.
