---
title: Equals()
second_title: Aspose.Slides for C++ API 参考
description: 使用 C# Object.Equals 语义比较对象。
type: docs
weight: 157
url: /zh/system/object/equals/
---
## Object::Equals(ptr) 方法


使用 C# [Object.Equals](./) 语义比较对象。

```cpp
virtual bool System::Object::Equals(ptr obj)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) 用于比较当前对象。 |

### 返回值

如果对象被视为相等则返回 True，否则返回 false。

## Object::Equals(T1 const\&, T2 const\&) 方法


在 C# 样式中比较引用类型对象。

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 用于比较的第一个对象的类型。 |
| T2 | 用于比较的第二个对象的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objA | T1 const\& | 要比较的第一个对象。 |
| objB | T2 const\& | 要比较的第二个对象。 |

### 返回值

如果对象通过引用或语义（类似 [Object.Equals](./) 的比较）匹配则返回 True，否则返回 false。

## Object::Equals(T1 const\&, T2 const\&) 方法


在 C# 样式中比较值类型对象。

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 用于比较的第一个对象的类型。 |
| T2 | 用于比较的第二个对象的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objA | T1 const\& | 要比较的第一个对象。 |
| objB | T2 const\& | 要比较的第二个对象。 |

### 返回值

如果对象通过可用的等号运算符被视为相等则返回 True，否则返回 false。

## Object::Equals(float const\&, float const\&) 方法


模拟 C# 样式的浮点数比较，即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），这里两个 NaN 也被视为相等。

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objA | **float** const\& | 左侧浮点数值。 |
| objB | **float** const\& | 右侧浮点数值。 |

### 返回值

如果 **objA** 和 **objB** 均为 NaN 或相等则返回 True，否则返回 false。

## Object::Equals(double const\&, double const\&) 方法


模拟 C# 样式的浮点数比较，即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），这里两个 NaN 也被视为相等。

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objA | **double** const\& | 左侧浮点数值。 |
| objB | **double** const\& | 右侧浮点数值。 |

### 返回值

如果 **objA** 和 **objB** 均为 NaN 或相等则返回 True，否则返回 false。

## 另请参见

* 类型定义 [ptr](../ptr/)
* 类 [Object](../)
* 结构体 [IsSmartPtr](../../issmartptr/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)