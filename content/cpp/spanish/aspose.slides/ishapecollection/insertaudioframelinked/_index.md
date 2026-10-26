---
title: InsertAudioFrameLinked()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo inserta en la colección de formas en el índice especificado.
type: docs
weight: 235
url: /es/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) method


Crea un nuevo marco de audio vinculado a un archivo de audio externo e lo inserta en la colección de formas en el índice especificado.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se insertará el marco de audio. |
| x | **float** | La coordenada x del nuevo marco de audio, en puntos. |
| y | **float** | La coordenada y del nuevo marco de audio, en puntos. |
| width | **float** | El ancho del nuevo marco de audio, en puntos. |
| height | **float** | La altura del nuevo marco de audio, en puntos. |
| fname | [System::String](../../../system/string/) | La ruta o nombre del archivo de audio externo a vincular. |

### Valor devuelto

El [IAudioFrame](../../iaudioframe/) recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAudioFrame](../../iaudioframe/)
* Clase [String](../../../system/string/)
* Clase [IShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)