---
title: WriteAllLines()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new text file or overwrites the existing one and writes all strings from the specified enumerable collection of strings to it, each string on a new line, using the specified encoding.
type: docs
weight: 456
url: /cpp/system.io/file/writealllines/
---
## File::WriteAllLines(const [String](../../../system/string/)\&, const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\&, const [EncodingPtr](../../../system/encodingptr/)\&) method


Creates a new text file or overwrites the existing one and writes all strings from the specified enumerable collection of strings to it, each string on a new line, using the specified encoding.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The file to create or overwrite |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | An enumerable collection of strings |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The character encoding to use |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## File::WriteAllLines(const [String](../../../system/string/)\&, const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\&, const [EncodingPtr](../../../system/encodingptr/)\&) method


Creates a new text file or overwrites the existing one and writes all strings from the specified array of strings to it, each string on a new line, using the specified encoding.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The file to create or overwrite |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | A string array |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The character encoding to use |

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
