---
title: Compile()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compile l'expression XPath spécifiée et renvoie un objet XPathExpression représentant l'expression XPath.
type: docs
weight: 66
url: /fr/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) method


Compile l'expression [XPath](../../) spécifiée et renvoie un objet [XPathExpression](../) représentant l'expression [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Une expression [XPath](../../). |

### Valeur de retour

Un objet [XPathExpression](../).

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) method


Compile l'expression [XPath](../../) spécifiée, avec l'objet [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) indiqué pour la résolution d'espace de noms, et renvoie un objet [XPathExpression](../) qui représente l'expression [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Une expression [XPath](../../). |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Un objet qui implémente l'interface [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) pour la résolution d'espace de noms. |

### Valeur de retour

Un objet [XPathExpression](../).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathExpression](../)
* Classe [String](../../../system/string/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)