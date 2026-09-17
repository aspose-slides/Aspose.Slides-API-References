---
title: set_geometry_paths method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/audioframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Actualiza la geometría de la forma a partir de una matriz de [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la izquierda
             esquina superior de la forma.
             Cambia el tipo de la forma ([`GeometryShape.shape_type`](/slides/python-net/es/aspose.slides/geometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/es/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Matriz de rutas de geometría |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | No se encontró la ruta |
| **RuntimeError(Proxy error(ArgumentException))** | Ruta vacía |

### Ver también
* clase [`AudioFrame`](/slides/python-net/es/aspose.slides/audioframe)
* clase [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)