---
title: Equals()
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 14
url: /zh/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) 方法




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) 方法


在 C++ 中替代 C# [Object.Equals](../../object/equals/) 调用，适用于任何类型。针对智能指针类型的重载。

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 第一个对象类型。 |
| T2 | 第二个对象类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | 第一个对象。 |
| another | const T2\& | 第二个对象。 |

### 返回值

如果对象被视为相等，则返回 True；否则返回 false。

## ObjectExt::Equals(T, const T2\&) 方法


在 C++ 中替代 C# [Object.Equals](../../object/equals/) 调用，适用于任何类型。针对结构体类型的重载。

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 第一个对象类型。 |
| T2 | 第二个对象类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | T | 第一个对象。 |
| another | const T2\& | 第二个对象。 |

### 返回值

如果对象被视为相等，则返回 True；否则返回 false。

## ObjectExt::Equals(const T\&, const T2\&) 方法


在 C++ 中替代 C# [Object.Equals](../../object/equals/) 调用，适用于任何类型。针对标量类型的重载。

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 第一个对象类型。 |
| T2 | 第二个对象类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | 第一个对象。 |
| another | const T2\& | 第二个对象。 |

### 返回值

如果对象被视为相等，则返回 True；否则返回 false。

## ObjectExt::Equals(const char_t(&), String) 方法


在 C++ 中替代 C# [Object.Equals](../../object/equals/) 调用，适用于任何类型。针对字符串字面量与字符串比较的重载。

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| N | [String](../../string/) 字面量大小。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) 字面量。 |
| another | [String](../../string/) | [String](../../string/)。 |

### 返回值

如果字符串匹配，则返回 True；否则返回 false。

## ObjectExt::Equals(const float\&, const float\&) 方法


模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const **float**\& | 左侧浮点值。 |
| another | const **float**\& | 右侧浮点值。 |

### 返回值

如果 **obj** 和 **another** 均为 NaN 或相等，则返回 True；否则返回 false。

## ObjectExt::Equals(const double\&, const double\&) 方法


模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const **double**\& | 左侧浮点值。 |
| another | const **double**\& | 右侧浮点值。 |

### 返回值

如果 **obj** 和 **another** 均为 NaN 或相等，则返回 True；否则返回 false。

## 另见

* 类 [ObjectExt](../)
* 类 [String](../../string/)
* 结构体 [IsExceptionWrapper](../../isexceptionwrapper/)
* 结构体 [IsSmartPtr](../../issmartptr/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)