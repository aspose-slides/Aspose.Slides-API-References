---
title: Format()
second_title: Aspose.Slides for C++ API Reference
description: Formats string in C# style.
type: docs
weight: 846
url: /cpp/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) method


Formats string in C# style.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Args | Arguments to format string. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider to use to convert arguments to strings. |
| format | const [String](../)\& | Format string. |
| args | const Args\&... | Arguments to format string. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) method


Formats string in C# style.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Args | Arguments to format string. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | std::nullptr_t | Format string. |
| args | const [String](../)\& | Arguments to format string. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) method


Formats string in C# style.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Args | Arguments to format string. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | std::nullptr_t | Format string. |
| args | const char16_t(&) | Arguments to format string. |

## String::Format(const String\&, const Args\&...) method


Formats string in C# style.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Args | Arguments to format string. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../)\& | Format string. |
| args | const Args\&... | Arguments to format string. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) method


Formats string in C# style.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Arguments to format string. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../)\& | Format string. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | Arguments to format string. |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)