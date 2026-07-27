---
title: InsertOleObjectFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado.
type: docs
weight: 196
url: /es/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) método


Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice base cero en el que se insertará el marco del objeto OLE. |
| x | **float** | La coordenada x del nuevo marco OLE, en puntos. |
| y | **float** | La coordenada y del nuevo marco OLE, en puntos. |
| width | **float** | El ancho del nuevo marco OLE, en puntos. |
| height | **float** | La altura del nuevo marco OLE, en puntos. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | La información de datos OLE incrustados ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Valor devuelto

El [IOleObjectFrame](../../ioleobjectframe/) recién creado.

## Observaciones



Este ejemplo demuestra la inserción de un objeto OLE en el segundo índice: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) método


Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice base cero en el que se insertará el marco del objeto OLE. |
| x | **float** | La coordenada x del nuevo marco OLE, en puntos. |
| y | **float** | La coordenada y del nuevo marco OLE, en puntos. |
| width | **float** | El ancho del nuevo marco OLE, en puntos. |
| height | **float** | La altura del nuevo marco OLE, en puntos. |
| className | [System::String](../../../system/string/) | El nombre de clase del objeto OLE. |
| path | [System::String](../../../system/string/) | La ruta al archivo vinculado. |

### Valor devuelto

El marco del objeto OLE recién creado.

## Observaciones



Esta ruta se almacena literalmente en la presentación. Si se especifica una ruta relativa, el archivo será inaccesible al abrir la presentación desde un directorio diferente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IOleObjectFrame](../../ioleobjectframe/)
* Clase [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Clase [ShapeCollection](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)