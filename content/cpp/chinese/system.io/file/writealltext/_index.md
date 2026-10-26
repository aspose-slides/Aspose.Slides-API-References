---
title: WriteAllText()
second_title: Aspose.Slides C++ API 参考
description: 创建一个新文本文件或覆盖已存在的文件，并使用指定的编码将指定字符串的内容写入其中。
type: docs
weight: 469
url: /zh/system.io/file/writealltext/
---
## File::WriteAllText(const String\&, const String\&, const EncodingPtr\&) 方法

创建一个新文本文件或覆盖已存在的文件，并使用指定的编码将指定字符串的内容写入其中。

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要创建或覆盖的文件 |
| contents | const [String](../../../system/string/)\& | 字符串数组 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的字符编码 |

## 另见

* Typedef [EncodingPtr](../../../system/encodingptr/)
* 类 [String](../../../system/string/)
* 类 [File](../)
* 命名空间 [System::IO](../../)
* Library [Aspose.Slides](../../../)