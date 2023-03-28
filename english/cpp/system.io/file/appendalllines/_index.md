---
title: AppendAllLines()
second_title: Aspose.Slides for C++ API Reference
description: Appends strings from the specified collection of strings to the specified file using the specified encoding by writing each string in a new line. If the specified file does not exist, it is created. The file is closed after writing all strings.
type: docs
weight: 1
url: /cpp/system.io/file/appendalllines/
---
## File::AppendAllLines(const [String](../../../system/string/)\&, const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\&, const [EncodingPtr](../../../system/encodingptr/)\&) method


Appends strings from the specified collection of strings to the specified file using the specified encoding by writing each string in a new line. If the specified file does not exist, it is created. The file is closed after writing all strings.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to append the strings to |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | The strings to write to the file |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The character encoding to use |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
