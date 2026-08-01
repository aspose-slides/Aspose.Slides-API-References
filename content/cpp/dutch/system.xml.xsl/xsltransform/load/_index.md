---
title: Load()
second_title: Aspose.Slides voor C++ API-referentie
description: Laadt het XSLT-stijlsheet dat is opgenomen in de XmlReader.
type: docs
weight: 27
url: /nl/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) methode

Laadt het XSLT-stijlsheet dat is opgenomen in de [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Een [XmlReader](../../../system.xml/xmlreader/) object dat het XSLT-stijlsheet bevat. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) methode

Laadt het XSLT-stijlsheet dat is opgenomen in de [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Een [XmlReader](../../../system.xml/xmlreader/) object dat het XSLT-stijlsheet bevat. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om alle stijlsheets te laden die worden vermeld in **xsl:import** en **xsl:include** elementen. Als dit **nullptr** is, worden externe bronnen niet opgelost. De [XmlResolver](../../../system.xml/xmlresolver/) wordt niet gecached nadat deze methode is voltooid. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) methode

Laadt het XSLT-stijlsheet dat is opgenomen in de IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) (meestal een [XmlDocument](../../../system.xml/xmldocument/)) of een XPathDocument zijn dat het XSLT-stijlsheet bevat. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) methode

Laadt het XSLT-stijlsheet dat is opgenomen in de IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) (meestal een [XmlDocument](../../../system.xml/xmldocument/)) of een XPathDocument zijn dat het XSLT-stijlsheet bevat. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om alle stijlsheets te laden die worden vermeld in **xsl:import** en **xsl:include** elementen. Als dit **nullptr** is, worden externe bronnen niet opgelost. De [XmlResolver](../../../system.xml/xmlresolver/) wordt niet gecached nadat deze methode is voltooid. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) methode

Laadt het XSLT-stijlsheet dat is opgenomen in de XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Een XPathNavigator-object dat het XSLT-stijlsheet bevat. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) methode

Laadt het XSLT-stijlsheet dat is opgenomen in de XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Een XPathNavigator-object dat het XSLT-stijlsheet bevat. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om alle stijlsheets te laden die worden vermeld in **xsl:import** en **xsl:include** elementen. Als dit **nullptr** is, worden externe bronnen niet opgelost. De [XmlResolver](../../../system.xml/xmlresolver/) wordt niet gecached nadat deze methode is voltooid. |

## XslTransform::Load(const String\&) methode

Laadt het XSLT-stijlsheet dat is opgegeven via een URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | De URL die het XSLT-stijlsheet specificeert dat moet worden geladen. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) methode

Laadt het XSLT-stijlsheet dat is opgegeven via een URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | De URL die het XSLT-stijlsheet specificeert dat moet worden geladen. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om het stijlsheet en eventuele stijlsheets die worden vermeld in **xsl:import** en **xsl:include** elementen te laden. Als dit **nullptr** is, wordt een standaard [XmlUrlResolver](../../../system.xml/xmlurlresolver/) zonder gebruikersreferenties gebruikt om het stijlsheet te openen. De standaard [XmlUrlResolver](../../../system.xml/xmlurlresolver/) wordt niet gebruikt om externe bronnen in het stijlsheet op te lossen, zodat **xsl:import** en **xsl:include** elementen niet worden opgelost. De [XmlResolver](../../../system.xml/xmlresolver/) wordt niet gecached nadat deze methode is voltooid. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslTransform](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)