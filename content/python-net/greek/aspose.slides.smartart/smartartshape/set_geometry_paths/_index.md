---
title: set_geometry_paths method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.smartart/smartartshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Ενημερώνει τη γεωμετρία του σχήματος από έναν πίνακα του [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή επάνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Διαδρομές γεωμετρίας |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Δεν βρέθηκε διαδρομή |
| **RuntimeError(Proxy error(ArgumentException))** | Κενή διαδρομή |

### Δείτε επίσης
* κλάση [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath)
* κλάση [`SmartArtShape`](/slides/python-net/el/aspose.slides.smartart/smartartshape)
* μονάδα [`aspose.slides.smartart`](/slides/python-net/el/aspose.slides.smartart)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)