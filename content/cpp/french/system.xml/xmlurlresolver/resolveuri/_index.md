---
title: ResolveUri()
second_title: Référence API Aspose.Slides pour C++
description: Résout l'URI absolu à partir des URI de base et relatives.
type: docs
weight: 66
url: /fr/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) méthode

Résout l'URI absolu à partir des URI de base et relatifs.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI de base utilisé pour résoudre l'URI relative. |
| relativeUri | [String](../../../system/string/) | L'URI à résoudre. L'URI peut être absolu ou relatif. Si absolu, cette valeur remplace effectivement la valeur **baseUri**. Si relatif, elle se combine avec la **baseUri** pour former un URI absolu. |

### Valeur de retour

L'URI absolu, ou **nullptr** si l'URI relative ne peut pas être résolue.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [XmlUrlResolver](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)