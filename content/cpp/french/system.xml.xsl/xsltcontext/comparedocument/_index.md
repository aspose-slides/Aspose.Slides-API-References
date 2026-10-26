---
title: CompareDocument()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est remplacée dans une classe dérivée, compare les identifiants de ressources uniformes (URI) de base de deux documents en fonction de l'ordre dans lequel les documents ont été chargés par le processeur XSLT (c’est-à-dire, la classe XslTransform).
type: docs
weight: 53
url: /fr/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) méthode


Lorsqu'elle est remplacée dans une classe dérivée, compare les identifiants de ressources uniformes (URI) de base de deux documents en fonction de l'ordre dans lequel les documents ont été chargés par le processeur XSLT (c’est-à-dire, la [XslTransform](../../xsltransform/) classe).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | L'URI de base du premier document à comparer. |
| nextbaseUri | [String](../../../system/string/) | L'URI de base du deuxième document à comparer. |

### Valeur de retour

Une valeur entière décrivant l'ordre relatif des deux URI de base : -1 si **baseUri** apparaît avant **nextbaseUri** ; 0 si les deux URI de base sont identiques ; et 1 si **baseUri** apparaît après **nextbaseUri**.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XsltContext](../)
* Espace de noms [System::Xml::Xsl](../../)
* Bibliothèque [Aspose.Slides](../../../)