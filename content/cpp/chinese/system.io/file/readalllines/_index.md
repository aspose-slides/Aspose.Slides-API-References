---
title: ReadAllLines()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的字符编码，逐行读取指定文本文件的内容并存入字符串数组。
type: docs
weight: 300
url: /zh/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) 方法

读取指定文本文件的内容，逐行使用指定的字符编码存入字符串数组。

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要读取的文件路径 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的字符编码 |

### 返回值

一个字符串数组，其中每个元素表示指定文件中的一行

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [EncodingPtr](../../../system/encodingptr/)
* 类 [String](../../../system/string/)
* 类 [File](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)