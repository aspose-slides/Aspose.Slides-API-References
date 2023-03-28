---
title: Append()
second_title: Aspose.Slides for C++ API Reference
description: Adds character to builder.
type: docs
weight: 118
url: /cpp/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) method


Adds character to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Character value. |

### Return Value

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## StringBuilder::Append(char_t, int) method


Adds characters to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Character value. |
| count | int | How many times to repeat insertee character. |

### Return Value

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## StringBuilder::Append(const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\&) method


Adds characters array to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Characters to add. |

### Return Value

This pointer.

## See Also

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## StringBuilder::Append(const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\&, int, int) method


Adds characters array slice to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Characters to add. |
| startIndex | int | Slice beginning index. |
| charCount | int | Slice length. |

### Return Value

This pointer.

## See Also

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## StringBuilder::Append(const [String](../../../system/string/)\&) method


Adds string to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) to add. |

### Return Value

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## StringBuilder::Append(const [String](../../../system/string/)\&, int, int) method


Adds string slice to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) to add. |
| startIndex | int | Slice beginning index. |
| charCount | int | Slice length. |

### Return Value

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## StringBuilder::Append(const [SharedPtr](../../../system/sharedptr/)\<T\>\&) method


Adds object's string representation to builder.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../../system/object/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) to serialize and add. |

### Return Value

This pointer.

## See Also

* Class [StringBuilder](../)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## StringBuilder::Append(const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\&) method


Adds builder's content to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | Builder to add content from. |

### Return Value

This pointer.

## See Also

* Class [StringBuilder](../)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## StringBuilder::Append(**float**) method


Adds floating point value to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| f | **float** | Value to serialize and add. |

### Return Value

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## StringBuilder::Append(**double**) method


Adds floating point value to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| df | **double** | Value to serialize and add. |

### Return Value

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## StringBuilder::Append(int) method


Adds integer value to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | int | Value to serialize and add. |

### Return Value

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## StringBuilder::Append(T) method


Adds arithmetic value to builder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Arithmetic type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | Value to serialize and add. |

### Return Value

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## StringBuilder::Append(E) method


Adds enum value string representation to builder.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| E | [Enum](../../../system/enum/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| e | E | Value to serialize and add. |

### Return Value

This pointer.

## See Also

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
