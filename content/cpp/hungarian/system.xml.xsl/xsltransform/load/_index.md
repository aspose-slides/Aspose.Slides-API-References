---
title: Load()
second_title: Aspose.Slides for C++ API Referenciája
description: Betölti az XmlReader-ben található XSLT stíluslapot.
type: docs
weight: 27
url: /hu/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) method

Betölti a [XmlReader](../../../system.xml/xmlreader/)-ban található XSLT stíluslapot.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Egy [XmlReader](../../../system.xml/xmlreader/) objektum, amely tartalmazza az XSLT stíluslapot. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Betölti a [XmlReader](../../../system.xml/xmlreader/)-ban található XSLT stíluslapot.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Egy [XmlReader](../../../system.xml/xmlreader/) objektum, amely tartalmazza az XSLT stíluslapot. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a **xsl:import** és **xsl:include** elemekben hivatkozott bármely stíluslap betöltésére szolgál. Ha ez **nullptr**, a külső erőforrások nem kerülnek feloldásra. A [XmlResolver](../../../system.xml/xmlresolver/) nem kerül gyorsítótárba a metódus befejezése után. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method

Betölti az IXPathNavigable-ban található XSLT stíluslapot.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Az IXPathNavigable interfészt megvalósító objektum. Lehet egy [XmlNode](../../../system.xml/xmlnode/) (általában egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy XPathDocument, amely tartalmazza az XSLT stíluslapot. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Betölti az IXPathNavigable-ban található XSLT stíluslapot.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Az IXPathNavigable interfészt megvalósító objektum. Lehet egy [XmlNode](../../../system.xml/xmlnode/) (általában egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy XPathDocument, amely tartalmazza az XSLT stíluslapot. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a **xsl:import** és **xsl:include** elemekben hivatkozott bármely stíluslap betöltésére szolgál. Ha ez **nullptr**, a külső erőforrások nem kerülnek feloldásra. A [XmlResolver](../../../system.xml/xmlresolver/) nem kerül gyorsítótárba a metódus befejezése után. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) method

Betölti az XPathNavigator-ban található XSLT stíluslapot.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Egy XPathNavigator objektum, amely tartalmazza az XSLT stíluslapot. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Betölti az XPathNavigator-ban található XSLT stíluslapot.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Egy XPathNavigator objektum, amely tartalmazza az XSLT stíluslapot. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a **xsl:import** és **xsl:include** elemekben hivatkozott bármely stíluslap betöltésére szolgál. Ha ez **nullptr**, a külső erőforrások nem kerülnek feloldásra. A [XmlResolver](../../../system.xml/xmlresolver/) nem kerül gyorsítótárba a metódus befejezése után. |

## XslTransform::Load(const String\&) method

Betölti a URL által megadott XSLT stíluslapot.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Az URL, amely meghatározza a betöltendő XSLT stíluslapot. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Betölti a URL által megadott XSLT stíluslapot.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Az URL, amely meghatározza a betöltendő XSLT stíluslapot. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a stíluslap és a **xsl:import** illetve **xsl:include** elemekben hivatkozott bármely stíluslap betöltésére használható. Ha ez **nullptr**, egy alapértelmezett [XmlUrlResolver](../../../system.xml/xmlurlresolver/) felhasználói hitelesítés nélkül kerül felhasználásra a stíluslap megnyitásához. Az alapértelmezett [XmlUrlResolver](../../../system.xml/xmlurlresolver/) nem használatos a stíluslapban lévő külső erőforrások feloldására, így a **xsl:import** és **xsl:include** elemek nem kerülnek feloldásra. A [XmlResolver](../../../system.xml/xmlresolver/) nem kerül gyorsítótárba a metódus befejezése után. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlReader](../../../system.xml/xmlreader/)
* Osztály [XslTransform](../)
* Osztály [XmlResolver](../../../system.xml/xmlresolver/)
* Osztály [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Osztály [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Osztály [String](../../../system/string/)
* Névtér [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)