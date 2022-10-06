# Enums iterations
Example Enum:
```cpp
Enum MyEnum {
  First = -1111,
  Second,
  Third,
  LastEnum
}

const MyEnum[] myEnums = {MyEnum.First, MyEnum.Second, MyEnum.Third, MyEnum.LastEnum};

```
## Method 1
```cpp
int first = MyEnum.First;
int last = MyEnum.LastEnum;
for (int i = first; i < last; i++) {
  
}
```
