---
title: GetImage()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un objeto Image con escalado personalizado.
type: docs
weight: 105
url: /es/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) método

Devuelve un objeto Image con escalado personalizado.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleX | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje x. |
| scaleY | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje y. |

### Valor devuelto

objeto Image [IImage](../../iimage/)

## ISlide::GetImage() método

Devuelve un objeto Thumbnail Image (20% del tamaño real).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### Valor devuelto

objeto Image [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) método

Devuelve un objeto Image con el tamaño especificado.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamaño de la imagen a crear. |

### Valor devuelto

objeto Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) método

Devuelve un objeto Thumbnail tiff bitmap con los parámetros especificados.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Opciones Tiff. |

### Valor devuelto

objeto Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) método

Devuelve un objeto Thumbnail Bitmap.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |

### Valor devuelto

objeto Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) método

Devuelve un objeto Thumbnail Bitmap con escalado personalizado.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |
| scaleX | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje x. |
| scaleY | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje y. |

### Valor devuelto

objeto Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) método

Devuelve un objeto Thumbnail Bitmap con el tamaño especificado.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamaño de la imagen a crear. |

### Valor devuelto

objeto Image [IImage](../../iimage/)

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IImage](../../iimage/)
* Clase [ISlide](../)
* Clase [Size](../../../system.drawing/size/)
* Clase [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Clase [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)