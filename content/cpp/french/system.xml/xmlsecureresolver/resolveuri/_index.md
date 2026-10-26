---
title: ResolveUri()
second_title: Référence de l'API Aspose.Slides pour C++
description: Résout l'URI absolu à partir des URI de base et relatives en appelant ResolveUri sur le XmlResolver sous-jacent.
type: docs
weight: 40
url: /fr/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) méthode

Résout l'URI absolu à partir des URI de base et relatives en appelant **ResolveUri** sur le [XmlResolver](../../xmlresolver/) sous-jacent.

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI de base utilisé pour résoudre l'URI relative. |
| relativeUri | [String](../../../system/string/) | L'URI à résoudre. L'URI peut être absolu ou relatif. Si absolu, cette valeur remplace effectivement la valeur **baseUri**. Si relatif, il se combine avec **baseUri** pour créer un URI absolu. |

### Valeur de retour

L'URI absolu ou **nullptr** si l'URI relative ne peut pas être résolue (renvoyé en appelant **ResolveUri** sur le [XmlResolver](../../xmlresolver/) sous-jacent).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [XmlSecureResolver](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)