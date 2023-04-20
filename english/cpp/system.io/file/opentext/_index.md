---
title: OpenText()
second_title: Aspose.Slides for C++ API Reference
description: Opens the specified existing file for reading text using UTF-8 encoding with no sharing.
type: docs
weight: 261
url: /cpp/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) method


Opens the specified existing file for reading text using UTF-8 encoding with no sharing.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to open |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The character encoding to use |

### Return Value

A shared pointer to a [StreamWriter](../../streamwriter/) object associated with the opened file

## See Also

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)