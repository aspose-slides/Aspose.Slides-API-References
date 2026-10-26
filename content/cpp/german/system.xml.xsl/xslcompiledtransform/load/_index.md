---
title: Load()
second_title: Aspose.Slides für C++ API-Referenz
description: Kompiliert das Stylesheet, das im XmlReader enthalten ist.
type: docs
weight: 27
url: /de/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) Methode

Kompiliert das Stylesheet, das in [XmlReader](../../../system.xml/xmlreader/) enthalten ist.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ein [XmlReader](../../../system.xml/xmlreader/), das das Stylesheet enthält. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) Methode

Kompiliert das XSLT-Stylesheet, das in [XmlReader](../../../system.xml/xmlreader/) enthalten ist. [XmlResolver](../../../system.xml/xmlresolver/) löst alle XSLT-**import**- oder **include**-Elemente auf und die XSLT-Einstellungen bestimmen die Berechtigungen für das Stylesheet.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Der [XmlReader](../../../system.xml/xmlreader/), der das Stylesheet enthält. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | Die [XsltSettings](../../xsltsettings/), die auf das Stylesheet angewendet wird. Wenn dies **nullptr** ist, wird die [XsltSettings::get_Default](../../xsltsettings/get_default/)-Einstellung angewendet. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/), der verwendet wird, um alle in XSLT-**import**- und **include**-Elementen referenzierten Stylesheets aufzulösen. Wenn dies **nullptr** ist, werden externe Ressourcen nicht aufgelöst. |

## XslCompiledTransform::Load(const String\&) Methode

Lädt und kompiliert das Stylesheet, das unter der angegebenen URI liegt.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | Die URI des Stylesheets. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) Methode

Lädt und kompiliert das XSLT-Stylesheet, das durch die URI angegeben ist. [XmlResolver](../../../system.xml/xmlresolver/) löst alle XSLT-**import**- oder **include**-Elemente auf und die XSLT-Einstellungen bestimmen die Berechtigungen für das Stylesheet.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | Die URI des Stylesheets. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | Die [XsltSettings](../../xsltsettings/), die auf das Stylesheet angewendet wird. Wenn dies **nullptr** ist, wird die [XsltSettings::get_Default](../../xsltsettings/get_default/)-Einstellung angewendet. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/), der verwendet wird, um die Stylesheet-URI und alle in XSLT-**import**- und **include**-Elementen referenzierten Stylesheets aufzulösen. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) Methode

Kompiliert das Stylesheet, das im IXPathNavigable-Objekt enthalten ist.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das das IXPathNavigable-Interface implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das das Stylesheet enthält. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) Methode

Kompiliert das XSLT-Stylesheet, das im IXPathNavigable enthalten ist. [XmlResolver](../../../system.xml/xmlresolver/) löst alle XSLT-**import**- oder **include**-Elemente auf und die XSLT-Einstellungen bestimmen die Berechtigungen für das Stylesheet.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ein Objekt, das das IXPathNavigable-Interface implementiert. Es kann entweder ein [XmlNode](../../../system.xml/xmlnode/) (typischerweise ein [XmlDocument](../../../system.xml/xmldocument/)) oder ein XPathDocument sein, das das Stylesheet enthält. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | Die [XsltSettings](../../xsltsettings/), die auf das Stylesheet angewendet wird. Wenn dies **nullptr** ist, wird die [XsltSettings::get_Default](../../xsltsettings/get_default/)-Einstellung angewendet. |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | Der [XmlResolver](../../../system.xml/xmlresolver/), der verwendet wird, um alle in XSLT-**import**- und **include**-Elementen referenzierten Stylesheets aufzulösen. Wenn dies **nullptr** ist, werden externe Ressourcen nicht aufgelöst. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Klasse [XslCompiledTransform](../)
* Klasse [XsltSettings](../../xsltsettings/)
* Klasse [XmlResolver](../../../system.xml/xmlresolver/)
* Klasse [String](../../../system/string/)
* Klasse [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Namensraum [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)