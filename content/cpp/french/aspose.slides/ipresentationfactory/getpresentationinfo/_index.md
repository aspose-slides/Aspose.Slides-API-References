---
title: GetPresentationInfo()
second_title: Référence API Aspose.Slides pour C++
description: Obtient les informations sur la présentation dans le fichier spécifié.
type: docs
weight: 14
url: /fr/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) méthode


Obtient les informations sur la présentation dans le fichier spécifié.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) fichier. |

### Valeur de retour

[Presentation](../../presentation/) informations

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) méthode


Obtient les informations sur la présentation dans le flux spécifié.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) flux. |

### Valeur de retour

[Presentation](../../presentation/) informations.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPresentationInfo](../../ipresentationinfo/)
* Classe [String](../../../system/string/)
* Classe [IPresentationFactory](../)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)