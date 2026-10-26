---
title: PreserveWhitespace()
second_title: Référence API Aspose.Slides pour C++
description: Lorsqu'il est remplacé dans une classe dérivée, il évalue s'il faut conserver les nœuds d'espace blanc ou les supprimer pour le contexte donné.
type: docs
weight: 40
url: /fr/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) method


Lorsqu’il est remplacé dans une classe dérivée, il évalue s’il faut conserver les nœuds d’espace blanc ou les supprimer pour le contexte donné.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Le nœud d’espace blanc qui doit être conservé ou supprimé dans le contexte actuel. |

### Valeur de retour

**true** si l’espace blanc doit être conservé ; **false** si l’espace blanc doit être supprimé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Classe [XsltContext](../)
* Espace de noms [System::Xml::Xsl](../../)
* Bibliothèque [Aspose.Slides](../../../)