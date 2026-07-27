---
title: GetImage()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un objeto de imagen con escalado personalizado.
type: docs
weight: 105
url: /es/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) method

Devuelve un objeto de imagen con escalado personalizado.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleX | **float** | El valor por el cual escalar esta Miniatura en la dirección del eje x. |
| scaleY | **float** | El valor por el cual escalar esta Miniatura en la dirección del eje y. |

### Valor devuelto

Objeto Image [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() method

Devuelve un objeto de imagen Miniatura (20 % del tamaño real).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### Valor devuelto

Objeto Image [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) method

Devuelve un objeto de imagen con el tamaño especificado.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamaño de la imagen a crear. |

### Valor devuelto

Objeto Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) method

Devuelve un objeto bitmap tiff Miniatura con los parámetros especificados.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Opciones tiff. |

### Valor devuelto

Objeto Image.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) method

Devuelve un objeto Bitmap Miniatura.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |

### Valor devuelto

Objetos Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method

Devuelve un objeto Bitmap Miniatura con escalado personalizado.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |
| scaleX | **float** | El valor por el cual escalar esta Miniatura en la dirección del eje x. |
| scaleY | **float** | El valor por el cual escalar esta Miniatura en la dirección del eje y. |

### Valor devuelto

Objetos Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method

Devuelve un objeto Bitmap Miniatura con el tamaño especificado.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamaño de la imagen a crear. |

### Valor devuelto

Objetos Bitmap.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [ISlide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)