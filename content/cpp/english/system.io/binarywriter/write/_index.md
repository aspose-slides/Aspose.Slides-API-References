---
title: Write()
second_title: Aspose.Slides for C++ API Reference
description: Writes the specified unsigned 8-bit integer value to the output stream.
type: docs
weight: 92
url: /system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) method


Writes the specified unsigned 8-bit integer value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **uint8_t** | The value to write |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) method


Writes the specified subrange of bytes from the specified byte array to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The array containing the bytes to write |
| index | int | A 0-based index of the elemnet in **buffer** at which the subrange to write begins |
| count | int | The number of elements in the subrange to write; -1 specifies that the subrange ends where **buffer** array ends |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) method


Writes the specified subrange of UTF-16 characters from the specified character array to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | The array containing the characters to write |
| index | int | A 0-based index of the elemnet in **buffer** at which the subrange to write begins |
| count | int | The number of characters in the subrange to write; -1 specifies that the subrange ends where **buffer** array ends |

## BinaryWriter::Write(bool) method


Writes single byte with a value of 0 if **value** is 'true' and 1 if **value** is 'false' to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **bool** | The boolean value specifying the byte value to write to the output stream |

## BinaryWriter::Write(char16_t) method


Writes the specified 16-bit wide character value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | char16_t | The value to write |

## BinaryWriter::Write(int16_t) method


Writes the specified 16-bit integer value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **int16_t** | The value to write |

## BinaryWriter::Write(int) method


Writes the specified 32-bit integer value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The value to write |

## BinaryWriter::Write(int64_t) method


Writes the specified 64-bit integer value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **int64_t** | The value to write |

## BinaryWriter::Write(uint16_t) method


Writes the specified unsigned 16-bit integer value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **uint16_t** | The value to write |

## BinaryWriter::Write(uint32_t) method


Writes the specified unsigned 32-bit integer value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **uint32_t** | The value to write |

## BinaryWriter::Write(uint64_t) method


Writes the specified unsigned 64-bit integer value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **uint64_t** | The value to write |

## BinaryWriter::Write(float) method


Writes the specified single-precision floating point value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **float** | The value to write |

## BinaryWriter::Write(double) method


Writes the specified double-precision floating point value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | The value to write |

## BinaryWriter::Write(const Decimal\&) method


Writes the byte representation of the specified [Decimal](../../../system/decimal/) value to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | The value to write |

## BinaryWriter::Write(const String\&) method


Writes a length-prefixed string in the current encoding to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | The string to write |

## BinaryWriter::Write(const char_t *) method


Writes a length-prefixed string in the current encoding to the output stream.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | The c-string to write |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryWriter](../)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)