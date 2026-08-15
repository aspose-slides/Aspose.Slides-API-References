---
title: Load()
second_title: Aspose.Slides for C++ API 參考
description: 載入包含於 XmlReader 中的 XSLT 樣式表。
type: docs
weight: 27
url: /zh-hant/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) 方法

載入包含於 [XmlReader](../../../system.xml/xmlreader/) 中的 XSLT 樣式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 一個包含 XSLT 樣式表的 [XmlReader](../../../system.xml/xmlreader/) 物件。 |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

載入包含於 [XmlReader](../../../system.xml/xmlreader/) 中的 XSLT 樣式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 一個包含 XSLT 樣式表的 [XmlReader](../../../system.xml/xmlreader/) 物件。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於載入在 **xsl:import** 和 **xsl:include** 元素中引用的任何樣式表的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不解析外部資源。此方法完成後，[XmlResolver](../../../system.xml/xmlresolver/) 不會被快取。 |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) 方法

載入包含於 IXPathNavigable 中的 XSLT 樣式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/)（通常是 [XmlDocument](../../../system.xml/xmldocument/)），或是包含 XSLT 樣式表的 XPathDocument。 |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

載入包含於 IXPathNavigable 中的 XSLT 樣式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/)（通常是 [XmlDocument](../../../system.xml/xmldocument/)），或是包含 XSLT 樣式表的 XPathDocument。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於載入在 **xsl:import** 和 **xsl:include** 元素中引用的任何樣式表的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不解析外部資源。此方法完成後，[XmlResolver](../../../system.xml/xmlresolver/) 不會被快取。 |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) 方法

載入包含於 XPathNavigator 的 XSLT 樣式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 一個包含 XSLT 樣式表的 XPathNavigator 物件。 |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

載入包含於 XPathNavigator 的 XSLT 樣式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 一個包含 XSLT 樣式表的 XPathNavigator 物件。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於載入在 **xsl:import** 和 **xsl:include** 元素中引用的任何樣式表的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不解析外部資源。此方法完成後，[XmlResolver](../../../system.xml/xmlresolver/) 不會被快取。 |

## XslTransform::Load(const String\&) 方法

載入由 URL 指定的 XSLT 樣式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 指定要載入之 XSLT 樣式表的 URL。 |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

載入由 URL 指定的 XSLT 樣式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 指定要載入之 XSLT 樣式表的 URL。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於載入樣式表以及在 **xsl:import** 和 **xsl:include** 元素中引用的任何樣式表的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則使用預設的 [XmlUrlResolver](../../../system.xml/xmlurlresolver/)（不含使用者憑證）開啟樣式表。預設的 [XmlUrlResolver](../../../system.xml/xmlurlresolver/) 不會用於解析樣式表中的任何外部資源，因而不會解析 **xsl:import** 和 **xsl:include** 元素。此方法完成後，[XmlResolver](../../../system.xml/xmlresolver/) 不會被快取。 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslTransform](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)