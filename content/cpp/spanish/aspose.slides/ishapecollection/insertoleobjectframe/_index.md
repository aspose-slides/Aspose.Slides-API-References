---
title: InsertOleObjectFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado.
type: docs
weight: 79
url: /es/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) método


Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se insertará el marco de objeto OLE. |
| x | **float** | La coordenada x del nuevo marco OLE, en puntos. |
| y | **float** | La coordenada y del nuevo marco OLE, en puntos. |
| width | **float** | El ancho del nuevo marco OLE, en puntos. |
| height | **float** | La altura del nuevo marco OLE, en puntos. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | La información de datos OLE incrustada ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Valor devuelto

El [IOleObjectFrame](../../ioleobjectframe/) recién creado.

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) método


Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se insertará el marco de objeto OLE. |
| x | **float** | La coordenada x del nuevo marco OLE, en puntos. |
| y | **float** | La coordenada y del nuevo marco OLE, en puntos. |
| width | **float** | El ancho del nuevo marco OLE, en puntos. |
| height | **float** | La altura del nuevo marco OLE, en puntos. |
| className | [System::String](../../../system/string/) | El nombre de clase del objeto OLE. |
| path | [System::String](../../../system/string/) | La ruta al archivo enlazado. |

### Valor devuelto

El [IOleObjectFrame](../../ioleobjectframe/) recién creado.

## Observaciones



Esta ruta se almacena literalmente en la presentación. Si se especifica una ruta relativa, el archivo será inaccesible al abrir la presentación desde un directorio diferente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IOleObjectFrame](../../ioleobjectframe/)
* Clase [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Clase [IShapeCollection](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)