---
title: operator+()
second_title: Aspose.Slides for C++ API 参考
description: 返回 Decimal 类的新实例，该实例表示指定值与指定 Decimal 对象表示的值之和。
type: docs
weight: 2159
url: /zh/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) 函数


返回 [Decimal](../decimal/) 类的新实例，该实例表示指定值与指定 [Decimal](../decimal/) 对象表示的值之和。

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const T\& | 第一个加数 |
| d | const [Decimal](../decimal/)\& | 对表示第二个加数的 [Decimal](../decimal/) 对象的常量引用 |

### 返回值

返回 [Decimal](../decimal/) 类的新实例，该实例表示 **x** 与 **d** 所表示的值之和。

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) 函数


将右侧委托的所有回调连接到左侧委托回调列表的末尾。

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | 添加回调的委托。 |
| rhv | MulticastDelegate\<T\> | 其回调被添加的委托。 |

### 返回值

返回一个委托，其中包含左侧值的回调，然后是右侧值的回调。

## System::operator+(const T1\&, const Nullable\<T2\>\&) 函数


对非空和可空值进行求和。

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左操作数类型。 |
| T2 | 右操作数类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| some | const T1\& | 左操作数。 |
| other | const [Nullable](../nullable/)\<T2\>\& | 右操作数。 |

### 返回值

求和结果。

## System::operator+(T\&, const String\&) 函数


[String](../string/) 连接。

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [String](../string/) 文字字面量类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | T\& | 要连接到字符串的文字。 |
| right | const [String](../string/)\& | [String](../string/) 用于连接。 |

### 返回值

连接后的字符串。

## System::operator+(T\&, const String\&) 函数


[String](../string/) 连接。

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [String](../string/) 指针类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | T\& | [String](../string/) 指针用于连接到字符串。 |
| right | const [String](../string/)\& | [String](../string/) 用于连接。 |

### 返回值

连接后的字符串。

## System::operator+(const char_t, const String\&) 函数


[String](../string/) 连接。

```cpp
String System::operator+(const char_t left, const String &right)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | const char_t | 要连接到字符串的字符。 |
| right | const [String](../string/)\& | [String](../string/) 用于连接。 |

### 返回值

连接后的字符串。

## 另见

* 类 [Decimal](../decimal/)
* 类 [Nullable](../nullable/)
* 类 [String](../string/)
* 结构体 [IsStringLiteral](../isstringliteral/)
* 结构体 [IsStringPointer](../isstringpointer/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)