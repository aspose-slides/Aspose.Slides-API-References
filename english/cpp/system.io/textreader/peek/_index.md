---
title: Peek()
second_title: Aspose.Slides for C++ API Reference
description: Reads a single character from the stream without changing the stream's read cursor.
type: docs
weight: 27
url: /cpp/system.io/textreader/peek/
---
## TextReader::Peek() method


Reads a single character from the stream without changing the stream's read cursor.

```cpp
virtual int System::IO::TextReader::Peek()
```


### Return Value

Read character encoded with UTF-16 encoding; if the read character is represented by two codepoints in UTF-16 encoding then only the high surragate is returned; if no character was read -1 is returned

## See Also

* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)