---
title: ReadBlock()
second_title: Aspose.Slides for C++ API Reference
description: Reads the specified maximum number of characters from the current text reader and writes the data to a buffer, starting at the specified index.
type: docs
weight: 53
url: /cpp/system.io/textreader/readblock/
---
## TextReader::ReadBlock([ArrayPtr](../../../system/arrayptr/)\<char_t\>, int, int) method


Reads the specified maximum number of characters from the current text reader and writes the data to a buffer, starting at the specified index.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | A character buffer to write the read data to |
| index | int | A 0-based index in **buffer** to start writing at |
| count | int | The maximum number of characters to read |

### Return Value

The actual number of characters read

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
