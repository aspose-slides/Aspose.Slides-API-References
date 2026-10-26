---
title: ReferenceEquals()
second_title: Aspose.Slides for C++ API 参考
description: "Object::ReferenceEquals 在字符串和 nullptr 情形下的特化。"
type: docs
weight: 261
url: /zh/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) 方法

针对字符串和 nullptr 的 [Object::ReferenceEquals](./) 的特化。

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) 用于与 nullptr 比较。 |

### 返回值

如果字符串为 null 则返回 true，否则返回 false。

## Object::ReferenceEquals(String const\&, String const\&) 方法

针对字符串的 [Object::ReferenceEquals](./) 的特化。

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | 第一个要比较的字符串。 |
| str2 | [String](../../string/) const\& | 第二个要比较的字符串。 |

### 返回值

如果字符串匹配则返回 true，否则返回 false。

## Object::ReferenceEquals(ptr const\&, ptr const\&) 方法

通过引用比较对象。

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | 第一个要比较的指针。 |
| objB | [ptr](../ptr/) const\& | 第二个要比较的指针。 |

### 返回值

如果指针匹配则返回 True，否则返回 false。

## Object::ReferenceEquals(T const\&, T const\&) 方法

通过引用比较对象。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要比较的对象类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objA | T const\& | 第一个要比较的对象。 |
| objB | T const\& | 第二个要比较的对象。 |

### 返回值

如果对象地址匹配则返回 True，否则返回 false。

## Object::ReferenceEquals(T const\&, std::nullptr_t) 方法

将值类型对象与 nullptr 进行引用比较。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要比较的对象类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objA | T const\& | 第一个要比较的对象。 |

### 返回值

始终返回 false，因为值类型不能为 null。

## 另见

* 类型别名 [ptr](../ptr/)
* 类 [String](../../string/)
* 类 [Object](../)
* 结构体 [IsSmartPtr](../../issmartptr/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)