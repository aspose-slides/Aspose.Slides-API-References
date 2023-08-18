---
title: Load()
second_title: Aspose.Slides for C++ API Reference
description: Loads the XSLT style sheet contained in the XmlReader.
type: docs
weight: 27
url: /system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) method


Loads the XSLT style sheet contained in the [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | An [XmlReader](../../../system.xml/xmlreader/) object that contains the XSLT style sheet. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Loads the XSLT style sheet contained in the [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | An [XmlReader](../../../system.xml/xmlreader/) object that contains the XSLT style sheet. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to load any style sheets referenced in **xsl:import** and **xsl:include** elements. If this is **nullptr**, external resources are not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after this method completes. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method


Loads the XSLT style sheet contained in the IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the XSLT style sheet. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Loads the XSLT style sheet contained in the IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | An object implementing the IXPathNavigable interface. It can be either an [XmlNode](../../../system.xml/xmlnode/) (typically an [XmlDocument](../../../system.xml/xmldocument/)), or an XPathDocument containing the XSLT style sheet. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to load any style sheets referenced in **xsl:import** and **xsl:include** elements. If this is **nullptr**, external resources are not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after this method completes. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) method


Loads the XSLT style sheet contained in the XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | An XPathNavigator object that contains the XSLT style sheet. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Loads the XSLT style sheet contained in the XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | An XPathNavigator object that contains the XSLT style sheet. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to load any style sheets referenced in **xsl:import** and **xsl:include** elements. If this is **nullptr**, external resources are not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after this method completes. |

## XslTransform::Load(const String\&) method


Loads the XSLT style sheet specified by a URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | The URL that specifies the XSLT style sheet to load. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Loads the XSLT style sheet specified by a URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | The URL that specifies the XSLT style sheet to load. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) to use to load the style sheet and any style sheet(s) referenced in **xsl:import** and **xsl:include** elements. If this is **nullptr**, a default [XmlUrlResolver](../../../system.xml/xmlurlresolver/) with no user credentials is used to open the style sheet. The default [XmlUrlResolver](../../../system.xml/xmlurlresolver/) is not used to resolve any external resources in the style sheet, so **xsl:import** and **xsl:include** elements are not resolved. The [XmlResolver](../../../system.xml/xmlresolver/) is not cached after this method completes. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslTransform](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)