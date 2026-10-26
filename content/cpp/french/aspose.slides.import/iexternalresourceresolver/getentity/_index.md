---
title: GetEntity()
second_title: Référence API Aspose.Slides pour C++
description: Mappe un URI vers un objet contenant la ressource réelle.
type: docs
weight: 14
url: /fr/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) méthode


Mappe un URI vers un objet contenant la ressource réelle.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | URI absolu de l'objet. |

### Valeur de retour

Un objet [System::IO::Stream](../../../system.io/stream/) ou null si la ressource ne peut pas être diffusée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [String](../../../system/string/)
* Classe [IExternalResourceResolver](../)
* Espace de noms [Aspose::Slides::Import](../../)
* Bibliothèque [Aspose.Slides](../../../)