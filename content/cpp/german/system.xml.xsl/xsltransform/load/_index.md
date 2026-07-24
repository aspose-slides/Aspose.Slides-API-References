---
title: Load()
second_title: Aspose.Slides für C++ API-Referenz
description: Lädt das im XmlReader enthaltene XSLT-Stylesheet.
type: docs
weight: 27
url: /de/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) method


Lädt das im [XmlReader](../../../system.xml/xmlreader/) enthaltene XSLT-Stylesheet.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ein [XmlReader](../../../system.xml/xmlreader/) Objekt, das das XSLT-Stylesheet enthält. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Lädt das im [XmlReader](../../../system.xml/xmlreader/) enthaltene XSLT-Stylesheet.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ein [XmlReader](../../../system.xml/xmlreader/) Objekt, das das XSLT-Stylesheet enthält. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/) wird verwendet, um alle in **xsl:import** und **xsl:include** Elementen referenzierten Stylesheets zu laden. Wenn dies **nullptr** ist, werden externe Ressourcen nicht aufgelöst. Das [XmlResolver](../../../system.xml/xmlresolver/) wird nach Abschluss dieser Methode nicht zwischengespeichert. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method


Lädt das im IXPathNavigable enthaltene XSLT-Stylesheet.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das das IXPathNavigable-Interface implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das das XSLT-Stylesheet enthält. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Lädt das im IXPathNavigable enthaltene XSLT-Stylesheet.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das das IXPathNavigable-Interface implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das das XSLT-Stylesheet enthält. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/) wird verwendet, um alle in **xsl:import** und **xsl:include** Elementen referenzierten Stylesheets zu laden. Wenn dies **nullptr** ist, werden externe Ressourcen nicht aufgelöst. Das [XmlResolver](../../../system.xml/xmlresolver/) wird nach Abschluss dieser Methode nicht zwischengespeichert. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) method


Lädt das im XPathNavigator enthaltene XSLT-Stylesheet.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ein XPathNavigator-Objekt, das das XSLT-Stylesheet enthält. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Lädt das im XPathNavigator enthaltene XSLT-Stylesheet.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ein XPathNavigator-Objekt, das das XSLT-Stylesheet enthält. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/) wird verwendet, um alle in **xsl:import** und **xsl:include** Elementen referenzierten Stylesheets zu laden. Wenn dies **nullptr** ist, werden externe Ressourcen nicht aufgelöst. Das [XmlResolver](../../../system.xml/xmlresolver/) wird nach Abschluss dieser Methode nicht zwischengespeichert. |

## XslTransform::Load(const String\&) method


Lädt das XSLT-Stylesheet, das durch eine URL angegeben wird.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Die URL, die das zu ladende XSLT-Stylesheet angibt. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Lädt das XSLT-Stylesheet, das durch eine URL angegeben wird.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Die URL, die das zu ladende XSLT-Stylesheet angibt. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/) wird verwendet, um das Stylesheet und alle darin referenzierten Stylesheet(s) in **xsl:import** und **xsl:include** Elementen zu laden. Wenn dies **nullptr** ist, wird ein Standard-[XmlUrlResolver](../../../system.xml/xmlurlresolver/) ohne Benutzeranmeldeinformationen verwendet, um das Stylesheet zu öffnen. Der Standard-[XmlUrlResolver](../../../system.xml/xmlurlresolver/) wird nicht verwendet, um externe Ressourcen im Stylesheet aufzulösen, sodass **xsl:import**- und **xsl:include**-Elemente nicht aufgelöst werden. Das [XmlResolver](../../../system.xml/xmlresolver/) wird nach Abschluss dieser Methode nicht zwischengespeichert. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Klasse [XslTransform](../)
* Klasse [XmlResolver](../../../system.xml/xmlresolver/)
* Klasse [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Klasse [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml::Xsl](../../)
* Bibliothek [Aspose.Slides](../../../)