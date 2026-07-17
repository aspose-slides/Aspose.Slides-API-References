---
title: ReadAllText()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的字符编码，将指定文本文件的内容读取为单个 String 对象。
type: docs
weight: 313
url: /zh/system.io/file/readalltext/
---
## File::ReadAllText(const String&, const EncodingPtr&) 方法

读取指定文本文件的内容，并使用指定的字符编码将其转换为单个[String](../../../system/string/)对象。

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | 要读取的文件路径 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)& | 要使用的字符编码 |

### 返回值

一个包含指定文件内容的字符串

## 另请参见

* 类型定义 [EncodingPtr](../../../system/encodingptr/)
* 类 [String](../../../system/string/)
* 类 [File](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)