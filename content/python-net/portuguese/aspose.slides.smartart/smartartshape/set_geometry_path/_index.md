---
title: set_geometry_path method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.smartart/smartartshape/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Atualiza a geometria da forma a partir do objeto [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma.
             Altera o tipo da forma ([`GeometryShape.shape_type`](/slides/python-net/pt/aspose.slides/geometryshape/shape_type)) para [`ShapeType.CUSTOM`](/slides/python-net/pt/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath) | Caminho da geometria |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nenhum caminho encontrado |
| **RuntimeError(Proxy error(ArgumentException))** | Caminho vazio encontrado |

### Veja Também
* classe [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath)
* classe [`SmartArtShape`](/slides/python-net/pt/aspose.slides.smartart/smartartshape)
* módulo [`aspose.slides.smartart`](/slides/python-net/pt/aspose.slides.smartart)
* biblioteca [`Aspose.Slides`](/slides/python-net)