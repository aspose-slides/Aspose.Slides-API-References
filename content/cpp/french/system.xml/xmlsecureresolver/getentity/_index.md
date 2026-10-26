---
title: GetEntity()
second_title: Référence de l'API Aspose.Slides pour C++
description: Mappe un URI à un objet qui contient la ressource réelle.
type: docs
weight: 27
url: /fr/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

Mappe un URI à un objet qui contient la ressource réelle.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI qui est renvoyé par l'appel [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Actuellement non utilisé. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Le type d'objet à renvoyer. La version actuelle ne renvoie que des objets Stream. |

### Valeur de retour

Le flux renvoyé par l'appel de **GetEntity** sur le [XmlResolver](../../xmlresolver/) sous-jacent. Si un type autre que Stream est spécifié, la méthode renvoie **nullptr**.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlSecureResolver](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)