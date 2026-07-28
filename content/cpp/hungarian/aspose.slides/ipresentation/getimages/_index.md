---
title: GetImages()
second_title: Aspose.Slides C++ API referencia
description: Visszaad miniaturakép objektumokat a bemutató összes diájához.
type: docs
weight: 417
url: /hu/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) metódus


Visszaad Thumbnail Image objektumokat a bemutató összes diájához.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |

### Visszatérési érték

Bitmap objektumok.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) metódus


Visszaad Thumbnail Bitmap objektumokat a bemutató meghatározott diáihoz.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |

### Visszatérési érték

Bitmap objektumok.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metódus


Visszaad Thumbnail Image objektumokat a bemutató összes diájához egyéni méretezéssel.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| scaleX | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | **float** | The value by which to scale this Thumbnail in the y-axis direction. |

### Visszatérési érték

Bitmap objektumok.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) metódus


Visszaad Thumbnail Image objektumokat a bemutató meghatározott diáihoz egyéni méretezéssel.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| scaleX | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | **float** | The value by which to scale this Thumbnail in the y-axis direction. |

### Visszatérési érték

Bitmap objektumok.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metódus


Visszaad Thumbnail Image objektumokat a bemutató összes diájához a megadott mérettel.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Size of the image to create. |

### Visszatérési érték

Bitmap objektumok.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) metódus


Visszaad Thumbnail Image objektumokat a bemutató meghatározott diáihoz a megadott mérettel.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Size of the image to create. |

### Visszatérési érték

Bitmap objektumok.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IImage](../../iimage/)
* Osztály [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Osztály [IPresentation](../)
* Osztály [Size](../../../system.drawing/size/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)