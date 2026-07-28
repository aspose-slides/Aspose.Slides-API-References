---
title: Load()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ładuje arkusz stylów XSLT zawarty w XmlReader.
type: docs
weight: 27
url: /pl/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) metoda


Ładuje arkusz stylów XSLT zawarty w [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Obiekt [XmlReader](../../../system.xml/xmlreader/) zawierający arkusz stylów XSLT. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda


Ładuje arkusz stylów XSLT zawarty w [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Obiekt [XmlReader](../../../system.xml/xmlreader/) zawierający arkusz stylów XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do ładowania wszelkich arkuszy stylów odwoływanych w elementach **xsl:import** i **xsl:include**. Jeśli jest **nullptr**, zasoby zewnętrzne nie są rozwiązywane. [XmlResolver](../../../system.xml/xmlresolver/) nie jest buforowany po zakończeniu tej metody. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) metoda


Ładuje arkusz stylów XSLT zawarty w IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający arkusz stylów XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda


Ładuje arkusz stylów XSLT zawarty w IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający arkusz stylów XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do ładowania wszelkich arkuszy stylów odwoływanych w elementach **xsl:import** i **xsl:include**. Jeśli jest **nullptr**, zasoby zewnętrzne nie są rozwiązywane. [XmlResolver](../../../system.xml/xmlresolver/) nie jest buforowany po zakończeniu tej metody. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) metoda


Ładuje arkusz stylów XSLT zawarty w XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Obiekt XPathNavigator zawierający arkusz stylów XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda


Ładuje arkusz stylów XSLT zawarty w XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Obiekt XPathNavigator zawierający arkusz stylów XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do ładowania wszelkich arkuszy stylów odwoływanych w elementach **xsl:import** i **xsl:include**. Jeśli jest **nullptr**, zasoby zewnętrzne nie są rozwiązywane. [XmlResolver](../../../system.xml/xmlresolver/) nie jest buforowany po zakończeniu tej metody. |

## XslTransform::Load(const String\&) metoda


Ładuje arkusz stylów XSLT określony przez adres URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Adres URL określający arkusz stylów XSLT do załadowania. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda


Ładuje arkusz stylów XSLT określony przez adres URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Adres URL określający arkusz stylów XSLT do załadowania. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do ładowania arkusza stylów oraz wszelkich arkuszy stylów odwoływanych w elementach **xsl:import** i **xsl:include**. Jeśli jest **nullptr**, używany jest domyślny [XmlUrlResolver](../../../system.xml/xmlurlresolver/) bez danych uwierzytelniających użytkownika do otwarcia arkusza stylów. Domyślny [XmlUrlResolver](../../../system.xml/xmlurlresolver/) nie jest używany do rozwiązywania jakichkolwiek zasobów zewnętrznych w arkuszu stylów, więc elementy **xsl:import** i **xsl:include** nie są rozwiązywane. [XmlResolver](../../../system.xml/xmlresolver/) nie jest buforowany po zakończeniu tej metody. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlReader](../../../system.xml/xmlreader/)
* Klasa [XslTransform](../)
* Klasa [XmlResolver](../../../system.xml/xmlresolver/)
* Klasa [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Klasa [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml::Xsl](../../)
* Biblioteka [Aspose.Slides](../../../)