---
title: GetEntity()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est surchargée dans une classe dérivée, elle associe une URI à un objet contenant la ressource réelle.
type: docs
weight: 14
url: /fr/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

Lorsqu’elle est surchargée dans une classe dérivée, elle associe une URI à un objet contenant la ressource réelle.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI renvoyé par l’appel [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Actuellement non utilisé. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Le type d'objet à retourner. La version actuelle ne renvoie que des objets Stream. |

### Valeur de retour

Un objet stream ou **nullptr** si un type autre que stream est spécifié.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlResolver](../)
* Espace de noms [System::Xml](../../)
* Library [Aspose.Slides](../../../)