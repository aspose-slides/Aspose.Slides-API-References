---
title: ReadPresentation()
second_title: Référence de l'API Aspose.Slides for C++
description: Lit une présentation existante à partir d'un tableau
type: docs
weight: 27
url: /fr/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) méthode

Lit une présentation existante à partir d'un tableau

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tableau à lire |

### Valeur de retour

Lecture de la présentation

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) méthode

Lit une présentation existante à partir d'un tableau avec des options de chargement supplémentaires

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tableau à lire |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Options de chargement |

### Valeur de retour

Lecture de la présentation

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) méthode

Lit une présentation existante à partir d'un flux

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux d'entrée à lire |

### Valeur de retour

Lecture de la présentation

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) méthode

Lit une présentation existante à partir d'un flux avec des options de chargement supplémentaires

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux d'entrée à lire |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Options de chargement |

### Valeur de retour

Lecture de la présentation

## IPresentationFactory::ReadPresentation(System::String) méthode

Lit une présentation existante à partir d'un fichier

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nom du fichier |

### Valeur de retour

Lecture de la présentation

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) méthode

Lit une présentation existante à partir d'un fichier avec des options de chargement supplémentaires

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nom du fichier |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Options de chargement |

### Valeur de retour

Lecture de la présentation

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IPresentation](../../ipresentation/)
* Classe [IPresentationFactory](../)
* Classe [ILoadOptions](../../iloadoptions/)
* Classe [Stream](../../../system.io/stream/)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)