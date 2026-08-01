---
title: Load()
second_title: Aspose.Slides voor C++ API-referentie
description: Compileert het stijlblad dat in de XmlReader is opgenomen.
type: docs
weight: 27
url: /nl/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) methode

Compileert het stijlblad dat is opgenomen in de [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Een [XmlReader](../../../system.xml/xmlreader/) die het stijlblad bevat. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) methode

Compileert het XSLT-stijlblad dat is opgenomen in de [XmlReader](../../../system.xml/xmlreader/). De [XmlResolver](../../../system.xml/xmlresolver/) lost alle XSLT **import**- of **include**-elementen op en de XSLT-instellingen bepalen de rechten voor het stijlblad.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | De [XmlReader](../../../system.xml/xmlreader/) die het stijlblad bevat. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | De [XsltSettings](../../xsltsettings/) die op het stijlblad moet worden toegepast. Als dit **nullptr** is, wordt de [XsltSettings::get_Default](../../xsltsettings/get_default/) instelling toegepast. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om eventuele stijlbladen die in XSLT **import**- en **include**-elementen worden gerefereerd, op te lossen. Als dit **nullptr** is, worden externe bronnen niet opgelost. |

## XslCompiledTransform::Load(const String\&) methode

Laadt en compileert het stijlblad dat zich bevindt op de opgegeven URI.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | De URI van het stijlblad. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) methode

Laadt en compileert het XSLT-stijlblad dat is opgegeven door de URI. De [XmlResolver](../../../system.xml/xmlresolver/) lost alle XSLT **import**- of **include**-elementen op en de XSLT-instellingen bepalen de rechten voor het stijlblad.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | De URI van het stijlblad. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | De [XsltSettings](../../xsltsettings/) die op het stijlblad moet worden toegepast. Als dit **nullptr** is, wordt de [XsltSettings::get_Default](../../xsltsettings/get_default/) instelling toegepast. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om de URI van het stijlblad en eventuele stijlbladen die in XSLT **import**- en **include**-elementen worden gerefereerd, op te lossen. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) methode

Compileert het stijlblad dat is opgenomen in het IXPathNavigable-object.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) zijn (meestal een [XmlDocument](../../../system.xml/xmldocument/)), of een XPathDocument dat het stijlblad bevat. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) methode

Compileert het XSLT-stijlblad dat is opgenomen in de IXPathNavigable. De [XmlResolver](../../../system.xml/xmlresolver/) lost alle XSLT **import**- of **include**-elementen op en de XSLT-instellingen bepalen de rechten voor het stijlblad.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) zijn (meestal een [XmlDocument](../../../system.xml/xmldocument/)), of een XPathDocument dat het stijlblad bevat. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | De [XsltSettings](../../xsltsettings/) die op het stijlblad moet worden toegepast. Als dit **nullptr** is, wordt de [XsltSettings::get_Default](../../xsltsettings/get_default/) instelling toegepast. |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om eventuele stijlbladen die in XSLT **import**- en **include**-elementen worden gerefereerd, op te lossen. Als dit **nullptr** is, worden externe bronnen niet opgelost. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Klasse [XslCompiledTransform](../)
* Klasse [XsltSettings](../../xsltsettings/)
* Klasse [XmlResolver](../../../system.xml/xmlresolver/)
* Klasse [String](../../../system/string/)
* Klasse [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Naamruimte [System::Xml::Xsl](../../)
* Bibliotheek [Aspose.Slides](../../../)