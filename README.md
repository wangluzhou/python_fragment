# python问题碎片化整理
## E731 do not assign a lambda expression, use a def
PEP8又爆出了新的问题。
如果你输入：
```
f = lambda x : x**2
```
就会产生这样的提示。
