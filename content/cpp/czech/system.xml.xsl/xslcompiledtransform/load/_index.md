---
title: Load()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Zkompiluje stylový list obsažený v XmlReaderu.
type: docs
weight: 27
url: /cs/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) metoda

Zkompiluje stylový list obsažený v [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Objekt [XmlReader](../../../system.xml/xmlreader/) obsahující stylový list. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) metoda

Zkompiluje XSLT stylový list obsažený v [XmlReader](../../../system.xml/xmlreader/). [XmlResolver](../../../system.xml/xmlresolver/) řeší všechny XSLT **import** a **include** elementy a nastavení XSLT určují oprávnění pro stylový list.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Objekt [XmlReader](../../../system.xml/xmlreader/) obsahující stylový list. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | [XsltSettings](../../xsltsettings/) použité na stylový list. Pokud je **nullptr**, použije se nastavení [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) použitý k vyřešení všech stylových listů odkazovaných v XSLT **import** a **include** elementech. Pokud je **nullptr**, vnější zdroje nejsou řešeny. |

## XslCompiledTransform::Load(const String\&) metoda

Načte a zkompiluje stylový list umístěný na zadaném URI.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | URI stylového listu. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) metoda

Načte a zkompiluje XSLT stylový list určený URI. [XmlResolver](../../../system.xml/xmlresolver/) řeší všechny XSLT **import** a **include** elementy a nastavení XSLT určují oprávnění pro stylový list.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | URI stylového listu. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | [XsltSettings](../../xsltsettings/) použité na stylový list. Pokud je **nullptr**, použije se nastavení [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) použitý k vyřešení URI stylového listu a všech stylových listů odkazovaných v XSLT **import** a **include** elementech. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) metoda

Zkompiluje stylový list obsažený v objektu IXPathNavigable.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (obvykle [XmlDocument](../../../system.xml/xmldocument/)), nebo XPathDocument obsahující stylový list. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) metoda

Zkompiluje XSLT stylový list obsažený v IXPathNavigable. [XmlResolver](../../../system.xml/xmlresolver/) řeší všechny XSLT **import** a **include** elementy a nastavení XSLT určují oprávnění pro stylový list.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (obvykle [XmlDocument](../../../system.xml/xmldocument/)), nebo XPathDocument obsahující stylový list. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | [XsltSettings](../../xsltsettings/) použité na stylový list. Pokud je **nullptr**, použije se nastavení [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | [XmlResolver](../../../system.xml/xmlresolver/) použité k vyřešení všech stylových listů odkazovaných v XSLT **import** a **include** elementech. Pokud je **nullptr**, vnější zdroje nejsou řešeny. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslCompiledTransform](../)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [String](../../../system/string/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)