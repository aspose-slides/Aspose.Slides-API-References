---
title: XmlValidatingReader()
second_title: Aspose.Slides for C++ API 參考文件
description: 初始化一個新的 XmlValidatingReader 類別實例，用於驗證從給定的 XmlReader 返回的內容。
type: docs
weight: 430
url: /zh-hant/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor

初始化一個新的 [XmlValidatingReader](../) 類別實例，用於驗證從給定的 [XmlReader](../../xmlreader/) 返回的內容。

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | [XmlReader](../../xmlreader/) 用於在驗證過程中讀取。當前實作僅支援 [XmlTextReader](../../xmltextreader/)。 |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

使用指定的值初始化 [XmlValidatingReader](../) 類別的新實例。

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | 包含要解析的 XML 片段之字串。 |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML 片段的 XmlNodeType。此亦決定片段字串可以包含的內容（請參閱下表）。 |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) 用於解析 XML 片段的環境。其包括要使用的 [NameTable](../../nametable/)、編碼、命名空間範圍、目前的 **xml:lang** 與 **xml:space** 範圍。 |

## 備註

下表列出了 **fragType** 的有效值以及讀取器對各種節點類型的解析方式。

| XmlNodeType | 片段可能包含 |
| --- | --- |
| Element| 任何有效的元素內容（例如，元素、註解、處理指令、CDATA、文字與實體參照的任意組合）。 |
| [Attribute](../../../system/attribute/)| 屬性的值（引號內的部分）。 |
| Document| 整個 XML 文件的內容；會套用文件層級的規則。 |

## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

使用指定的值初始化 [XmlValidatingReader](../) 類別的新實例。

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含要解析之 XML 片段的串流。 |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML 片段的 XmlNodeType。此決定片段可以包含的內容（請參閱下表）。 |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) 用於解析 XML 片段的環境。其包括要使用的 [XmlNameTable](../../xmlnametable/)、編碼、命名空間範圍、目前的 **xml:lang** 與 **xml:space** 範圍。 |

## 備註

下表列出了 **fragType** 的有效值以及讀取器對各種節點類型的解析方式。

| XmlNodeType | 片段可能包含 |
| --- | --- |
| Element| 任何有效的元素內容（例如，元素、註解、處理指令、CDATA、文字與實體參照的任意組合）。 |
| [Attribute](../../../system/attribute/)| 屬性的值（引號內的部分）。 |
| Document| 整個 XML 文件的內容；會套用文件層級的規則。 |

## 相關參考

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlValidatingReader](../)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)