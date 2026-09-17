---
title: insert_ole_object_frame method
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado.

### Devuelve

El [`IOleObjectFrame`](/slides/python-net/es/aspose.slides/ioleobjectframe) recién creado.



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que insertar el marco de objeto OLE. |
| x | **float** | La coordenada x del nuevo marco OLE, en puntos. |
| y | **float** | La coordenada y del nuevo marco OLE, en puntos. |
| width | **float** | El ancho del nuevo marco OLE, en puntos. |
| height | **float** | La altura del nuevo marco OLE, en puntos. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/es/aspose.slides/ioleembeddeddatainfo) | La información de datos OLE incrustada ([`IOleEmbeddedDataInfo`](/slides/python-net/es/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado.

### Devuelve

El [`IOleObjectFrame`](/slides/python-net/es/aspose.slides/ioleobjectframe) recién creado.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que insertar el marco de objeto OLE. |
| x | **float** | La coordenada x del nuevo marco OLE, en puntos. |
| y | **float** | La coordenada y del nuevo marco OLE, en puntos. |
| width | **float** | El ancho del nuevo marco OLE, en puntos. |
| height | **float** | La altura del nuevo marco OLE, en puntos. |
| class_name | **str** | El nombre de clase del objeto OLE. |
| path | **str** | La ruta al archivo vinculado. <br/><br/>Esta ruta se almacena literalmente en la presentación.<br/><br/>            Si se especifica una ruta relativa, el archivo será inaccesible al abrir<br/><br/>            la presentación desde un directorio diferente. |



### Ver también
* clase [`IOleEmbeddedDataInfo`](/slides/python-net/es/aspose.slides/ioleembeddeddatainfo)
* clase [`IOleObjectFrame`](/slides/python-net/es/aspose.slides/ioleobjectframe)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)