---
title: String()
second_title: Aspose.Slides for C++ API Reference
description: Default constructor. Creates string object which is considered null.
type: docs
weight: 1
url: /cpp/system/string/string/
---
## String::String() constructor


Default constructor. Creates string object which is considered null.

```cpp
System::String::String()
```

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(T\&, typename std::enable_if\<[IsStringLiteral](../../isstringliteral/)\<T, char16_t\>::value\>::type *) constructor


Constructs string based on string literal. Considers literal a null-terminated string, calculates target string length based on literal size.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | T\& | [String](../) literal pointer. |

## See Also

* Struct [IsStringLiteral](../../isstringliteral/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const T\&, typename std::enable_if\<[IsStringPointer](../../isstringpointer/)\<T, char16_t\>::value\>::type *) constructor


Constructs string based on character string pointer. Treats pointed string as null-terminated, calculates target string length based on null character.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | Character string pointer. |

## See Also

* Struct [IsStringPointer](../../isstringpointer/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(T\&, typename std::enable_if\<[IsStringLiteral](../../isstringliteral/)\<T, char\>::value\>::type *) constructor


Constructs string based on string literal. Considers literal a null-terminated string in UTF8, calculates target string length based on literal size.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | T\& | [String](../) literal pointer. |

## See Also

* Struct [IsStringLiteral](../../isstringliteral/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const T\&, typename std::enable_if\<[IsStringPointer](../../isstringpointer/)\<T, char\>::value\>::type *) constructor


Constructs string based on character string pointer. Treats pointed string as null-terminated in UTF8, calculates target string length based on null character.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | Character string pointer. |

## See Also

* Struct [IsStringPointer](../../isstringpointer/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const char16_t *, int) constructor


Constructs string from character string pointer and explicit length.

```cpp
System::String::String(const char16_t *str, int length)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char16_t * | [String](../) pointer, may be literal or array. |
| length | int | Explicit string length |

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const char *, int) constructor


Constructs string from character string pointer and explicit length.

```cpp
System::String::String(const char *str, int length)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char * | [String](../) pointer to the UTF8 data, may be literal or array. |
| length | int | Explicit string length |

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const char16_t *, int, int) constructor


Constructs string from character string pointer from starting position using length.

```cpp
System::String::String(const char16_t *str, int start, int length)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char16_t * | [String](../) pointer, may be literal or array. |
| start | int | Starting position. |
| length | int | [String](../) length. |

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const char16_t, int) constructor


Fill constructor.

```cpp
System::String::String(const char16_t ch, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ch | const char16_t | Fill character. |
| count | int | Target length. |

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) constructor


Nullptr constructor. Declared as template to resolve priorities with other template constructors.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Should be nullptr_t |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | nullptr |

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(T\&, typename std::enable_if\<[IsStringLiteral](../../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) constructor


Constructs string based on widestring literal. Considers literal a null-terminated string, calculates target string length based on literal size. Conversion from **wchar_t** is time-consuming on some platforms, so no implicit conversions are allowed.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | T\& | [String](../) literal pointer. |

## See Also

* Struct [IsStringLiteral](../../isstringliteral/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const T\&, typename std::enable_if\<[IsStringPointer](../../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) constructor


Constructs string based on widecharacter string pointer. Treats pointed string as null-terminated, calculates target string length based on null character. Conversion from **wchar_t** is time-consuming on some platforms, so no implicit conversions are allowed.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | Character string pointer. |

## See Also

* Struct [IsStringPointer](../../isstringpointer/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const **wchar_t** *, int) constructor


Constructs string from widecharacter string pointer and explicit length. Conversion from **wchar_t** is time-consuming on some platforms, so no implicit conversions are allowed.

```cpp
System::String::String(const wchar_t *str, int length)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) pointer, may be literal or array. |
| length | int | Explicit string length |

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const **wchar_t**, int) constructor


Fill constructor. Conversion from **wchar_t** is time-consuming on some platforms, so no implicit conversions are allowed.

```cpp
System::String::String(const wchar_t ch, int count=1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ch | const **wchar_t** | Fill character. |
| count | int | Target length. |

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const [String](../)\&) constructor


Copy constructor.

```cpp
System::String::String(const String &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) to copy. |

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String([String](../)\&&) constructor


Move constructor.

```cpp
System::String::String(String &&str) noexcept
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) to move data from. |

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const [ArrayPtr](../../arrayptr/)\<char16_t\>\&) constructor


Converts whole character array to string.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) to convert to string. |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const [ArrayPtr](../../arrayptr/)\<char16_t\>\&, int, int) constructor


Converts character array subrange to string. If parameters are out of array bounds, empty string is constructed.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Character array. |
| offset | int | Subarray start index. |
| len | int | Subarray length. |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const icu::UnicodeString\&) constructor


Wraps UnicodeString into [String](../).

```cpp
System::String::String(const icu::UnicodeString &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const icu::UnicodeString\& | UnicodeString to wrap into [String](../). |

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(icu::UnicodeString\&&) constructor


Move constructor.

```cpp
System::String::String(icu::UnicodeString &&str) noexcept
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | icu::UnicodeString\&& | UnicodeString to wrap into [String](../). |

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const std::wstring\&) constructor


Creates [String](../) from widestring.

```cpp
System::String::String(const std::wstring &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const std::wstring\& | Widestring to convert into [String](../). |

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const std::u16string\&) constructor


Creates [String](../) from utf16 string.

```cpp
System::String::String(const std::u16string &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const std::u16string\& | Utf16 string to convert into [String](../). |

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const std::string\&) constructor


Creates [String](../) from std::string string presented in format UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| utf8str | const std::string\& | std::string string to convert into [String](../). |

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## String::String(const std::u32string\&) constructor


Creates [String](../) from std::u32string string.

```cpp
System::String::String(const std::u32string &u32str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string string to convert into [String](../). |

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
