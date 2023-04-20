---
title: Write()
second_title: Aspose.Slides for C++ API Reference
description: Writes the string representation of the specified object to the stream.
type: docs
weight: 105
url: /cpp/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) method


Writes the string representation of the specified object to the stream.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | The object to write |

## TextWriter::Write(bool) method


Writes the string representation of the specified boolean value to the stream.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **bool** | The value to write |

## TextWriter::Write(char_t) method


Writes the specified character to the stream.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | The value to write |

## TextWriter::Write(Decimal) method


Writes the string representation of the specified [Decimal](../../../system/decimal/) object to the stream.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | The object to write |

## TextWriter::Write(double) method


Writes the string representation of the specified double-precision floating point value to the stream.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | The value to write |

## TextWriter::Write(int) method


Writes the string representation of the specified 32-bit integer value to the stream.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The value to write |

## TextWriter::Write(int64_t) method


Writes the string representation of the specified 64-bit integer value to the stream.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **int64_t** | The value to write |

## TextWriter::Write(float) method


Writes the string representation of the specified single-precision floating point value to the stream.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **float** | The value to write |

## TextWriter::Write(const String\&) method


Writes the specified string to the stream.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | The string to write |

## TextWriter::Write(uint32_t) method


Writes the string representation of the specified unsigned 32-bit integer value to the stream.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **uint32_t** | The value to write |

## TextWriter::Write(uint64_t) method


Writes the string representation of the specified unsigned 64-bit integer value to the stream.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **uint64_t** | The value to write |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) method


Writes all characetrs from the specified array to the stream.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | The array containing the characters to write |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method


Writes the specified subrange of UTF-16 characters from the specified character array to the stream.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | The array containing the characters to write |
| index | **int32_t** | A 0-based index of the elemnet in **buffer** at which the subrange to write begins |
| count | **int32_t** | The number of characters in the subrange to write; -1 specifies that the subrange ends where **buffer** array ends |

## TextWriter::Write(const char_t *) method


Writes the specified c-string to the stream.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | The c-string to write |

## TextWriter::Write(const TypeInfo\&) method


Writes the string representation of the specified [TypeInfo](../../../system/typeinfo/) object to the stream.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | The object to write |

## TextWriter::Write(const String\&, const TArgs\&...) method


Writes the specified values formatted according to the specified format to the stream.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TArgs | The list of types of values to write |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | The string format |
| args | const TArgs\&... | The values to write |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [TextWriter](../)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)