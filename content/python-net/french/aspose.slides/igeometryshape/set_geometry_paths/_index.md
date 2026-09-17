---
title: set_geometry_paths method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/igeometryshape/set_geometry_paths/
weight: 80
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Met à jour la géométrie de la forme à partir d'un tableau de [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur
             gauche de la forme.
             Modifie le type de la forme ([`IGeometryShape.shape_type`](/slides/python-net/fr/aspose.slides/igeometryshape/shape_type)) en [`ShapeType.CUSTOM`](/slides/python-net/fr/aspose.slides/shapetype/CUSTOM).


```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Array geometry paths |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | No path found |
| **RuntimeError(Proxy error(ArgumentException))** | Empty path |



### Voir aussi
* classe [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath)
* classe [`IGeometryShape`](/slides/python-net/fr/aspose.slides/igeometryshape)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)