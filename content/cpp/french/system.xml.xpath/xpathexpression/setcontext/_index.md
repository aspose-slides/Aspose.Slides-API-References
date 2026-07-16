---
title: SetContext()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsque remplacée dans une classe dérivée, spécifie l'objet XmlNamespaceManager à utiliser pour la résolution des espaces de noms.
type: docs
weight: 53
url: /fr/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) méthode

Lorsqu'elle est remplacée dans une classe dérivée, spécifie l'objet [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) à utiliser pour la résolution des espaces de noms.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | Un objet [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) à utiliser pour la résolution des espaces de noms. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) méthode

Lorsqu'elle est remplacée dans une classe dérivée, spécifie l'objet [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) à utiliser pour la résolution des espaces de noms.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Un objet qui implémente l'interface [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) à utiliser pour la résolution des espaces de noms. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Classe [XPathExpression](../)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)