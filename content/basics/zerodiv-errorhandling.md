---
title: Zerodiv-Errorhandling
date: 2025-01-30
author: Your Name
cell_count: 3
score: 0
---

```python
# ZeroDivisionError exception
```


```python
def number(x,y):
    try:
        divide = x / y
        print(f'Result: {divide}')
    except ZeroDivisionError:
        print("Numbers can't divisible by zero")
```


```python
number(10,0)
```

    Numbers can't divisible by zero



---
**Score: 0**
