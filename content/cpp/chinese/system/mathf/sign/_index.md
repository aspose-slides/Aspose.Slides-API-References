---
title: Sign()
second_title: Aspose.Slides C++ API 参考
description: 确定指定有符号整数值的符号。
type: docs
weight: 274
url: /zh/system/mathf/sign/
---
## MathF::Sign(T) 方法


确定指定有符号整数值的符号。

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 整数有符号类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T | 用于确定符号的值 |

### 返回值

如果 **value** 小于 0，则为 -1；如果 **value** 等于 0，则为 0；如果 **value** 大于 0，则为 1

## MathF::Sign(T) 方法


确定指定浮点值的符号。

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 参数的浮点类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T | 用于确定符号的值 |

### 返回值

如果 **value** 小于 0，则为 -1；如果 **value** 等于 0，则为 0；如果 **value** 大于 0，则为 1

## 另请参阅

* Struct [MathF](../)
* 命名空间 [System](../../)
* Library [Aspose.Slides](../../../)