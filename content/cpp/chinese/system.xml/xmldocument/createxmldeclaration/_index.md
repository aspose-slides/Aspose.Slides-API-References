---
title: CreateXmlDeclaration()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的值创建 XmlDeclaration 节点。
type: docs
weight: 378
url: /zh/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) 方法

使用指定的值创建一个 [XmlDeclaration](../../xmldeclaration/) 节点。

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | 版本必须为 "1.0"。 |
| encoding | const [String](../../../system/string/)\& | 编码属性的值。当您将 [XmlDocument](../) 保存到文件或流时使用此编码；因此，必须将其设置为 [Text::Encoding](../../../system.text/encoding/) 类支持的字符串，否则 "XmlDocument::Save(String)" 将失败。如果此值为 **nullptr** 或 [String::Empty](../../../system/string/empty/)，[XmlDocument::Save](../save/) 方法不会在 XML 声明中写入 encoding 属性，因此使用默认编码 UTF-8。 |
| standalone | const [String](../../../system/string/)\& | 值必须为 "yes" 或 "no"。如果此值为 **nullptr** 或 [String::Empty](../../../system/string/empty/)，[XmlDocument::Save](../save/) 方法不会在 XML 声明中写入 standalone 属性。 |

### 返回值

新的 [XmlDeclaration](../../xmldeclaration/) 节点。

## 备注

注意：如果 [XmlDocument](../) 被保存到 TextWriter 或 [XmlTextWriter](../../xmltextwriter/)，此编码值将被丢弃。相反，将使用 TextWriter 或 [XmlTextWriter](../../xmltextwriter/) 的编码。这确保写出的 XML 可以使用正确的编码读取回来。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlDeclaration](../../xmldeclaration/)
* 类 [String](../../../system/string/)
* 类 [XmlDocument](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)