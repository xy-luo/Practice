# Array

**增**
```python
lst = []
lst.append(val)   # add an element to the end of list
lst.extend(lst2)   # add another list to the end of list
```

**删**
```python

lst.remove(val)   # remove first occurence of the val
del(lst[idx])   # delete element at a specific index
lst.pop()   # remove the last element

```

**查**
```python

lst[idx]
lst[0]
lst[-1]

```

**改**
```python

lst[idx] = val

```

**遍历 iterable**
```python

# iterate on list
for val in lst:

```

**Slicing**
```python

lst[start:end:step]   # [start, end) end cannot be arrive, 走step步取1次

```

**Otehr function**
```python
# get length of a list
len(lst)

# to string
"".join(lst)   # 用引号内的元素把lst中每个元素连接起来
```
