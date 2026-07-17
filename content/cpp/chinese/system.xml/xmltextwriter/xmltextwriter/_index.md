---
title: XmlTextWriter()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的流和编码创建 XmlTextWriter 类的实例。
type: docs
weight: 183
url: /zh/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) 构造函数

使用指定的流和编码创建 [XmlTextWriter](../) 类的实例。

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 要写入的流。 |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 要生成的编码。如果 encoding 为 **nullptr**，则以 UTF-8 写出流，并从 **ProcessingInstruction** 中省略 encoding 属性。 |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) 构造函数

使用指定的文件创建 [XmlTextWriter](../) 类的实例。

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 要写入的文件名。如果文件已存在，则截断并用新内容覆盖。 |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 要生成的编码。如果 encoding 为 **nullptr**，则以 UTF-8 写出文件，并从 **ProcessingInstruction** 中省略 encoding 属性。 |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) 构造函数

使用指定的 TextWriter 创建 [XmlTextWriter](../) 类的实例。

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 要写入的 TextWriter。假设 TextWriter 已经设置为正确的编码。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../../system.io/stream/)
* 类 [Encoding](../../../system.text/encoding/)
* 类 [XmlTextWriter](../)
* 类 [String](../../../system/string/)
* 类 [TextWriter](../../../system.io/textwriter/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)