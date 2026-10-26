---
title: AddAudioFrameLinked()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo agrega al final de la colección de formas.
type: docs
weight: 261
url: /es/aspose.slides/shapecollection/addaudioframelinked/
---
## ShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) método

Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo agrega al final de la colección de formas.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo marco de audio, en puntos. |
| y | **float** | La coordenada y del nuevo marco de audio, en puntos. |
| width | **float** | El ancho del nuevo marco de audio, en puntos. |
| height | **float** | La altura del nuevo marco de audio, en puntos. |
| fname | [System::String](../../../system/string/) | La ruta o nombre del archivo de audio externo a enlazar. |

### Valor devuelto

El [IAudioFrame](../../iaudioframe/) recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)