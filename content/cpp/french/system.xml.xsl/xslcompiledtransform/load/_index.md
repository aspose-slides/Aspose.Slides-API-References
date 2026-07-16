---
title: Load()
second_title: Référence de l'API Aspose.Slides for C++
description: Compile la feuille de style contenue dans le XmlReader.
type: docs
weight: 27
url: /fr/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) méthode


Compile la feuille de style contenue dans le [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) contenant la feuille de style. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) méthode


Compile la feuille de style XSLT contenue dans le [XmlReader](../../../system.xml/xmlreader/). Le [XmlResolver](../../../system.xml/xmlresolver/) résout tout élément XSLT **import** ou **include** et les paramètres XSLT déterminent les autorisations pour la feuille de style.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Le [XmlReader](../../../system.xml/xmlreader/) contenant la feuille de style. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | Le [XsltSettings](../../xsltsettings/) à appliquer à la feuille de style. Si ceci est **nullptr**, le paramètre [XsltSettings::get_Default](../../xsltsettings/get_default/) est appliqué. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre toute feuille de style référencée dans les éléments XSLT **import** et **include**. Si ceci est **nullptr**, les ressources externes ne sont pas résolues. |

## XslCompiledTransform::Load(const String\&) méthode


Charge et compile la feuille de style située à l'URI spécifié.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | L'URI de la feuille de style. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) méthode


Charge et compile la feuille de style XSLT spécifiée par l'URI. Le [XmlResolver](../../../system.xml/xmlresolver/) résout tout élément XSLT **import** ou **include** et les paramètres XSLT déterminent les autorisations pour la feuille de style.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | L'URI de la feuille de style. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | Le [XsltSettings](../../xsltsettings/) à appliquer à la feuille de style. Si ceci est **nullptr**, le paramètre [XsltSettings::get_Default](../../xsltsettings/get_default/) est appliqué. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre l'URI de la feuille de style et toute feuille de style référencée dans les éléments XSLT **import** et **include**. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) méthode


Compile la feuille de style contenue dans l'objet IXPathNavigable.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l'interface IXPathNavigable. Il peut être soit un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), soit un XPathDocument contenant la feuille de style. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) méthode


Compile la feuille de style XSLT contenue dans l'IXPathNavigable. Le [XmlResolver](../../../system.xml/xmlresolver/) résout tout élément XSLT **import** ou **include** et les paramètres XSLT déterminent les autorisations pour la feuille de style.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l'interface IXPathNavigable. Il peut être soit un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), soit un XPathDocument contenant la feuille de style. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | Le [XsltSettings](../../xsltsettings/) à appliquer à la feuille de style. Si ceci est **nullptr**, le paramètre [XsltSettings::get_Default](../../xsltsettings/get_default/) est appliqué. |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre toute feuille de style référencée dans les éléments XSLT **import** et **include**. Si ceci est **nullptr**, les ressources externes ne sont pas résolues. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslCompiledTransform](../)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [String](../../../system/string/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)