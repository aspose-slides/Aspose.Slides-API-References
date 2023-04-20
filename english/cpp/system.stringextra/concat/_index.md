---
title: Concat()
second_title: Aspose.Slides for C++ API Reference
description: Concatenates string array.
type: docs
weight: 1
url: /cpp/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) function


Concatenates string array.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) of strings to join. |

### Return Value

Joint string.

## System::StringExtra::Concat(const String\&, const String\&) function


Concatenates strings.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | First string to concatenate. |
| str1 | const [String](../../system/string/)\& | Second string to concatenate. |

### Return Value

Joint parameter strings.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) function


Concatenates strings.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | First string to concatenate. |
| str1 | const [String](../../system/string/)\& | Second string to concatenate. |
| str2 | const [String](../../system/string/)\& | Third string to concatenate. |

### Return Value

Joint parameter strings.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) function


Concatenates strings.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | First string to concatenate. |
| str1 | const [String](../../system/string/)\& | Second string to concatenate. |
| str2 | const [String](../../system/string/)\& | Third string to concatenate. |
| str3 | const [String](../../system/string/)\& | Fourth string to concatenate. |

### Return Value

Joint parameter strings.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function


Converts multiple objects to string and concatenates resulting strings. Specialization for [SmartPtr](../../system/smartptr/) types.

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) to convert and join. |

### Return Value

[String](../../system/string/) value joint from string representations of all objects passed.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function


Converts multiple objects to string and concatenates resulting strings. Specialization for arithmetic types.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) to convert and join. |

### Return Value

[String](../../system/string/) value joint from string representations of all objects passed.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function


Converts multiple objects to string and concatenates resulting strings. Specialization for structures and other value types.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) to convert and join. |

### Return Value

[String](../../system/string/) value joint from string representations of all objects passed.

## See Also

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [String](../../system/string/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::StringExtra](../)
* Library [Aspose.Slides](../../)