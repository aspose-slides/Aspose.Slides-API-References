---
title: XmlValidatingReader()
second_title: Aspose.Slides for C++ API 参考
description: 初始化 XmlValidatingReader 类的新实例，该实例验证来自给定 XmlReader 的返回内容。
type: docs
weight: 430
url: /zh/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) 构造函数


初始化 [XmlValidatingReader](../) 类的新实例，该实例验证来自给定 [XmlReader](../../xmlreader/) 的内容。

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | 在验证时要读取的 [XmlReader](../../xmlreader/)。当前实现仅支持 [XmlTextReader](../../xmltextreader/)。 |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) 构造函数


使用指定的值初始化 [XmlValidatingReader](../) 类的新实例。

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | 包含要解析的 XML 片段的字符串。 |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML 片段的 XmlNodeType。这还决定了片段字符串可以包含的内容（见下表）。 |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | 用于解析 XML 片段的 [XmlParserContext](../../xmlparsercontext/)。这包括要使用的 [NameTable](../../nametable/)、编码、命名空间范围、当前 **xml:lang** 和 **xml:space** 范围。 |

## 备注



下表列出了 **fragType** 的有效取值以及读取器如何解析每种不同的节点类型。

| XmlNodeType | Fragment May Contain |
| --- | --- |
| Element| 任何有效的元素内容（例如，元素、注释、处理指令、CDATA、文本和实体引用的任意组合）。 |
| [Attribute](../../../system/attribute/)| 属性的值（引号内的部分）。 |
| Document| 整个 XML 文档的内容；此规则强制执行文档级别的规则。 |


## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) 构造函数


使用指定的值初始化 [XmlValidatingReader](../) 类的新实例。

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含要解析的 XML 片段的流。 |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML 片段的 XmlNodeType。这决定了片段可以包含的内容（见下表）。 |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | 用于解析 XML 片段的 [XmlParserContext](../../xmlparsercontext/)。这包括要使用的 [XmlNameTable](../../xmlnametable/)、编码、命名空间范围、当前 **xml:lang** 和 **xml:space** 范围。 |

## 备注



下表列出了 **fragType** 的有效取值以及读取器如何解析每种不同的节点类型。

| XmlNodeType | Fragment May Contain |
| --- | --- |
| Element| 任何有效的元素内容（例如，元素、注释、处理指令、CDATA、文本和实体引用的任意组合）。 |
| [Attribute](../../../system/attribute/)| 属性的值（引号内的部分）。 |
| Document| 整个 XML 文档的内容；此规则强制执行文档级别的规则。 |


## 另请参见

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlValidatingReader](../)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)