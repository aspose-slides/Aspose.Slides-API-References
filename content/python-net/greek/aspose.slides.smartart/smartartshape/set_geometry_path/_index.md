---
title: set_geometry_path method
second_title: Aspose.Slides για Python μέσω .NET αναφορά API
description: 
type: docs
url: /el/aspose.slides.smartart/smartartshape/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή επάνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([`GeometryShape.shape_type`](/slides/python-net/el/aspose.slides/geometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM).

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
| **RuntimeError(Proxy error(ArgumentException))** | Δεν βρέθηκε διαδρομή |
| **RuntimeError(Proxy error(ArgumentException))** | Βρέθηκε κενή διαδρομή |



### Δείτε επίσης
* κλάση [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath)
* κλάση [`SmartArtShape`](/slides/python-net/el/aspose.slides.smartart/smartartshape)
* μονάδα [`aspose.slides.smartart`](/slides/python-net/el/aspose.slides.smartart)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)