---
title: AppendAllLines()
second_title: Aspose.Slides C++ API 参考文档
description: 将指定字符串集合中的字符串追加到指定文件中，使用指定的编码，每个字符串写入新行。如果指定的文件不存在，则会创建该文件。写入所有字符串后关闭文件。
type: docs
weight: 1
url: /zh/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) 方法

将指定字符串集合中的字符串追加到指定文件中，使用指定的编码，每个字符串写入新行。如果指定的文件不存在，则会创建该文件。写入所有字符串后关闭文件。

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要追加字符串的文件路径 |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | 要写入文件的字符串 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的字符编码 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [EncodingPtr](../../../system/encodingptr/)
* 类 [String](../../../system/string/)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 类 [File](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)