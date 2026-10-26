---
title: GetImages()
second_title: Aspose.Slides for C++ API referencia
description: Visszaad Image objektumokat a prezentáció minden diájához.
type: docs
weight: 456
url: /hu/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) method


Visszaad Image objektumokat az összes dia számára a prezentációban.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff beállítások. |

### Visszatérési érték

Image objektumok.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) method


Visszaad Thumbnail Image objektumokat a megadott diák számára a prezentációban.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff beállítások. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tömb a dia pozíciókkal, 1-től kezdve. |

### Visszatérési érték

Image objektumok.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method


Visszaad Thumbnail Image objektumokat az összes dia számára a prezentációban egyedi méretezéssel.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff beállítások. |
| scaleX | **float** | Az az érték, amellyel ezt a Thumbnail-et az x-tengely irányában méretezi. |
| scaleY | **float** | Az az érték, amellyel ezt a Thumbnail-et az y-tengely irányában méretezi. |

### Visszatérési érték

Image objektumok.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) method


Visszaad Thumbnail Image objektumokat a megadott diák számára a prezentációban egyedi méretezéssel.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff beállítások. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tömb a dia pozíciókkal, 1-től kezdve. |
| scaleX | **float** | Az az érték, amellyel ezt a Thumbnail-et az x-tengely irányában méretezi. |
| scaleY | **float** | Az az érték, amellyel ezt a Thumbnail-et az y-tengely irányában méretezi. |

### Visszatérési érték

Image objektumok.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method


Visszaad Thumbnail Image objektumokat az összes dia számára a prezentációban a megadott mérettel.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff beállítások. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Az elkészítendő kép mérete. |

### Visszatérési érték

Image objektumok.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) method


Visszaad Thumbnail Image objektumokat a megadott diák számára a prezentációban a megadott mérettel.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff beállítások. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Tömb a dia pozíciókkal, 1-től kezdve. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Az elkészítendő kép mérete. |

### Visszatérési érték

Image objektumok.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IImage](../../iimage/)
* Osztály [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Osztály [Presentation](../)
* Osztály [Size](../../../system.drawing/size/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)