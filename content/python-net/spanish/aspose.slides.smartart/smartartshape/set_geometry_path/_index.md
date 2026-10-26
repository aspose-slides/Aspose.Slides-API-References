---
title: set_geometry_path method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.smartart/smartartshape/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Actualiza la geometría de la forma a partir del objeto [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma.
             Cambia el tipo de la forma ([`GeometryShape.shape_type`](/slides/python-net/es/aspose.slides/geometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/es/aspose.slides/shapetype/CUSTOM).


```python
def set_geometry_path(self, geometry_path):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath) | Ruta de geometría |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | No se encontró una ruta |
| **RuntimeError(Proxy error(ArgumentException))** | Se encontró una ruta vacía |



### Ver también
* clase [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath)
* clase [`SmartArtShape`](/slides/python-net/es/aspose.slides.smartart/smartartshape)
* módulo [`aspose.slides.smartart`](/slides/python-net/es/aspose.slides.smartart)
* biblioteca [`Aspose.Slides`](/slides/python-net)