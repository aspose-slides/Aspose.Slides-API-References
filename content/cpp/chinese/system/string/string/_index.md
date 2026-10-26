---
title: String()
second_title: Aspose.Slides for C++ API 参考
description: 默认构造函数。创建被视为 null 的字符串对象。
type: docs
weight: 14
url: /zh/system/string/string/
---
## String::String() 构造函数

默认构造函数。创建被视为 null 的字符串对象。

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) 构造函数

基于字符串字面量构造字符串。将字面量视为以 null 结尾的字符串，依据字面量大小计算目标字符串长度。

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T\& | [String](../) 字面量指针。 |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) 构造函数

基于字符字符串指针构造字符串。将指向的字符串视为以 null 结尾，根据 null 字符计算目标字符串长度。

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | 字符字符串指针。 |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) 构造函数

基于字符串字面量构造字符串。将字面量视为 UTF8 编码的以 null 结尾的字符串，依据字面量大小计算目标字符串长度。

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T\& | [String](../) 字面量指针。 |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) 构造函数

基于字符字符串指针构造字符串。将指向的字符串视为 UTF8 编码的以 null 结尾，根据 null 字符计算目标字符串长度。

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | 字符字符串指针。 |

## String::String(const char16_t *, int) 构造函数

根据字符字符串指针和显式长度构造字符串。

```cpp
System::String::String(const char16_t *str, int length)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const char16_t * | [String](../) 指针，可为字面量或数组。 |
| length | int | 显式字符串长度。 |

## String::String(const ReadOnlySpan\<char16_t\>\&) 构造函数

使用指定只读跨度中指示的 Unicode 字符初始化 [System.String](../) 类的新实例。

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Unicode 字符的只读跨度。 |

## String::String(const char *, int) 构造函数

根据字符字符串指针和显式长度构造字符串。

```cpp
System::String::String(const char *str, int length)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const char * | [String](../) 指向 UTF8 数据的指针，可为字面量或数组。 |
| length | int | 显式字符串长度。 |

## String::String(const char16_t *, int, int) 构造函数

根据字符字符串指针、起始位置和长度构造字符串。

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const char16_t * | [String](../) 指针，可为字面量或数组。 |
| start | int | 起始位置。 |
| length | int | [String](../) 长度。 |

## String::String(const char16_t, int) 构造函数

填充构造函数。

```cpp
System::String::String(const char16_t ch, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ch | const char16_t | 填充字符。 |
| count | int | 目标长度。 |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) 构造函数

nullptr 构造函数。声明为模板以解决与其他模板构造函数的优先级冲突。

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 应为 nullptr_t |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) 构造函数

基于宽字符串字面量构造字符串。将字面量视为以 null 结尾的字符串，依据字面量大小计算目标字符串长度。某些平台上从 **wchar_t** 的转换耗时较长，因而不允许隐式转换。

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T\& | [String](../) 字面量指针。 |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) 构造函数

基于宽字符字符串指针构造字符串。将指向的字符串视为以 null 结尾，依据 null 字符计算目标字符串长度。某些平台上从 **wchar_t** 的转换耗时较长，因而不允许隐式转换。

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | 字符字符串指针。 |

## String::String(const wchar_t *, int) 构造函数

根据宽字符字符串指针和显式长度构造字符串。某些平台上从 **wchar_t** 的转换耗时较长，因而不允许隐式转换。

```cpp
System::String::String(const wchar_t *str, int length)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) 指针，可为字面量或数组。 |
| length | int | 显式字符串长度。 |

## String::String(const wchar_t, int) 构造函数

填充构造函数。某些平台上从 **wchar_t** 的转换耗时较长，因而不允许隐式转换。

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ch | const **wchar_t** | 填充字符。 |
| count | int | 目标长度。 |

## String::String(const String\&) 构造函数

拷贝构造函数。

```cpp
System::String::String(const String &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 用于拷贝。 |

## String::String(String\&&) 构造函数

移动构造函数。

```cpp
System::String::String(String &&str) noexcept
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) 用于移动数据。 |

## String::String(const ArrayPtr\<char16_t\>\&) 构造函数

将整个字符数组转换为字符串。

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) 用于转换为字符串。 |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) 构造函数

将字符数组子范围转换为字符串。如果参数超出数组边界，则构造空字符串。

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | 字符数组。 |
| offset | int | 子数组起始索引。 |
| len | int | 子数组长度。 |

## String::String(const codeporting_icu::UnicodeString\&) 构造函数

将 UnicodeString 包装为 [String](../)。

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString 用于包装为 [String](../)。 |

## String::String(codeporting_icu::UnicodeString\&&) 构造函数

移动构造函数。

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString 用于包装为 [String](../)。 |

## String::String(const std::wstring\&) 构造函数

从宽字符串创建 [String](../)。

```cpp
System::String::String(const std::wstring &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const std::wstring\& | 宽字符串用于转换为 [String](../)。 |

## String::String(const std::u16string\&) 构造函数

从 utf16 字符串创建 [String](../)。

```cpp
System::String::String(const std::u16string &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const std::u16string\& | utf16 字符串用于转换为 [String](../)。 |

## String::String(const std::string\&) 构造函数

从 UTF-8 格式的 std::string 字符串创建 [String](../)。

```cpp
System::String::String(const std::string &utf8str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| utf8str | const std::string\& | std::string 字符串用于转换为 [String](../)。 |

## String::String(const std::u32string\&) 构造函数

从 std::u32string 字符串创建 [String](../)。

```cpp
System::String::String(const std::u32string &u32str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string 字符串用于转换为 [String](../)。 |

## 另见

* 类型别名 [ArrayPtr](../../arrayptr/)
* 类 [String](../)
* 类 [ReadOnlySpan](../../readonlyspan/)
* 结构体 [IsStringLiteral](../../isstringliteral/)
* 结构体 [IsStringPointer](../../isstringpointer/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)