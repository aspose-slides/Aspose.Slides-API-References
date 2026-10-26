---
title: GetImages()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve objetos Thumbnail Image para todas las diapositivas de una presentación.
type: docs
weight: 417
url: /es/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) método

Devuelve objetos Thumbnail Image para todas las diapositivas de una presentación.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |

### Valor de retorno

Objetos Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) método

Devuelve objetos Thumbnail Bitmap para las diapositivas especificadas de una presentación.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz con posiciones de diapositivas, comenzando desde 1. |

### Valor de retorno

Objetos Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) método

Devuelve objetos Thumbnail Image para todas las diapositivas de una presentación con escala personalizada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |
| scaleX | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje x. |
| scaleY | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje y. |

### Valor de retorno

Objetos Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) método

Devuelve objetos Thumbnail Image para las diapositivas especificadas de una presentación con escala personalizada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz con posiciones de diapositivas, comenzando desde 1. |
| scaleX | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje x. |
| scaleY | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje y. |

### Valor de retorno

Objetos Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) método

Devuelve objetos Thumbnail Image para todas las diapositivas de una presentación con el tamaño especificado.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamaño de la imagen a crear. |

### Valor de retorno

Objetos Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) método

Devuelve objetos Thumbnail Image para las diapositivas especificadas de una presentación con el tamaño especificado.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz con posiciones de diapositivas, comenzando desde 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamaño de la imagen a crear. |

### Valor de retorno

Objetos Bitmap.

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IImage](../../iimage/)
* Clase [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Clase [IPresentation](../)
* Clase [Size](../../../system.drawing/size/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)