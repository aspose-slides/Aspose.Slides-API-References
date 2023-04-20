---
title: ReadAllText()
second_title: Aspose.Slides for C++ API Reference
description: Reads the content of the specified text file to a single String object using the specified character encoding.
type: docs
weight: 313
url: /cpp/system.io/file/readalltext/
---
## File::ReadAllText(const String\&, const EncodingPtr\&) method


Reads the content of the specified text file to a single [String](../../../system/string/) object using the specified character encoding.

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to read |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The character encoding to use |

### Return Value

A string containing the content of the specified file

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)