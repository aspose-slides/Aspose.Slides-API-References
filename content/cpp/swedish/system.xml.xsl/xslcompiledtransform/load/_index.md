---
title: Load()
second_title: Aspose.Slides för C++ API-referens
description: Kompilerar stilarket som finns i XmlReader.
type: docs
weight: 27
url: /sv/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) metod


Kompilerar stilarket som finns i [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ett [XmlReader](../../../system.xml/xmlreader/) som innehåller stilarket. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) metod


Kompilerar XSLT-stilarket som finns i [XmlReader](../../../system.xml/xmlreader/). [XmlResolver](../../../system.xml/xmlresolver/) löser alla XSLT-**import**- eller **include**-element och XSLT-inställningarna bestämmer behörigheterna för stilarket.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Det [XmlReader](../../../system.xml/xmlreader/) som innehåller stilarket. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | Den [XsltSettings](../../xsltsettings/) som ska tillämpas på stilarket. Om detta är **nullptr**, används inställningen [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att lösa alla stilark som refereras i XSLT-**import**- och **include**-element. Om detta är **nullptr**, löses externa resurser inte. |

## XslCompiledTransform::Load(const String\&) metod


Laddar och kompilerar stilarket som finns på den angivna URI:n.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | URI:n för stilarket. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) metod


Laddar och kompilerar XSLT-stilarket som specificeras av URI:n. [XmlResolver](../../../system.xml/xmlresolver/) löser alla XSLT-**import**- eller **include**-element och XSLT-inställningarna bestämmer behörigheterna för stilarket.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | URI:n för stilarket. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | Den [XsltSettings](../../xsltsettings/) som ska tillämpas på stilarket. Om detta är **nullptr**, används inställningen [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att lösa stilarkets URI och alla stilark som refereras i XSLT-**import**- och **include**-element. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) metod


Kompilerar stilarket som finns i IXPathNavigable-objektet.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ett objekt som implementerar IXPathNavigable-gränssnittet. Det kan vara antingen en [XmlNode](../../../system.xml/xmlnode/) (vanligtvis en [XmlDocument](../../../system.xml/xmldocument/)) eller ett XPathDocument som innehåller stilarket. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) metod


Kompilerar XSLT-stilarket som finns i IXPathNavigable. [XmlResolver](../../../system.xml/xmlresolver/) löser alla XSLT-**import**- eller **include**-element och XSLT-inställningarna bestämmer behörigheterna för stilarket.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ett objekt som implementerar IXPathNavigable-gränssnittet. Det kan vara antingen en [XmlNode](../../../system.xml/xmlnode/) (vanligtvis en [XmlDocument](../../../system.xml/xmldocument/)) eller ett XPathDocument som innehåller stilarket. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | Den [XsltSettings](../../xsltsettings/) som ska tillämpas på stilarket. Om detta är **nullptr**, används inställningen [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att lösa alla stilark som refereras i XSLT-**import**- och **include**-element. Om detta är **nullptr**, löses externa resurser inte. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlReader](../../../system.xml/xmlreader/)
* Klass [XslCompiledTransform](../)
* Klass [XsltSettings](../../xsltsettings/)
* Klass [XmlResolver](../../../system.xml/xmlresolver/)
* Klass [String](../../../system/string/)
* Klass [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Namnrymd [System::Xml::Xsl](../../)
* Bibliotek [Aspose.Slides](../../../)