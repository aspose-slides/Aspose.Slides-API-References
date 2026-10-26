---
title: AppendAllText()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的编码将指定字符串追加到指定文件。
type: docs
weight: 14
url: /zh/system.io/file/appendalltext/
---
## File::AppendAllText(const String\&, const String\&, const EncodingPtr\&) 方法

将指定字符串使用指定的编码追加到指定文件。

```cpp
static void System::IO::File::AppendAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要追加字符串的文件路径 |
| contents | const [String](../../../system/string/)\& | 要写入文件的字符串 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的字符编码 |

## 参见

* Typedef [EncodingPtr](../../../system/encodingptr/)
* 类 [String](../../../system/string/)
* 类 [File](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)