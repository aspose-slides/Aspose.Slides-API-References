---
title: ResolveUri()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Lorsqu'elle est redéfinie dans une classe dérivée, résout l'URI absolu à partir des URI de base et relatives.
type: docs
weight: 27
url: /fr/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) méthode

Lorsqu'elle est redéfinie dans une classe dérivée, résout l'URI absolu à partir des URI de base et relatives.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI de base utilisé pour résoudre l'URI relative. |
| relativeUri | [String](../../../system/string/) | L'URI à résoudre. L'URI peut être absolu ou relatif. Si elle est absolue, cette valeur remplace effectivement la valeur **baseUri**. Si elle est relative, elle se combine avec **baseUri** pour former un URI absolu. |

### Valeur de retour

L'URI absolu ou **nullptr** si l'URI relative ne peut pas être résolue.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [XmlResolver](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)