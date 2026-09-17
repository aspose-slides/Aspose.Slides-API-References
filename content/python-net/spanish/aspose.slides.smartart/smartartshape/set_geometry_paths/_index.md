---
title: set_geometry_paths method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.smartart/smartartshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Actualiza la geometría de la forma a partir de una matriz de [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([`GeometryShape.shape_type`](/slides/python-net/es/aspose.slides/geometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/es/aspose.slides/shapetype/CUSTOM).

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
* clase [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath)
* clase [`SmartArtShape`](/slides/python-net/es/aspose.slides.smartart/smartartshape)
* módulo [`aspose.slides.smartart`](/slides/python-net/es/aspose.slides.smartart)
* biblioteca [`Aspose.Slides`](/slides/python-net)