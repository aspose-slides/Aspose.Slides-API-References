---
title: Read()
second_title: Aspose.Slides for C++ API Reference
description: Reads a single character from the stream.
type: docs
weight: 40
url: /cpp/system.io/stringreader/read/
---
## StringReader::Read() method


Reads a single character from the stream.

```cpp
virtual int System::IO::StringReader::Read() override
```


### Return Value

A read character or -1 if no character has been read

## See Also

* Class [StringReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StringReader::Read([ArrayPtr](../../../system/arrayptr/)\<char_t\>, int, int) method


Reads the specified number of characters from the stream to the specified character array starting at the specified position.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | The character array to write the characters read from the stream to |
| index | int | A 0-based index in **buffer** at which to start writing |
| count | int | The number of characters to read from the stream |

### Return Value

The number of characters read from the stream

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
