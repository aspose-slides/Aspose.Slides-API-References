---
title: InsertAudioFrameLinked()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo marco de audio vinculado a un archivo de audio externo e lo inserta en la colección de formas en el índice especificado.
type: docs
weight: 274
url: /es/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) método

Crea un nuevo marco de audio vinculado a un archivo de audio externo e lo inserta en la colección de formas en el índice especificado.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice base cero en el que se inserta el marco de audio. |
| x | **float** | La coordenada X del nuevo marco de audio, en puntos. |
| y | **float** | La coordenada Y del nuevo marco de audio, en puntos. |
| width | **float** | El ancho del nuevo marco de audio, en puntos. |
| height | **float** | La altura del nuevo marco de audio, en puntos. |
| fname | [System::String](../../../system/string/) | La ruta o el nombre del archivo de audio externo a vincular. |

### Valor devuelto

El [IAudioFrame](../../iaudioframe/) recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAudioFrame](../../iaudioframe/)
* Clase [String](../../../system/string/)
* Clase [ShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)