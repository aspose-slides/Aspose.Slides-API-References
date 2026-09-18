---
title: set_geometry_paths method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/videoframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Atualiza a geometria da forma a partir de um array de [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([`GeometryShape.shape_type`](/slides/python-net/pt/aspose.slides/geometryshape/shape_type)) para [`ShapeType.CUSTOM`](/slides/python-net/pt/aspose.slides/shapetype/CUSTOM).


```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Array de caminhos de geometria |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nenhum caminho encontrado |
| **RuntimeError(Proxy error(ArgumentException))** | Caminho vazio |



### Veja Também
* classe [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath)
* classe [`VideoFrame`](/slides/python-net/pt/aspose.slides/videoframe)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)