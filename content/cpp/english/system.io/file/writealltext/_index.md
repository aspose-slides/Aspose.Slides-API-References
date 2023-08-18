---
title: WriteAllText()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new text file or overwrites the existing one and writes the content of the specified string to it using the specified encoding.
type: docs
weight: 469
url: /system.io/file/writealltext/
---
## File::WriteAllText(const String\&, const String\&, const EncodingPtr\&) method


Creates a new text file or overwrites the existing one and writes the content of the specified string to it using the specified encoding.

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The file to create or overwrite |
| contents | const [String](../../../system/string/)\& | A string array |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The character encoding to use |

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)