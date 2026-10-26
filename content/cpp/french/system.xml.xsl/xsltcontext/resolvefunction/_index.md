---
title: ResolveFunction()
second_title: Référence API Aspose.Slides pour C++
description: Lorsqu'elle est remplacée dans une classe dérivée, résout une référence de fonction et renvoie un IXsltContextFunction représentant la fonction. Le IXsltContextFunction est utilisé au moment de l'exécution pour obtenir la valeur de retour de la fonction.
type: docs
weight: 27
url: /fr/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) méthode

Lorsqu'elle est remplacée dans une classe dérivée, résout une référence de fonction et renvoie un [IXsltContextFunction](../../ixsltcontextfunction/) représentant la fonction. Le [IXsltContextFunction](../../ixsltcontextfunction/) est utilisé au moment de l'exécution pour obtenir la valeur de retour de la fonction.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Le préfixe de la fonction tel qu'il apparaît dans l'expression [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | Le nom de la fonction. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | Un tableau de types d'argument pour la fonction résolue. Cela vous permet de choisir entre des méthodes portant le même nom (par exemple, des méthodes surchargées). |

### Valeur de retour

Un [IXsltContextFunction](../../ixsltcontextfunction/) représentant la fonction.

## Voir aussi

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IXsltContextFunction](../../ixsltcontextfunction/)
* Classe [String](../../../system/string/)
* Classe [XsltContext](../)
* Espace de noms [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)