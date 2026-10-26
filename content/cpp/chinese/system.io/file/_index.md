---
title: File
second_title: Aspose.Slides for C++ API 参考文档
description: 提供用于操作文件的方法。这是一个没有实例服务的静态类型。切勿以任何方式创建其实例。
type: docs
weight: 261
url: /zh/system.io/file/
---
## File 类

提供用于操作文件的方法。这是一个没有实例服务的静态类型。切勿以任何方式创建其实例。

```cpp
class File
```

## 方法

| Method | Description |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | 将指定字符串集合中的字符串追加到指定文件中，使用指定的编码，并在每个字符串后写入新行。如果指定的文件不存在，则会创建该文件。写入所有字符串后会关闭文件。 |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 使用指定的编码，将指定字符串追加到指定文件中。 |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | 创建一个 [StreamWriter](../streamwriter/) 对象，使用 UTF-8 编码将文本追加到指定文件中。如果指定的文件不存在，则会创建该文件。 |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | 将指定文件复制到指定位置。如果目标文件已存在，参数指定是否覆盖它。 |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | 创建新文件（或覆盖已存在的文件），并使用指定的缓冲区大小和选项以读取写入访问方式打开它。 |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | 创建新文件或打开已存在的文件，以写入 UTF-8 编码的文本。 |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | NOT IMPLEMENTED. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | 删除指定的文件或目录。 |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | NOT IMPLEMENTED. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | 确定指定的路径是否引用了已有文件。 |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | 返回指定实体的属性。 |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | 返回指定实体的创建时间（本地时间）。 |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | 返回指定实体的创建时间（UTC 时间）。 |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | 返回指定实体的最后访问时间（本地时间）。 |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | 返回指定实体的最后访问时间（UTC 时间）。 |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | 返回指定实体的最后写入时间（本地时间）。 |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | 返回指定实体的最后写入时间（UTC 时间）。 |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 将指定文件移动到新位置。 |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | 以指定模式打开指定文件，可读写且不共享。 |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | 以指定模式打开指定文件，使用指定的访问类型和共享选项。 |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | 以 'Open' 模式打开指定文件，仅供读取，且共享读取访问。 |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 以 UTF-8 编码打开指定的已存在文件进行文本读取，且不共享。 |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | 以 'OpenOrCreate' 模式打开指定文件，仅供写入，且不共享。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | 读取指定二进制文件的内容到字节数组。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 使用指定的字符编码，将指定文本文件的内容逐行读取到字符串数组中。 |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 使用指定的字符编码，将指定文本文件的内容读取到单个 [String](../../system/string/) 对象中。 |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 使用指定的字符编码，将指定文本文件的内容逐行读取，并返回一个可枚举的字符串集合，每个字符串表示文件内容的一行。 |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | 将一个文件的内容替换为另一个文件的内容，并创建被替换文件的备份。 |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | 为指定文件设置指定属性。 |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 将指定实体的最后写入时间设置为本地时间。 |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 将指定实体的最后写入时间设置为 UTC 时间。 |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 覆盖指定的二进制文件并写入指定的字节。 |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | 创建新文本文件或覆盖已有文件，使用指定编码将指定可枚举字符串集合中的所有字符串写入文件，每个字符串占一新行。 |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | 创建新文本文件或覆盖已有文件，使用指定编码将指定字符串数组中的所有字符串写入文件，每个字符串占一新行。 |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 创建新文本文件或覆盖已有文件，使用指定编码将指定字符串的内容写入文件。 |

## 字段

| Field | Description |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | 在读取和写入文件时缓冲的字节数的默认值。 |

## 另见

* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)