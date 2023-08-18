---
title: Write()
second_title: Aspose.Slides for C++ API Reference
description: Writes the specified character to the stream.
type: docs
weight: 40
url: /system.io/stringwriter/write/
---
## StringWriter::Write(char_t) method


Writes the specified character to the stream.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | The value to write |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method


Writes the specified subrange of characters from the specified character array to the stream.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | The array containing the characters to write |
| index | **int32_t** | A 0-based index of the elemnet in **buffer** at which the subrange to write begins |
| count | **int32_t** | The number of characters in the subrange to write |

## StringWriter::Write(const String\&) method


Writes the specified string to the stream.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | The string to write |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)