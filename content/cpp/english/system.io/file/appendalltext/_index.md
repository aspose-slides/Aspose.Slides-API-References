---
title: AppendAllText()
second_title: Aspose.Slides for C++ API Reference
description: Appends the specified string to the specified file using the specified encoding.
type: docs
weight: 14
url: /system.io/file/appendalltext/
---
## File::AppendAllText(const String\&, const String\&, const EncodingPtr\&) method


Appends the specified string to the specified file using the specified encoding.

```cpp
static void System::IO::File::AppendAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to append the string to |
| contents | const [String](../../../system/string/)\& | The string to write to the file |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The character encoding to use |

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)