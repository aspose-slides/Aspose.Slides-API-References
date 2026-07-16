---
title: ResolveUri()
second_title: Aspose.Slides pour la référence de l'API C++
description: Résout l'URI absolu à partir des URI de base et relatifs.
type: docs
weight: 40
url: /fr/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) méthode

Résout l'URI absolu à partir des URI de base et relatifs.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI de base utilisé pour résoudre l'URI relative. |
| relativeUri | [String](../../../system/string/) | L'URI à résoudre. L'URI peut être absolu ou relatif. S'il est absolu, cette valeur remplace efficacement la valeur **baseUri**. S'il est relatif, elle se combine avec **baseUri** pour former un URI absolu. |

### Valeur de retour

Le [Uri](../../../system/uri/) représentant l'URI absolu ou **nullptr** si l'URI relative ne peut pas être résolue.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [XmlPreloadedResolver](../)
* Espace de noms [System::Xml::Resolvers](../../)
* Bibliothèque [Aspose.Slides](../../../)