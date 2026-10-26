---
title: ToString()
second_title: Aspose.Slides for C++ API 参考
description: C# ToString 方法的替代实现，可用于任意 C++ 类型。
type: docs
weight: 27
url: /zh/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) method

C# 的 ToString 方法的替代实现，可用于任意 C++ 类型。

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) 字面值转换为字符串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(const Nullable\<T\>\&) method

C# 的 ToString 方法的替代实现，可用于任意 C++ 类型。

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Nullable](../../nullable/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) 对象转换为字符串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(const T\&) method

C# 的 ToString 方法的替代实现，可用于任意 C++ 类型。

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Enum](../../enum/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) 值转换为字符串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(const T\&) method

C# 的 ToString 方法的替代实现，可用于任意 C++ 类型。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 智能指针类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) 值转换为字符串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(T\&) method

C# 的 ToString 方法的替代实现，可用于任意 C++ 类型。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 智能指针类型或 [ExceptionWrapper](../../exceptionwrapper/)。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | T\& | 智能指针或 [ExceptionWrapper](../../exceptionwrapper/) 转换为字符串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(T\&) method

C# 的 ToString 方法的替代实现，可用于任意 C++ 类型。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 标量类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | T\& | 标量值转换为字符串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(T\&&) method

C# 的 ToString 方法的替代实现，可用于任意 C++ 类型。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 标量类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | T\&& | 标量值转换为字符串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(T\&) method

C# 的 ToString 方法的替代实现，可用于任意 C++ 类型。

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 结构体类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | T\& | 结构体值转换为字符串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(const T\&) method

C# 的 ToString 方法的替代实现，可用于任意 C++ 类型。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 结构体类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | 结构体值转换为字符串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(T\&&) method

C# 的 ToString 方法的替代实现，可用于任意 C++ 类型。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 标量类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | T\&& | 标量值转换为字符串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## See Also

* 类 [String](../../string/)
* 类 [ObjectExt](../)
* 类 [Nullable](../../nullable/)
* 结构体 [IsSmartPtr](../../issmartptr/)
* 结构体 [IsExceptionWrapper](../../isexceptionwrapper/)
* 结构体 [IsNullable](../../isnullable/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)