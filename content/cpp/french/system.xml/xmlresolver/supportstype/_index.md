---
title: SupportsType()
second_title: Référence API Aspose.Slides pour C++
description: Permet au résolveur de renvoyer des types autres que Stream.
type: docs
weight: 40
url: /fr/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) méthode

Permet au résolveur de renvoyer des types autres que Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Le type à renvoyer. |

### Valeur de retour

**true** si le **type** est pris en charge ; sinon, **false**.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlResolver](../)
* Espace de noms [System::Xml](../../)
* Library [Aspose.Slides](../../../)