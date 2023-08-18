---
title: File
second_title: Aspose.Slides for C++ API Reference
description: Provides methods for manipulating files. This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 248
url: /system.io/file/
---
## File class


Provides methods for manipulating files. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class File
```

## Methods

| Method | Description |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Appends strings from the specified collection of strings to the specified file using the specified encoding by writing each string in a new line. If the specified file does not exist, it is created. The file is closed after writing all strings. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Appends the specified string to the specified file using the specified encoding. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Creates a [StreamWriter](../streamwriter/) object that appends text to the specified file using UTF-8 encoding. If the specified file does not exist, it is created. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Copies the specified file to the specified location. If the destination file already exists, a parameter specifies if it should be overwritten. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Creates a new file (or overwrites existing) and opens it for reading and writing access using the specified buffer size and options. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | Creates a new or opens existing file for writing UTF-8 encoded text. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | NOT IMPLEMENTED. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | Deletes the specified file or directory. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | NOT IMPLEMENTED. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Determines if the specified path references an existing file. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Returns the attributes of the specified entity. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Returns the creation time of the specified entity as local time. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Returns the creation time of the specified entity as UTC time. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Returns the last access time of the specified entity as local time. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Returns the last access time of the specified entity as UTC time. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Returns the last write time of the specified entity as local time. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Returns the last write time of the specified entity as UTC time. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Moves the specified file to the new location. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Opens the specified file in the specified mode for reading and writing and with no sharing. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Opens the specified file in the specified mode, with the specified access type and sharing option. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Opens the specified file for reading only, in 'Open' mode with shared access for reading. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Opens the specified existing file for reading text using UTF-8 encoding with no sharing. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Opens the specified file for writing only, in 'OpenOrCreate' mode with no sharing. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Reads the content of the specified binary file to a byte array. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Reads the content of the specified text file line by line to an array of strings using the specified character encoding. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Reads the content of the specified text file to a single [String](../../system/string/) object using the specified character encoding. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Reads the content of the specified text file line by line using the specified character encoding and returns enumerable collection of strings each of which represents a single line of the file's content. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Replaces the contents of a one file with another and creates a backup of the replaced file. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Sets the specified attributes on the specified file. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Sets the last write time of the specified entity as local time. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Sets the last write time of the specified entity as UTC time. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Overwrites the specified binary file and writes the specified bytes to it. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Creates a new text file or overwrites the existing one and writes all strings from the specified enumerable collection of strings to it, each string on a new line, using the specified encoding. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Creates a new text file or overwrites the existing one and writes all strings from the specified array of strings to it, each string on a new line, using the specified encoding. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Creates a new text file or overwrites the existing one and writes the content of the specified string to it using the specified encoding. |
## Fields

| Field | Description |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Default value of the number of bytes buffered during reading from and writing to a file. |
## See Also

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)