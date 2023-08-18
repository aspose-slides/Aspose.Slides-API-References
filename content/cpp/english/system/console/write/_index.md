---
title: Write()
second_title: Aspose.Slides for C++ API Reference
description: Outputs the string representation of the specified object to the standard output stream.
type: docs
weight: 1
url: /system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) method


Outputs the string representation of the specified object to the standard output stream.

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type of the object to output |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) to output |

## Console::Write(bool) method


Outputs the string representation of bool value to the standard output stream.

```cpp
static void System::Console::Write(bool value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **bool** | The value to output |

## Console::Write(char_t) method


Outputs the specified character value to the standard output stream.

```cpp
static void System::Console::Write(char_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | The value to output |

## Console::Write(const ArrayPtr\<char_t\>\&) method


Outputs the string representation of the specified character array to the standard output stream.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | The array to output |

## Console::Write(const Decimal\&) method


Outputs the string representation of [Decimal](../../decimal/) value to the standard output stream.

```cpp
static void System::Console::Write(const Decimal &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | The value to output |

## Console::Write(double) method


Outputs the string representation of double-precision floating-point value to the standard output stream.

```cpp
static void System::Console::Write(double value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | The value to output |

## Console::Write(float) method


Outputs the string representation of single-precision floating-point value to the standard output stream.

```cpp
static void System::Console::Write(float value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **float** | The value to output |

## Console::Write(int32_t) method


Outputs the string representation of 32-bit integer value to the standard output stream.

```cpp
static void System::Console::Write(int32_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **int32_t** | The value to output |

## Console::Write(int64_t) method


Outputs the string representation of 64-bit integer value to the standard output stream.

```cpp
static void System::Console::Write(int64_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **int64_t** | The value to output |

## Console::Write(const String\&) method


Outputs the specified string object to the standard output stream.

```cpp
static void System::Console::Write(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string object to output |

## Console::Write(const char_t *) method


Outputs the specified c-string to the standard output stream.

```cpp
static void System::Console::Write(const char_t *value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | The c-string to output |

## Console::Write(const TypeInfo\&) method


Outputs the string representation of [TypeInfo](../../typeinfo/) value to the standard output stream.

```cpp
static void System::Console::Write(const TypeInfo &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | The value to output |

## Console::Write(uint32_t) method


Outputs the string representation of unsigned 32-bit integer value to the standard output stream.

```cpp
static void System::Console::Write(uint32_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **uint32_t** | The value to output |

## Console::Write(uint64_t) method


Outputs the string representation of unsigned 64-bit integer value to the standard output stream.

```cpp
static void System::Console::Write(uint64_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **uint64_t** | The value to output |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method


Outputs the string representation of the specified range of the specified character array to the standard output stream.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | The character array |
| index | **int32_t** | The index in the array at which the range to output begins |
| count | **int32_t** | The number of elements in the range to output |

## Console::Write(const String\&, Args\&&...) method


Outputs the string representation of the specified arguments formatted according to the specified format to the standard output stream.

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| The | types of the values to output |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | The string format |
| args | Args\&&... | The values to output |

## Console::Write(const char *) method




```cpp
static void System::Console::Write(const char *)=delete
```

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Console](../)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)