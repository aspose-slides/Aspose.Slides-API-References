---
title: InsertVideoFrame()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un nuevo marco de video y lo inserta en la colección de formas en el índice especificado.
type: docs
weight: 183
url: /es/aspose.slides/ishapecollection/insertvideoframe/
---
## IShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) método

Crea un nuevo marco de video y lo inserta en la colección de formas en el índice especificado.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que insertar el marco de video. |
| x | **float** | La coordenada x del nuevo marco de video, en puntos. |
| y | **float** | La coordenada y del nuevo marco de video, en puntos. |
| width | **float** | El ancho del nuevo marco de video, en puntos. |
| height | **float** | La altura del nuevo marco de video, en puntos. |
| fname | [System::String](../../../system/string/) | La ruta o nombre del archivo de video a incrustar. |

### Valor devuelto

El [IVideoFrame](../../ivideoframe/) recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IVideoFrame](../../ivideoframe/)
* Clase [String](../../../system/string/)
* Clase [IShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)