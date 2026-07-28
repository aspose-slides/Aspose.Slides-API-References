---
title: Load()
second_title: Aspose.Slides C++ API hivatkozás
description: Lefordítja az XmlReader-ben lévő stíluslapot.
type: docs
weight: 27
url: /hu/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) metódus


A [XmlReader](../../../system.xml/xmlreader/)-ban lévő stíluslapot fordítja le.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Egy [XmlReader](../../../system.xml/xmlreader/), amely a stíluslapot tartalmazza. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) metódus


A [XmlReader](../../../system.xml/xmlreader/)-ban lévő XSLT stíluslapot fordítja le. A [XmlResolver](../../../system.xml/xmlresolver/) megoldja az összes XSLT **import** vagy **include** elemet, és az XSLT beállítások meghatározzák a stíluslap jogosultságait.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | A [XmlReader](../../../system.xml/xmlreader/), amely a stíluslapot tartalmazza. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | A [XsltSettings](../../xsltsettings/), amelyet a stíluslapra alkalmaznak. Ha ez **nullptr**, akkor a [XsltSettings::get_Default](../../xsltsettings/get_default/) beállítás kerül alkalmazásra. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/), amely az XSLT **import** és **include** elemekben hivatkozott stíluslapok feloldására szolgál. Ha ez **nullptr**, a külső erőforrások nem kerülnek feloldásra. |

## XslCompiledTransform::Load(const String\&) metódus


Betölti és lefordítja a megadott URI-n található stíluslapot.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | A stíluslap URI-ja. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) metódus


Betölti és lefordítja a megadott URI által meghatározott XSLT stíluslapot. A [XmlResolver](../../../system.xml/xmlresolver/) megoldja az összes XSLT **import** vagy **include** elemet, és az XSLT beállítások meghatározzák a stíluslap jogosultságait.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | A stíluslap URI-ja. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | A [XsltSettings](../../xsltsettings/), amelyet a stíluslapra alkalmaznak. Ha ez **nullptr**, akkor a [XsltSettings::get_Default](../../xsltsettings/get_default/) beállítás kerül alkalmazásra. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/), amely a stíluslap URI-ját és az XSLT **import** és **include** elemekben hivatkozott stíluslapokat oldja fel. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) metódus


Az IXPathNavigable objektumban lévő stíluslapot fordítja le.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Egy objektum, amely megvalósítja az IXPathNavigable interfészt. Lehet egy [XmlNode](../../../system.xml/xmlnode/) (jellemzően egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy XPathDocument, amely a stíluslapot tartalmazza. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) metódus


Az IXPathNavigable-ban lévő XSLT stíluslapot fordítja le. A [XmlResolver](../../../system.xml/xmlresolver/) megoldja az összes XSLT **import** vagy **include** elemet, és az XSLT beállítások meghatározzák a stíluslap jogosultságait.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Egy objektum, amely megvalósítja az IXPathNavigable interfészt. Lehet egy [XmlNode](../../../system.xml/xmlnode/) (jellemzően egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy XPathDocument, amely a stíluslapot tartalmazza. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | A [XsltSettings](../../xsltsettings/), amelyet a stíluslapra alkalmaznak. Ha ez **nullptr**, akkor a [XsltSettings::get_Default](../../xsltsettings/get_default/) beállítás kerül alkalmazásra. |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | A [XmlResolver](../../../system.xml/xmlresolver/), amely az XSLT **import** és **include** elemekben hivatkozott stíluslapok feloldására szolgál. Ha ez **nullptr**, a külső erőforrások nem kerülnek feloldásra. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlReader](../../../system.xml/xmlreader/)
* Osztály [XslCompiledTransform](../)
* Osztály [XsltSettings](../../xsltsettings/)
* Osztály [XmlResolver](../../../system.xml/xmlresolver/)
* Osztály [String](../../../system/string/)
* Osztály [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Névtér [System::Xml::Xsl](../../)
* Könyvtár [Aspose.Slides](../../../)