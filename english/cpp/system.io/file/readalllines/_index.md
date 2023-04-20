---
title: ReadAllLines()
second_title: Aspose.Slides for C++ API Reference
description: Reads the content of the specified text file line by line to an array of strings using the specified character encoding.
type: docs
weight: 300
url: /cpp/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) method


Reads the content of the specified text file line by line to an array of strings using the specified character encoding.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to read |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The character encoding to use |

### Return Value

A string array each element of which represents a single line from the specified file

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)