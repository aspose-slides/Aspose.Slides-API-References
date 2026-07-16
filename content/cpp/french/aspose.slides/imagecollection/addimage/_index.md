---
title: AddImage()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une copie d'une image d'une autre présentation.
type: docs
weight: 53
url: /fr/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) méthode

Ajoute une copie d'une image d'une autre présentation.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Image source. |

### Valeur de retour

Image ajoutée.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) méthode

Ajoute une image à une présentation.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Image à ajouter. |

### Valeur de retour

Image ajoutée.

## Remarques

Cette méthode convertit les métafichiers WMF/EMF en image PNG raster avant de les insérer dans une présentation.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) méthode

Ajoute une image à une présentation depuis un flux.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Flux d'où provient l'image à ajouter. |

### Valeur de retour

Image ajoutée.

## Remarques

Cette méthode peut ajouter des métafichiers WMF/EMF à une présentation sans les convertir en image PNG raster.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) méthode

Ajoute une image à une présentation depuis un flux.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux d'où provient l'image à ajouter. |

### Valeur de retour

Image ajoutée.

## Remarques

Cette méthode peut ajouter des métafichiers WMF/EMF à une présentation sans les convertir en image PNG raster.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) méthode

Crée et ajoute une image à une présentation depuis un flux.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux d'où provient le fichier image à ajouter. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Le comportement qui sera appliqué au flux. |

### Valeur de retour

Ajouté [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) méthode

Ajoute une image à une présentation depuis le tampon spécifié.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tampon. |

### Valeur de retour

Image ajoutée.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) méthode

Ajoute une image à une présentation depuis un objet Svg.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Objet d'image Svg [ISvgImage](../../isvgimage/) |

### Valeur de retour

Image ajoutée.

## Voir aussi

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [ImageCollection](../)
* Class [IImage](../../iimage/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)