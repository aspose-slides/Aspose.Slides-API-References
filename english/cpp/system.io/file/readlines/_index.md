---
title: ReadLines()
second_title: Aspose.Slides for C++ API Reference
description: Reads the content of the specified text file line by line using the specified character encoding and returns enumerable collection of strings each of which represents a single line of the file's content.
type: docs
weight: 326
url: /cpp/system.io/file/readlines/
---
## File::ReadLines(const [String](../../../system/string/)\&, const [EncodingPtr](../../../system/encodingptr/)\&) method


Reads the content of the specified text file line by line using the specified character encoding and returns enumerable collection of strings each of which represents a single line of the file's content.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to read |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The character encoding to use |

### Return Value

An enumerable collection of strings representing the content of the specified file

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
