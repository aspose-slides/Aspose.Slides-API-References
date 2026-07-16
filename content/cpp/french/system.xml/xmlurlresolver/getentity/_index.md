---
title: GetEntity()
second_title: Référence API Aspose.Slides pour C++
description: Associe un URI à un objet contenant la ressource réelle.
type: docs
weight: 53
url: /fr/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) méthode

Associe un URI à un objet contenant la ressource réelle.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI retourné par l'appel [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Actuellement non utilisé. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Le type d'objet à renvoyer. L'implémentation actuelle ne renvoie que des objets Stream. |

### Valeur de retour

Un objet Stream ou **nullptr** si un type autre que Stream est spécifié.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlUrlResolver](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)