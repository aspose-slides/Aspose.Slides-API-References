---
title: WriteAllLines()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新的文本文件或覆盖已存在的文件，并将指定的可枚举字符串集合中的所有字符串写入该文件，每个字符串占一行，使用指定的编码。
type: docs
weight: 456
url: /zh/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) method

创建一个新的文本文件或覆盖已存在的文件，并将指定的字符串可枚举集合中的所有字符串写入该文件，每个字符串占一行，使用指定的编码。

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要创建或覆盖的文件 |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | 字符串的可枚举集合 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的字符编码 |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) method

创建一个新的文本文件或覆盖已存在的文件，并将指定的字符串数组中的所有字符串写入该文件，每个字符串占一行，使用指定的编码。

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要创建或覆盖的文件 |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | 字符串数组 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的字符编码 |

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [EncodingPtr](../../../system/encodingptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 类 [File](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)