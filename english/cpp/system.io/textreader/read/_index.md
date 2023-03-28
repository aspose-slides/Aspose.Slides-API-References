---
title: Read()
second_title: Aspose.Slides for C++ API Reference
description: Reads a single character from the stream.
type: docs
weight: 40
url: /cpp/system.io/textreader/read/
---
## TextReader::Read() method


Reads a single character from the stream.

```cpp
virtual int System::IO::TextReader::Read()
```


### Return Value

Read character encoded with UTF-16 encoding; if the read character is represented by two codepoints in UTF-16 encoding then only the high surragate is returned.

## See Also

* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## TextReader::Read([ArrayPtr](../../../system/arrayptr/)\<char_t\>, int, int) method


Reads the specified number of characters from the stream and writes them to the specified character array starting at the specified position.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
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
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
