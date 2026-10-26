---
title: GetImages()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve objetos Image para todas las diapositivas de una presentación.
type: docs
weight: 456
url: /es/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) method

Devuelve objetos Image para todas las diapositivas de una presentación.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff options. |

### Valor devuelto

Objetos Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) method

Devuelve objetos Image en miniatura para diapositivas específicas de una presentación.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz con posiciones de diapositivas, comenzando desde 1. |

### Valor devuelto

Objetos Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method

Devuelve objetos Image en miniatura para todas las diapositivas de una presentación con escalado personalizado.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff options. |
| scaleX | **float** | El valor por el que escalar esta miniatura en la dirección del eje x. |
| scaleY | **float** | El valor por el que escalar esta miniatura en la dirección del eje y. |

### Valor devuelto

Objetos Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) method

Devuelve objetos Image en miniatura para diapositivas específicas de una presentación con escalado personalizado.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz con posiciones de diapositivas, comenzando desde 1. |
| scaleX | **float** | El valor por el que escalar esta miniatura en la dirección del eje x. |
| scaleY | **float** | El valor por el que escalar esta miniatura en la dirección del eje y. |

### Valor devuelto

Objetos Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method

Devuelve objetos Image en miniatura para todas las diapositivas de una presentación con el tamaño especificado.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff options. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamaño de la imagen a crear. |

### Valor devuelto

Objetos Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) method

Devuelve objetos Image en miniatura para diapositivas específicas de una presentación con el tamaño especificado.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Matriz con posiciones de diapositivas, comenzando desde 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamaño de la imagen a crear. |

### Valor devuelto

Objetos Image.

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IImage](../../iimage/)
* Clase [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Clase [Presentation](../)
* Clase [Size](../../../system.drawing/size/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)