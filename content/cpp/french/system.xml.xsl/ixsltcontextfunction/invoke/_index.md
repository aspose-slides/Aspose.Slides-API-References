---
title: Invoke()
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit la méthode permettant d'appeler la fonction avec les arguments fournis dans le contexte donné.
type: docs
weight: 53
url: /fr/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) méthode

Fournit la méthode permettant d’invoquer la fonction avec les arguments fournis dans le contexte donné.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Le contexte XSLT pour l’appel de la fonction. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Les arguments de l’appel de la fonction. Chaque argument est un élément du tableau. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Le nœud de contexte pour l’appel de la fonction. |

### Valeur de retour

Un [Object](../../../system/object/) représentant la valeur de retour de la fonction.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [XsltContext](../../xsltcontext/)
* Classe [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Classe [IXsltContextFunction](../)
* Espace de noms [System::Xml::Xsl](../../)
* Bibliothèque [Aspose.Slides](../../../)