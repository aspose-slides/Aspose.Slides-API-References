---
title: GetImage()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un objet image avec un redimensionnement personnalisé.
type: docs
weight: 105
url: /fr/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) méthode


Renvoie un objet image avec un redimensionnement personnalisé.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| scaleX | **float** | La valeur par laquelle redimensionner cette miniature selon l'axe x. |
| scaleY | **float** | La valeur par laquelle redimensionner cette miniature selon l'axe y. |

### Valeur de retour

Objet Image [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() méthode


Renvoie un objet Image miniature (20 % de la taille réelle).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### Valeur de retour

Objet Image [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) méthode


Renvoie un objet image avec la taille spécifiée.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Taille de l'image à créer. |

### Valeur de retour

Objet Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) méthode


Renvoie un objet bitmap TIFF miniature avec les paramètres spécifiés.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Options TIFF. |

### Valeur de retour

Objet Image.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) méthode


Renvoie un objet Bitmap miniature.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Options de rendu. |

### Valeur de retour

Objets Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) méthode


Renvoie un objet Bitmap miniature avec un redimensionnement personnalisé.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Options de rendu. |
| scaleX | **float** | La valeur par laquelle redimensionner cette miniature selon l'axe x. |
| scaleY | **float** | La valeur par laquelle redimensionner cette miniature selon l'axe y. |

### Valeur de retour

Objets Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) méthode


Renvoie un objet Bitmap miniature avec la taille spécifiée.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Options de rendu. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Taille de l'image à créer. |

### Valeur de retour

Objets Bitmap.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../iimage/)
* Classe [ISlide](../)
* Classe [Size](../../../system.drawing/size/)
* Classe [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Classe [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)