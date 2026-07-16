---
title: GetEntity()
second_title: Référence de l'API Aspose.Slides pour C++
description: Mappe un URI vers un objet contenant la ressource réelle.
type: docs
weight: 14
url: /fr/aspose.slides.import/htmlexternalresolver/getentity/
---
## HtmlExternalResolver::GetEntity(System::String) méthode

Mappe un URI vers un objet contenant la ressource réelle.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::HtmlExternalResolver::GetEntity(System::String absoluteUri) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | URI absolu vers l'objet. |

### Valeur de retour

Un objet [System::IO::Stream](../../../system.io/stream/) ou null si la ressource ne peut pas être diffusée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [String](../../../system/string/)
* Classe [HtmlExternalResolver](../)
* Espace de noms [Aspose::Slides::Import](../../)
* Bibliothèque [Aspose.Slides](../../../)