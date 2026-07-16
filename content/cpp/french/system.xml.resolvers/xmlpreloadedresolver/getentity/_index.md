---
title: GetEntity()
second_title: Référence de l'API Aspose.Slides pour C++
description: Mappe un URI à un objet contenant la ressource réelle.
type: docs
weight: 53
url: /fr/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) méthode

Mappe un URI à un objet contenant la ressource réelle.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI retourné par l'appel [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Actuellement non utilisé. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Le type d'objet à retourner. Le [XmlPreloadedResolver](../) prend en charge les objets Stream et les objets TextReader pour les URI qui ont été ajoutés en tant que [String](../../../system/string/). Si le type demandé n'est pas pris en charge par le résolveur, une exception sera levée. Utilisez la méthode XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) pour déterminer si un certain **Type** est pris en charge par ce résolveur. |

### Valeur de retour

Un objet Stream ou TextReader correspondant à la source réelle.

## Voir également

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlPreloadedResolver](../)
* Espace de noms [System::Xml::Resolvers](../../)
* Bibliothèque [Aspose.Slides](../../../)