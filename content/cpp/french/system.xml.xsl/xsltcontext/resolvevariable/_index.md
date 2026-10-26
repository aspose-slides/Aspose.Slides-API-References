---
title: ResolveVariable()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est substituée dans une classe dérivée, résout une référence de variable et renvoie un IXsltContextVariable représentant la variable.
type: docs
weight: 14
url: /fr/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) méthode

Lorsqu'elle est substituée dans une classe dérivée, résout une référence de variable et renvoie un [IXsltContextVariable](../../ixsltcontextvariable/) représentant la variable.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Le préfixe de la variable tel qu'il apparaît dans l'expression [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | Le nom de la variable. |

### Valeur de retour

Un [IXsltContextVariable](../../ixsltcontextvariable/) représentant la variable au moment de l'exécution.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IXsltContextVariable](../../ixsltcontextvariable/)
* Classe [String](../../../system/string/)
* Classe [XsltContext](../)
* Espace de noms [System::Xml::Xsl](../../)
* Bibliothèque [Aspose.Slides](../../../)