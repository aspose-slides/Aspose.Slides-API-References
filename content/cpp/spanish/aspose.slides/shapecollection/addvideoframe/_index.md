---
title: AddVideoFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo fotograma de vídeo y lo agrega al final de la colección de formas.
type: docs
weight: 209
url: /es/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) método

Crea un nuevo fotograma de vídeo y lo agrega al final de la colección de formas.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo fotograma de vídeo, en puntos. |
| y | **float** | La coordenada y del nuevo fotograma de vídeo, en puntos. |
| width | **float** | El ancho del nuevo fotograma de vídeo, en puntos. |
| height | **float** | La altura del nuevo fotograma de vídeo, en puntos. |
| fname | [System::String](../../../system/string/) | La ruta o el nombre del archivo de vídeo a incrustar. |

### Valor devuelto

El [IVideoFrame](../../ivideoframe/) recién creado.

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) método

Crea un nuevo fotograma de vídeo y lo agrega al final de la colección de formas.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo fotograma de vídeo, en puntos. |
| y | **float** | La coordenada y del nuevo fotograma de vídeo, en puntos. |
| width | **float** | El ancho del nuevo fotograma de vídeo, en puntos. |
| height | **float** | La altura del nuevo fotograma de vídeo, en puntos. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | El [IVideo](../../ivideo/) para incrustar en el fotograma de vídeo. |

### Valor devuelto

El [IVideoFrame](../../ivideoframe/) recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IVideoFrame](../../ivideoframe/)
* Clase [String](../../../system/string/)
* Clase [ShapeCollection](../)
* Clase [IVideo](../../ivideo/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)