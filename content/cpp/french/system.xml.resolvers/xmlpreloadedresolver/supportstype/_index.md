---
title: SupportsType()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si le résolveur prend en charge d'autres Types que simplement Stream.
type: docs
weight: 66
url: /fr/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) méthode

Détermine si le résolveur prend en charge d'autres Types que simplement Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI absolu à vérifier. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Le Type à renvoyer. |

### Valeur de retour

**true** si le Type est pris en charge ; sinon, **false**.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)