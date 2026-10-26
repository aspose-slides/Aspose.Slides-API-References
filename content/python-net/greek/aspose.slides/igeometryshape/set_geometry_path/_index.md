---
title: set_geometry_path method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή πάνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([`IGeometryShape.shape_type`](/slides/python-net/el/aspose.slides/igeometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath) | Διαδρομή γεωμετρίας |

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Δε βρέθηκε διαδρομή |
| **RuntimeError(Proxy error(ArgumentException))** | Βρέθηκε κενή διαδρομή |

### Δείτε επίσης
* κλάση [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath)
* κλάση [`IGeometryShape`](/slides/python-net/el/aspose.slides/igeometryshape)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)