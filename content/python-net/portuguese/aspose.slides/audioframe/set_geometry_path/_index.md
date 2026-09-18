---
title: set_geometry_path method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/audioframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Atualiza a geometria da forma a partir do objeto [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto esquerdo
             superior da forma.
             Altera o tipo da forma ([`GeometryShape.shape_type`](/slides/python-net/pt/aspose.slides/geometryshape/shape_type)) para [`ShapeType.CUSTOM`](/slides/python-net/pt/aspose.slides/shapetype/CUSTOM).

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
* classe [`AudioFrame`](/slides/python-net/pt/aspose.slides/audioframe)
* classe [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)