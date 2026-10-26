---
title: Load()
second_title: Aspose.Slides for C++ API 參考文件
description: 編譯包含於 XmlReader 中的樣式表。
type: docs
weight: 27
url: /zh-hant/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) method


編譯包含於 [XmlReader](../../../system.xml/xmlreader/) 中的樣式表。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含樣式表的 [XmlReader](../../../system.xml/xmlreader/)。 |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) method


編譯 [XmlReader](../../../system.xml/xmlreader/) 中的 XSLT 樣式表。此 [XmlResolver](../../../system.xml/xmlresolver/) 會解析任何 XSLT **import** 或 **include** 元素，而 XSLT 設定決定樣式表的權限。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含樣式表的 [XmlReader](../../../system.xml/xmlreader/)。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | 套用至樣式表的 [XsltSettings](../../xsltsettings/)。如果此值為 **nullptr**，則套用 [XsltSettings::get_Default](../../xsltsettings/get_default/) 設定。 |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 XSLT **import** 和 **include** 元素中參照的任何樣式表的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不會解析外部資源。 |

## XslCompiledTransform::Load(const String\&) method


載入並編譯位於指定 URI 的樣式表。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | 樣式表的 URI。 |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) method


載入並編譯由 URI 指定的 XSLT 樣式表。此 [XmlResolver](../../../system.xml/xmlresolver/) 會解析任何 XSLT **import** 或 **include** 元素，而 XSLT 設定決定樣式表的權限。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | 樣式表的 URI。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | 套用至樣式表的 [XsltSettings](../../xsltsettings/)。如果此值為 **nullptr**，則套用 [XsltSettings::get_Default](../../xsltsettings/get_default/) 設定。 |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析樣式表 URI 以及 XSLT **import** 和 **include** 元素中參照的任何樣式表的 [XmlResolver](../../../system.xml/xmlresolver/)。 |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method


編譯位於 IXPathNavigable 物件中的樣式表。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/)（通常是 [XmlDocument](../../../system.xml/xmldocument/)）或包含樣式表的 XPathDocument。 |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) method


編譯 IXPathNavigable 中的 XSLT 樣式表。此 [XmlResolver](../../../system.xml/xmlresolver/) 會解析任何 XSLT **import** 或 **include** 元素，而 XSLT 設定決定樣式表的權限。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 實作 IXPathNavigable 介面的物件。它可以是 [XmlNode](../../../system.xml/xmlnode/)（通常是 [XmlDocument](../../../system.xml/xmldocument/)）或包含樣式表的 XPathDocument。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | 套用至樣式表的 [XsltSettings](../../xsltsettings/)。如果此值為 **nullptr**，則套用 [XsltSettings::get_Default](../../xsltsettings/get_default/) 設定。 |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | 用於解析 XSLT **import** 和 **include** 元素中參照的任何樣式表的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值為 **nullptr**，則不會解析外部資源。 |

## 相關參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlReader](../../../system.xml/xmlreader/)
* 類別 [XslCompiledTransform](../)
* 類別 [XsltSettings](../../xsltsettings/)
* 類別 [XmlResolver](../../../system.xml/xmlresolver/)
* 類別 [String](../../../system/string/)
* 類別 [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* 命名空間 [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)