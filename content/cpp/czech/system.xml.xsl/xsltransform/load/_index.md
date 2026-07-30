---
title: Load()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Načte XSLT stylový list obsažený v XmlReaderu.
type: docs
weight: 27
url: /cs/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) method


Načte XSLT stylový list obsažený v [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) objekt, který obsahuje XSLT stylový list. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Načte XSLT stylový list obsažený v [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) objekt, který obsahuje XSLT stylový list. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) používaný k načtení všech stylových listů odkazovaných v elementech **xsl:import** a **xsl:include**. Pokud je to **nullptr**, externí zdroje nejsou rozřešeny. [XmlResolver](../../../system.xml/xmlresolver/) není po dokončení této metody uložena do mezipaměti. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method


Načte XSLT stylový list obsažený v IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (typicky [XmlDocument](../../../system.xml/xmldocument/)), nebo XPathDocument obsahující XSLT stylový list. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Načte XSLT stylový list obsažený v IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (typicky [XmlDocument](../../../system.xml/xmldocument/)), nebo XPathDocument obsahující XSLT stylový list. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) používaný k načtení všech stylových listů odkazovaných v elementech **xsl:import** a **xsl:include**. Pokud je to **nullptr**, externí zdroje nejsou rozřešeny. [XmlResolver](../../../system.xml/xmlresolver/) není po dokončení této metody uložena do mezipaměti. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) method


Načte XSLT stylový list obsažený v XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Objekt XPathNavigator, který obsahuje XSLT stylový list. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Načte XSLT stylový list obsažený v XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Objekt XPathNavigator, který obsahuje XSLT stylový list. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) používaný k načtení všech stylových listů odkazovaných v elementech **xsl:import** a **xsl:include**. Pokud je to **nullptr**, externí zdroje nejsou rozřešeny. [XmlResolver](../../../system.xml/xmlresolver/) není po dokončení této metody uložena do mezipaměti. |

## XslTransform::Load(const String\&) method


Načte XSLT stylový list určený pomocí URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL, která určuje XSLT stylový list k načtení. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Načte XSLT stylový list určený pomocí URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL, která určuje XSLT stylový list k načtení. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) používaný k načtení stylového listu a všech stylových listů odkazovaných v elementech **xsl:import** a **xsl:include**. Pokud je to **nullptr**, je použito výchozí [XmlUrlResolver](../../../system.xml/xmlurlresolver/) bez uživatelských přihlašovacích údajů k otevření stylového listu. Výchozí [XmlUrlResolver](../../../system.xml/xmlurlresolver/) není používán k řešení externích zdrojů ve stylovém listu, takže elementy **xsl:import** a **xsl:include** nejsou rozřešeny. [XmlResolver](../../../system.xml/xmlresolver/) není po dokončení této metody uložena do mezipaměti. |

## See Also

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [XmlReader](../../../system.xml/xmlreader/)
* Třída [XslTransform](../)
* Třída [XmlResolver](../../../system.xml/xmlresolver/)
* Třída [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Třída [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml::Xsl](../../)
* Knihovna [Aspose.Slides](../../../)