# Split 함수
- String Type의 값을 나눠서 리스트 형태로 변환
```py
items = 'zero one two three'.split()
print(items)
>>> ['zero', 'one', 'two', 'three']

example = 'python,jquery,javascript'
example.split(",")
print(example)
>>> ['python', 'jquery', 'javascript']
a, b, c = example.split(",")
>>> a = 'python'
>>> b = 'jquery'
>>> c = 'javascript'
```

# Join 함수
- String list를 합쳐 하나의 string으로 반환할 수 있음.
```py
colors = ['red', 'blue', 'green', 'yellow']
result = ''.join(colors)
>>> result
'redbluegreenyellow'

result = ' '.join(colors)
>>> result
'red blue green yellow'

result = ', '.join(colors)
>>> result
'red, blue, green, yellow'

result = '-'.join(colors)
>>> result
'red-blue-green-yellow'
```

