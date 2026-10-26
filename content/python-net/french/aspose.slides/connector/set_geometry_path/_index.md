---
title: set_geometry_path method
second_title: Aspose.Slides pour Python via l'API de référence .NET
description: 
type: docs
url: /fr/aspose.slides/connector/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Met à jour la géométrie de la forme à partir de l'objet [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Modifie le type de la forme ([`GeometryShape.shape_type`](/slides/python-net/fr/aspose.slides/geometryshape/shape_type)) en [`ShapeType.CUSTOM`](/slides/python-net/fr/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath) | Chemin de géométrie |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Aucun chemin trouvé |
| **RuntimeError(Proxy error(ArgumentException))** | Chemin vide trouvé |

### Voir aussi
* classe [`Connector`](/slides/python-net/fr/aspose.slides/connector)
* classe [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)