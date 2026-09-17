---
title: set_geometry_paths method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/igeometryshape/set_geometry_paths/
weight: 80
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Actualiza la geometría de la forma a partir de una matriz de [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([`IGeometryShape.shape_type`](/slides/python-net/es/aspose.slides/igeometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/es/aspose.slides/shapetype/CUSTOM).

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
| **RuntimeError(Proxy error(ArgumentException))** | No se encontró ruta |
| **RuntimeError(Proxy error(ArgumentException))** | Ruta vacía |

### Véase también
* clase [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath)
* clase [`IGeometryShape`](/slides/python-net/es/aspose.slides/igeometryshape)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)