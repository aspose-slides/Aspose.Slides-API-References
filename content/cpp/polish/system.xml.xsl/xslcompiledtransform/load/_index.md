---
title: Load()
second_title: Odniesienie API Aspose.Slides dla C++
description: Kompiluje arkusz stylów zawarty w XmlReader.
type: docs
weight: 27
url: /pl/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) metoda

Kompiluje arkusz stylów zawarty w [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) zawierający arkusz stylów. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) metoda

Kompiluje arkusz stylów XSLT zawarty w [XmlReader](../../../system.xml/xmlreader/). [XmlResolver](../../../system.xml/xmlresolver/) rozwiązuje wszystkie elementy XSLT **import** lub **include**, a ustawienia XSLT określają uprawnienia dla arkusza stylów.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) zawierający arkusz stylów. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | [XsltSettings](../../xsltsettings/) stosowane do arkusza stylów. Jeśli jest to **nullptr**, zastosowane jest ustawienie [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania arkuszy stylów odwoływanych w elementach XSLT **import** i **include**. Jeśli jest to **nullptr**, zasoby zewnętrzne nie są rozwiązywane. |

## XslCompiledTransform::Load(const String\&) metoda

Wczytuje i kompiluje arkusz stylów znajdujący się pod podanym adresem URI.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | Adres URI arkusza stylów. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) metoda

Wczytuje i kompiluje arkusz stylów XSLT określony przez adres URI. [XmlResolver](../../../system.xml/xmlresolver/) rozwiązuje wszystkie elementy XSLT **import** lub **include**, a ustawienia XSLT określają uprawnienia dla arkusza stylów.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | Adres URI arkusza stylów. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | [XsltSettings](../../xsltsettings/) stosowane do arkusza stylów. Jeśli jest to **nullptr**, zastosowane jest ustawienie [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania adresu URI arkusza stylów oraz arkuszy stylów odwoływanych w elementach XSLT **import** i **include**. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) metoda

Kompiluje arkusz stylów zawarty w obiekcie IXPathNavigable.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający arkusz stylów. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) metoda

Kompiluje arkusz stylów XSLT zawarty w IXPathNavigable. [XmlResolver](../../../system.xml/xmlresolver/) rozwiązuje wszystkie elementy XSLT **import** lub **include**, a ustawienia XSLT określają uprawnienia dla arkusza stylów.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający arkusz stylów. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | [XsltSettings](../../xsltsettings/) stosowane do arkusza stylów. Jeśli jest to **nullptr**, zastosowane jest ustawienie [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania wszystkich arkuszy stylów odwoływanych w elementach XSLT **import** i **include**. Jeśli jest to **nullptr**, zasoby zewnętrzne nie są rozwiązywane. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslCompiledTransform](../)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [String](../../../system/string/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)