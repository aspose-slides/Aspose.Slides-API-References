---
title: set_geometry_paths method
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/geometryshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Met à jour la géométrie de la forme à partir d'un tableau de [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath). Les coordonnées doivent être relatives au
             coin supérieur gauche de la forme.
             Modifie le type de la forme ([`GeometryShape.shape_type`](/slides/python-net/fr/aspose.slides/geometryshape/shape_type)) en [`ShapeType.CUSTOM`](/slides/python-net/fr/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Tableau de chemins géométriques |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Chemin non trouvé |
| **RuntimeError(Proxy error(ArgumentException))** | Chemin vide |

### Voir aussi
* classe [`GeometryShape`](/slides/python-net/fr/aspose.slides/geometryshape)
* classe [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)