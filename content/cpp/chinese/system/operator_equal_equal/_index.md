---
title: operator==()
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 2016
url: /zh/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) 函数




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) 函数




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) 函数




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) 函数


确定指定的 [Nullable](../nullable/) 对象是否表示等于 null 的值。

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | std::nullptr_t | 要测试的 [Nullable](../nullable/) 对象的常量引用 |

### 返回值

如果指定的对象表示 null 值则返回 True，否则返回 false

## System::operator==(const T1\&, const Nullable\<T2\>\&) 函数


通过将 [operator==()](./) 应用于这些值，确定指定的值是否等于由指定的 [Nullable](../nullable/) 对象表示的值。

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 第一个可比较值的类型 |
| T2 | 表示第二个可比较值的 [Nullable](../nullable/) 对象的底层类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| some | const T1\& | 用作第一个可比较值的常量引用 |
| other | const [Nullable](../nullable/)\<T2\>\& | 表示第二个可比较值的 [Nullable](../nullable/) 对象的常量引用 |

### 返回值

如果两个可比较值相等则返回 True，否则返回 false

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) 函数


比较两个智能指针是否相等。

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| X | 第一个指针的被指类型。 |
| Y | 第二个指针的被指类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | 第一个要比较的指针。 |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | 第二个要比较的指针。 |

### 返回值

如果指针匹配则返回 True，否则返回 false。

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) 函数


检查智能指针是否为 null。

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| X | 指针的被指类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | std::nullptr_t | 要检查的指针。 |

### 返回值

如果指针为 null 则返回 True，否则返回 false。

## System::operator==(const SmartPtr\<X\>\&, const Y *) 函数


将智能指针与普通 (C) 指针进行相等比较。

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| X | 智能指针的类型。 |
| Y | 普通指针的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | 要比较的智能指针（左侧）。 |
| y | const Y * | 要比较的普通指针（右侧）。 |

### 返回值

如果指针匹配则返回 True，否则返回 false。

## System::operator==(const X *, const SmartPtr\<Y\>\&) 函数


将智能指针与普通 (C) 指针进行相等比较。

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| X | 普通指针的类型。 |
| Y | 智能指针的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const X * | 要比较的普通指针（右侧）。 |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | 要比较的智能指针（左侧）。 |

### 返回值

如果指针匹配则返回 True，否则返回 false。

## System::operator==(T const\&, std::nullptr_t) 函数


检查值类型对象（已翻译的 C# 结构等）是否为 null。

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 值类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | T const\& | 要检查的 [Object](../object/)。 |

### 返回值

如果对象为 null 则返回 True，否则返回 false。

## System::operator==(std::nullptr_t, T const\&) 函数


检查值类型对象（已翻译的 C# 结构等）是否为 null。

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 值类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | std::nullptr_t | 要检查的 [Object](../object/)。 |

### 返回值

如果对象为 null 则返回 True，否则返回 false。

## System::operator==(Chars\&, const String\&) 函数


[String](../string/) 比较。

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| Chars | [String](../string/) 字面量类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | Chars\& | 要比较的 [String](../string/) 字面量。 |
| right | const [String](../string/)\& | 要比较的 [String](../string/)。 |

### 返回值

如果字符串匹配则返回 true，否则返回 false。

## System::operator==(T\&, const String\&) 函数


[String](../string/) 比较。

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [String](../string/) 指针类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | T\& | 要比较的 [String](../string/) 指针。 |
| right | const [String](../string/)\& | 要比较的 [String](../string/)。 |

### 返回值

如果字符串匹配则返回 true，否则返回 false。

## System::operator==(const SharedPtr\<Object\>\&, const String\&) 函数


[Object](../object/) 与字符串比较。

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | 要转换为字符串并比较的 [Object](../object/)。 |
| right | const [String](../string/)\& | 要比较的 [String](../string/)。 |

### 返回值

如果对象的字符串表示等于该字符串则返回 true，否则返回 false。

## System::operator==(std::nullptr_t, const String\&) 函数


检查字符串是否为 null。

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | std::nullptr_t | 要检查的 [String](../string/)。 |

### 返回值

如果字符串为 null 则返回 true，否则返回 false。

## System::operator==(std::nullptr_t, TimeSpan) 函数




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) 函数


确定当前对象和指定对象表示的 URI 是否相等。

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | 第一个要比较的 [Uri](../uri/) 对象 |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | 第二个要比较的 [Uri](../uri/) 对象 |

### 返回值

如果 URI 相等则返回 True，否则返回 false

## 另请参见

* 类型别名 [SharedPtr](../sharedptr/)
* 类 [ArraySegment](../arraysegment/)
* 类 [DateTime](../datetime/)
* 类 [DateTimeOffset](../datetimeoffset/)
* 类 [Nullable](../nullable/)
* 类 [SmartPtr](../smartptr/)
* 类 [Object](../object/)
* 类 [String](../string/)
* 类 [TimeSpan](../timespan/)
* 类 [Uri](../uri/)
* 结构体 [IsNullable](../isnullable/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)