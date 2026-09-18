---
title: set_geometry_path method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Updates shape geometry from [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath) object. Coordinates must be relative to the left
top corner of the shape.
Changes the type of the shape ([`IGeometryShape.shape_type`](/slides/python-net/pt/aspose.slides/igeometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/pt/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath) | Geometry path |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nenhum caminho encontrado |
| **RuntimeError(Proxy error(ArgumentException))** | Caminho vazio encontrado |

### Veja Também
* classe [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath)
* classe [`IGeometryShape`](/slides/python-net/pt/aspose.slides/igeometryshape)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)