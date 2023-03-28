---
title: Write()
second_title: Aspose.Slides for C++ API Reference
description: Writes the specified character to the stream.
type: docs
weight: 79
url: /cpp/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) method


Writes the specified character to the stream.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | The character to write |

## See Also

* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamWriter::Write(const [String](../../../system/string/)\&) method


Writes the specified string to the stream.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | The string to write |

## See Also

* Class [String](../../../system/string/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamWriter::Write(const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\&) method


Writes the string representation of the specified object to the stream.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | The object to write |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamWriter::Write(const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\&) method


Writes all characetrs from the specified array to the stream.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | The array containing the characters to write |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamWriter::Write(const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) method


Writes the specified subrange of UTF-16 characters from the specified character array to the stream.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | The array containing the characters to write |
| index | **int32_t** | A 0-based index of the elemnet in **buffer** at which the subrange to write begins |
| count | **int32_t** | The number of characters in the subrange to write; -1 specifies that the subrange ends where **buffer** array ends |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamWriter::Write(const char_t *) method


Writes the specified c-string to the stream.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const char_t * | The c-string to write |

## See Also

* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamWriter::Write(const [System::SharedPtr](../../../system/sharedptr/)\<T\>\&) method


Writes the string representation of the specified object to the stream.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of the object |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | The object to write |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
