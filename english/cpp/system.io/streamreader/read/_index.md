---
title: Read()
second_title: Aspose.Slides for C++ API Reference
description: Reads a single character from the stream.
type: docs
weight: 40
url: /cpp/system.io/streamreader/read/
---
## StreamReader::Read() method


Reads a single character from the stream.

```cpp
virtual int System::IO::StreamReader::Read() override
```


### Return Value

Read character encoded with UTF-16 encoding; if the read character is represented by two codepoints in UTF-16 encoding then only the high surragate is returned.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) method


Reads the specified number of characters from the stream, converts them to UTF-16 encoding and writes the resulting UTF-16 characters to the specified character array starting at the specified position.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | The UTF-16 character array to write the characters read from the stream to |
| index | int | A 0-based index in **buffer** at which to start writing |
| count | int | The number of characters to read from the stream |

### Return Value

The number of characters read from the stream

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)