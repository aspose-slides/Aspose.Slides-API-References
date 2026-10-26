---
title: AddVideoFrame()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un nuevo marco de video y lo agrega al final de la colección de formas.
type: docs
weight: 170
url: /es/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) método


Crea un nuevo marco de video y lo agrega al final de la colección de formas.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo marco de video, en puntos. |
| y | **float** | La coordenada y del nuevo marco de video, en puntos. |
| width | **float** | El ancho del nuevo marco de video, en puntos. |
| height | **float** | La altura del nuevo marco de video, en puntos. |
| fname | [System::String](../../../system/string/) | La ruta o el nombre del archivo de video que se va a incrustar. |

### Valor de retorno

El [IVideoFrame](../../ivideoframe/) recién creado.

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) método


Crea un nuevo marco de video y lo agrega al final de la colección de formas.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo marco de video, en puntos. |
| y | **float** | La coordenada y del nuevo marco de video, en puntos. |
| width | **float** | El ancho del nuevo marco de video, en puntos. |
| height | **float** | La altura del nuevo marco de video, en puntos. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | El [IVideo](../../ivideo/) que se incrusta en el marco de video. |

### Valor de retorno

El [IVideoFrame](../../ivideoframe/) recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IVideoFrame](../../ivideoframe/)
* Clase [String](../../../system/string/)
* Clase [IShapeCollection](../)
* Clase [IVideo](../../ivideo/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)