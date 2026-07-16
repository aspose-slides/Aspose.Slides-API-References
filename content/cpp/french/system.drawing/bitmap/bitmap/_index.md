---
title: Bitmap()
second_title: Référence API Aspose.Slides pour C++
description: Construit un nouvel objet Bitmap à partir de l'image existante spécifiée.
type: docs
weight: 1
url: /fr/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) constructeur


Construit un nouvel objet [Bitmap](../) à partir de l'image existante spécifiée.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image existante à partir de laquelle créer l'image bitmap |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) constructeur


Construit un nouvel objet [Bitmap](../) à partir du flux spécifié.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Un flux contenant des données d'image |
| useIcm | **bool** | IGNORÉ |

## Bitmap::Bitmap(const String\&) constructeur


Construit un nouvel objet [Bitmap](../) à partir du fichier spécifié.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Le nom du fichier contenant les données d'image |

## Bitmap::Bitmap(const String\&, bool) constructeur


Construit un nouvel objet [Bitmap](../) à partir du fichier spécifié.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Le nom du fichier contenant les données d'image |
| useIcm | **bool** | IGNORÉ |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) constructeur


Construit un nouvel objet [Bitmap](../) qui représente une image bitmap avec la largeur, la hauteur, le format de pixel et les données de pixel spécifiés.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de l'image |
| height | int | La hauteur de l'image |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Le format de pixel de l'image |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) constructeur


Construit un nouvel objet [Bitmap](../) à partir de l'image existante spécifiée, redimensionnée à la taille indiquée.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image existante à partir de laquelle créer l'image bitmap |
| size | const [Size](../../size/)\& | La taille de la nouvelle image |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) constructeur


Construit un nouvel objet [Bitmap](../) à partir de l'image existante spécifiée avec la largeur et la hauteur redimensionnées aux valeurs indiquées.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image existante à partir de laquelle créer l'image bitmap |
| width | int | Largeur de la nouvelle image |
| height | int | Hauteur de la nouvelle image |

## Voir aussi

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Image](../../image/)
* Classe [Bitmap](../)
* Classe [Stream](../../../system.io/stream/)
* Classe [String](../../../system/string/)
* Classe [Size](../../size/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)