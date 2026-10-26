---
title: set_geometry_path method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/connector/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή
             άνω γωνία του σχήματος.
             Αλλάζει τον τύπο του σ_shape ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath) | Διαδρομή γεωμετρίας |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Δε βρέθηκε διαδρομή |
| **RuntimeError(Proxy error(ArgumentException))** | Βρέθηκε κενή διαδρομή |

### Δείτε επίσης
* κλάση [`Connector`](/slides/python-net/el/aspose.slides/connector)
* κλάση [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)