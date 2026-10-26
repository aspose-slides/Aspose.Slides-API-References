---
title: XPathDocument()
second_title: Aspose.Slides for C++ API 參考
description: 從指定的 XmlReader 物件中包含的 XML 資料初始化 XPathDocument 類別的新實例。
type: docs
weight: 1
url: /zh-hant/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) 建構函式


初始化一個新的 [XPathDocument](../) 類別實例，資料來源為指定的 [XmlReader](../../../system.xml/xmlreader/) 物件中包含的 XML 資料。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```


### 參數說明

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含 XML 資料的 [XmlReader](../../../system.xml/xmlreader/) 物件。 |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) 建構函式


初始化一個新的 [XPathDocument](../) 類別實例，資料來源為指定的 [XmlReader](../../../system.xml/xmlreader/) 物件中包含的 XML 資料，並使用指定的空白字元處理方式。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```


### 參數說明

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含 XML 資料的 [XmlReader](../../../system.xml/xmlreader/) 物件。 |
| space | [XmlSpace](../../../system.xml/xmlspace/) | XmlSpace 物件。 |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) 建構函式


初始化一個新的 [XPathDocument](../) 類別實例，資料來源為指定的 TextReader 物件中包含的 XML 資料。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```


### 參數說明

| Parameter | Type | Description |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 包含 XML 資料的 TextReader 物件。 |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) 建構函式


初始化一個新的 [XPathDocument](../) 類別實例，資料來源為指定的 Stream 物件中包含的 XML 資料。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```


### 參數說明

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 包含 XML 資料的 Stream 物件。 |

## XPathDocument::XPathDocument(const String\&) 建構函式


初始化一個新的 [XPathDocument](../) 類別實例，資料來源為指定檔案中包含的 XML 資料。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```


### 參數說明

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | 含有 XML 資料之檔案的路徑。 |

## XPathDocument::XPathDocument(const String\&, XmlSpace) 建構函式


初始化一個新的 [XPathDocument](../) 類別實例，資料來源為指定檔案中包含的 XML 資料，並使用指定的空白字元處理方式。

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```


### 參數說明

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | 含有 XML 資料之檔案的路徑。 |
| space | [XmlSpace](../../../system.xml/xmlspace/) | XmlSpace 物件。 |

## 另請參閱

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathDocument](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)