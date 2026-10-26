---
title: GetEntity()
second_title: Référence de l'API Aspose.Slides pour C++
description: Mappe un URI à un objet contenant la ressource réelle.
type: docs
weight: 14
url: /fr/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) méthode


Mappe un URI à un objet contenant la ressource réelle.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | URI absolu vers l'objet. |

### Valeur de retour

Un objet [System::IO::Stream](../../../system.io/stream/) ou null si la ressource ne peut pas être diffusée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [String](../../../system/string/)
* Classe [ExternalResourceResolver](../)
* Espace de noms [Aspose::Slides::Import](../../)
* Bibliothèque [Aspose.Slides](../../../)