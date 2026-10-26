---
title: Sign()
second_title: Aspose.Slides C++ API 参考
description: 确定指定的带符号整数值的符号。
type: docs
weight: 274
url: /zh/system/math/sign/
---
## Math::Sign(T) 方法

确定指定的带符号整数值的符号。

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 整数带符号类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T | 要确定符号的值 |

### 返回值

- 1 如果 **value** 小于 0； 0 如果 **value** 等于 0； 1 如果 **value** 大于 0

## Math::Sign(T) 方法

确定指定的浮点值的符号。

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 参数的浮点类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T | 要确定符号的值 |

### 返回值

- 1 如果 **value** 小于 0； 0 如果 **value** 等于 0； 1 如果 **value** 大于 0

## Math::Sign(const Decimal\&) 方法

确定指定的十进制值的符号。

```cpp
static int System::Math::Sign(const Decimal &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | 要确定符号的值 |

### 返回值

- 1 如果 **value** 小于 0； 0 如果 **value** 等于 0； 1 如果 **value** 大于 0

## 参见

* 类 [Decimal](../../decimal/)
* 结构体 [Math](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)