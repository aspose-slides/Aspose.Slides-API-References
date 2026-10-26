---
title: Load()
second_title: Référence de l'API Aspose.Slides for C++
description: Charge la feuille de style XSLT contenue dans le XmlReader.
type: docs
weight: 27
url: /fr/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) méthode


Charge la feuille de style XSLT contenue dans le [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un objet [XmlReader](../../../system.xml/xmlreader/) qui contient la feuille de style XSLT. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) méthode


Charge la feuille de style XSLT contenue dans le [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un objet [XmlReader](../../../system.xml/xmlreader/) qui contient la feuille de style XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour charger toutes les feuilles de style référencées dans les éléments **xsl:import** et **xsl:include**. Si c'est **nullptr**, les ressources externes ne sont pas résolues. Le [XmlResolver](../../../system.xml/xmlresolver/) n'est pas mis en cache après la fin de cette méthode. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) méthode


Charge la feuille de style XSLT contenue dans l'IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l'interface IXPathNavigable. Il peut s'agir soit d'un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), soit d'un XPathDocument contenant la feuille de style XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) méthode


Charge la feuille de style XSLT contenue dans l'IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l'interface IXPathNavigable. Il peut s'agir soit d'un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), soit d'un XPathDocument contenant la feuille de style XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour charger toutes les feuilles de style référencées dans les éléments **xsl:import** et **xsl:include**. Si c'est **nullptr**, les ressources externes ne sont pas résolues. Le [XmlResolver](../../../system.xml/xmlresolver/) n'est pas mis en cache après la fin de cette méthode. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) méthode


Charge la feuille de style XSLT contenue dans le XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un objet XPathNavigator qui contient la feuille de style XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) méthode


Charge la feuille de style XSLT contenue dans le XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un objet XPathNavigator qui contient la feuille de style XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour charger toutes les feuilles de style référencées dans les éléments **xsl:import** et **xsl:include**. Si c'est **nullptr**, les ressources externes ne sont pas résolues. Le [XmlResolver](../../../system.xml/xmlresolver/) n'est pas mis en cache après la fin de cette méthode. |

## XslTransform::Load(const String\&) méthode


Charge la feuille de style XSLT spécifiée par une URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L'URL qui spécifie la feuille de style XSLT à charger. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) méthode


Charge la feuille de style XSLT spécifiée par une URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L'URL qui spécifie la feuille de style XSLT à charger. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) à utiliser pour charger la feuille de style et toutes les feuilles de style référencées dans les éléments **xsl:import** et **xsl:include**. Si c'est **nullptr**, un [XmlUrlResolver](../../../system.xml/xmlurlresolver/) par défaut sans informations d'identification utilisateur est utilisé pour ouvrir la feuille de style. Le [XmlUrlResolver](../../../system.xml/xmlurlresolver/) par défaut n'est pas utilisé pour résoudre les ressources externes de la feuille de style, ainsi les éléments **xsl:import** et **xsl:include** ne sont pas résolus. Le [XmlResolver](../../../system.xml/xmlresolver/) n'est pas mis en cache après la fin de cette méthode. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Classe [XslTransform](../)
* Classe [XmlResolver](../../../system.xml/xmlresolver/)
* Classe [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Classe [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml::Xsl](../../)
* Bibliothèque [Aspose.Slides](../../../)