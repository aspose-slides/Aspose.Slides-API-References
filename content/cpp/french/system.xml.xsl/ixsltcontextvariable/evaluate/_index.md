---
title: Evaluate()
second_title: Référence API Aspose.Slides pour C++
description: Évalue la variable à l'exécution et renvoie un objet qui représente la valeur de la variable.
type: docs
weight: 40
url: /fr/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate(SharedPtr\<XsltContext\>) méthode


Évalue la variable à l'exécution et renvoie un objet qui représente la valeur de la variable.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Un [XsltContext](../../xsltcontext/) représentant le contexte d'exécution de la variable. |

### Valeur de retour

Un [Object](../../../system/object/) représentant la valeur de la variable. Les types de retour possibles incluent number, string, [Boolean](../../../system/boolean/), fragment de document ou ensemble de nœuds.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [XsltContext](../../xsltcontext/)
* Classe [IXsltContextVariable](../)
* Espace de noms [System::Xml::Xsl](../../)
* Bibliothèque [Aspose.Slides](../../../)