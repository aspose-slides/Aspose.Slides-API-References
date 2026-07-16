---
title: GetPresentationInfo()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouvel objet PresentationInfo à partir d'un fichier et lie la présentation à celui-ci.
type: docs
weight: 27
url: /fr/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) méthode

Crée un nouvel objet [PresentationInfo](../../presentationinfo/) à partir du fichier et lie la présentation à celui-ci.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) fichier. |

### Valeur de retour

[Presentation](../../presentation/) informations liées à la présentation.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) méthode

Crée un nouvel objet [PresentationInfo](../../presentationinfo/) à partir du flux et lie la présentation à celui-ci. Obtient des informations sur la présentation dans le flux spécifié.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) flux. |

### Valeur de retour

[Presentation](../../presentation/) informations liées à la présentation.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationInfo](../../ipresentationinfo/)
* Class [String](../../../system/string/)
* Class [PresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)