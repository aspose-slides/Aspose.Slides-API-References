---
title: AddImage()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une image à une présentation.
type: docs
weight: 14
url: /fr/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) méthode


Ajoute une image à une présentation.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Image à ajouter. |

### Valeur de retour

Image ajoutée.

## Remarques


Cette méthode convertit les fichiers WMF/EMF en image PNG raster avant de les insérer dans une présentation.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) méthode


Ajoute une image à partir d'un flux mémoire.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Flux mémoire. |

### Valeur de retour

Image ajoutée.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) méthode


Ajoute une image à une présentation depuis un flux.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux depuis lequel ajouter l'image. |

### Valeur de retour

Image ajoutée.

## Remarques


Cette méthode peut ajouter des fichiers WMF/EMF à une présentation sans les convertir en image PNG raster.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) méthode


Crée et ajoute une image à une présentation depuis un flux.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux depuis lequel ajouter le fichier image. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Le comportement qui sera appliqué au flux. |

### Valeur de retour

Ajouté [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) méthode


Ajoute une image à une présentation depuis le tampon spécifié.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tampon. |

### Valeur de retour

Image ajoutée.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) méthode


Ajoute une copie d'une image d'une autre présentation.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Image source. |

### Valeur de retour

Image ajoutée.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) méthode


Ajoute une image à une présentation depuis un objet SVG.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Objet image SVG [ISvgImage](../../isvgimage/) |

### Valeur de retour

Image ajoutée.

## See Also

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [IImage](../../iimage/)
* Class [IImageCollection](../)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)