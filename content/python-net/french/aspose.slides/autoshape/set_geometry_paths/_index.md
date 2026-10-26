---
title: set_geometry_paths method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/autoshape/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Met à jour la géométrie de la forme à partir d'un tableau de [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Modifie le type de la forme ([`GeometryShape.shape_type`](/slides/python-net/fr/aspose.slides/geometryshape/shape_type)) en [`ShapeType.CUSTOM`](/slides/python-net/fr/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Tableau de chemins de géométrie |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Aucun chemin trouvé |
| **RuntimeError(Proxy error(ArgumentException))** | Chemin vide |

### Voir aussi
* classe [`AutoShape`](/slides/python-net/fr/aspose.slides/autoshape)
* classe [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)