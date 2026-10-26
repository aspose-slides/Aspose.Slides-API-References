---
title: ReadLines()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的字符编码逐行读取指定文本文件的内容，并返回一个可枚举的字符串集合，每个字符串表示文件内容中的单行。
type: docs
weight: 326
url: /zh/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) 方法

使用指定的字符编码逐行读取指定文本文件的内容，并返回一个可枚举的字符串集合，每个字符串表示文件内容中的单行。

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要读取的文件路径 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的字符编码 |

### 返回值

一个可枚举的字符串集合，表示指定文件的内容

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 类 [String](../../../system/string/)
* 类 [File](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)