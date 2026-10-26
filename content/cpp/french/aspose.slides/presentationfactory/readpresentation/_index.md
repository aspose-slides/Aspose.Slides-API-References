---
title: ReadPresentation()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit une présentation existante à partir d'un tableau
type: docs
weight: 40
url: /fr/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) méthode


Lit une présentation existante à partir d'un tableau

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tableau à lire |

### Valeur de retour

Présentation lue

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) méthode


Lit une présentation existante à partir d'un tableau avec des options de chargement supplémentaires

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tableau à lire |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Options de chargement |

### Valeur de retour

Présentation lue

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) méthode


Lit une présentation existante à partir d'un flux

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux d'entrée à lire |

### Valeur de retour

Présentation lue

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) méthode


Lit une présentation existante à partir d'un flux avec des options de chargement supplémentaires

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux d'entrée à lire |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Options de chargement |

### Valeur de retour

Présentation lue

## PresentationFactory::ReadPresentation(System::String) méthode


Lit une présentation existante à partir d'un fichier

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nom du fichier |

### Valeur de retour

Présentation lue

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) méthode


Lit une présentation existante à partir d'un fichier avec des options de chargement supplémentaires

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nom du fichier |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Options de chargement |

### Valeur de retour

Présentation lue

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IPresentation](../../ipresentation/)
* Classe [PresentationFactory](../)
* Classe [ILoadOptions](../../iloadoptions/)
* Classe [Stream](../../../system.io/stream/)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)