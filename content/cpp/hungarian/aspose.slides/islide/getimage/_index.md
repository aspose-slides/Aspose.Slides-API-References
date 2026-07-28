---
title: GetImage()
second_title: Aspose.Slides C++ API-referencia
description: Visszaad egy képobjektumot egyéni méretezéssel.
type: docs
weight: 105
url: /hu/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) módszer


Visszaad egy képobjektumot egyéni méretezéssel.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scaleX | **float** | Az érték, amellyel a bélyegképet az x tengely mentén méretezi. |
| scaleY | **float** | Az érték, amellyel a bélyegképet az y tengely mentén méretezi. |

### Visszatérési érték

Képobjektum [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() módszer


Visszaad egy bélyegkép képtárgyat (a valós méret 20%-a).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### Visszatérési érték

Képobjektum [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) módszer


Visszaad egy képobjektumot megadott mérettel.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | A létrehozandó kép mérete. |

### Visszatérési érték

Bitmap objektum.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) módszer


Visszaad egy bélyegkép tiff bitmap objektumot megadott paraméterekkel.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff beállítások. |

### Visszatérési érték

Képobjektum.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) módszer


Visszaad egy bélyegkép bitmap objektumot.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderelési beállítások. |

### Visszatérési érték

Bitmap objektumok.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) módszer


Visszaad egy bélyegkép bitmap objektumot egyéni méretezéssel.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderelési beállítások. |
| scaleX | **float** | Az érték, amellyel a bélyegképet az x tengely mentén méretezi. |
| scaleY | **float** | Az érték, amellyel a bélyegképet az y tengely mentén méretezi. |

### Visszatérési érték

Bitmap objektumok.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) módszer


Visszaad egy bélyegkép bitmap objektumot megadott mérettel.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderelési beállítások. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | A létrehozandó kép mérete. |

### Visszatérési érték

Bitmap objektumok.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IImage](../../iimage/)
* Osztály [ISlide](../)
* Osztály [Size](../../../system.drawing/size/)
* Osztály [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Osztály [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)