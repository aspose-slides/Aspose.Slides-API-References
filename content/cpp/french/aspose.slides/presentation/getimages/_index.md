---
title: GetImages()
second_title: Référence de l'API C++ Aspose.Slides
description: Renvoie des objets Image pour toutes les diapositives d'une présentation.
type: docs
weight: 456
url: /fr/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) méthode

Renvoie des objets Image pour toutes les diapositives d'une présentation.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Options Tiff. |

### Valeur de retour

Objets Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) méthode


Renvoie des objets Image miniature pour les diapositives spécifiées d'une présentation.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Options Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tableau contenant les positions des diapositives, en commençant à 1. |

### Valeur de retour

Objets Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) méthode


Renvoie des objets Image miniature pour toutes les diapositives d'une présentation avec un redimensionnement personnalisé.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Options Tiff. |
| scaleX | **float** | Valeur par laquelle mettre à l'échelle cette miniature le long de l'axe x. |
| scaleY | **float** | Valeur par laquelle mettre à l'échelle cette miniature le long de l'axe y. |

### Valeur de retour

Objets Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) méthode


Renvoie des objets Image miniature pour les diapositives spécifiées d'une présentation avec un redimensionnement personnalisé.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Options Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tableau contenant les positions des diapositives, en commençant à 1. |
| scaleX | **float** | Valeur par laquelle mettre à l'échelle cette miniature le long de l'axe x. |
| scaleY | **float** | Valeur par laquelle mettre à l'échelle cette miniature le long de l'axe y. |

### Valeur de retour

Objets Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) méthode


Renvoie des objets Image miniature pour toutes les diapositives d'une présentation avec une taille spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Options Tiff. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Taille de l'image à créer. |

### Valeur de retour

Objets Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) méthode


Renvoie des objets Image miniature pour les diapositives spécifiées d'une présentation avec une taille spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Options Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tableau contenant les positions des diapositives, en commençant à 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Taille de l'image à créer. |

### Valeur de retour

Objets Image.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [Presentation](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)