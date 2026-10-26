---
title: GetGeometryPaths()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει το αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με την αριστερή πάνω γωνία του σχήματος.
type: docs
weight: 53
url: /el/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() μέθοδος


Επιστρέφει το αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με την αριστερή πάνω γωνία του σχήματος.

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```


### Τιμή Επιστροφής

Πίνακας του [IGeometryPath](../../igeometrypath/)
## Σχόλια



Παράδειγμα: 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>();

auto shape = AsCast<GeometryShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 200.0f, 100.0f));

auto geometryPath = shape->GetGeometryPaths()->idx_get(0);

geometryPath->LineTo(100.0f, 50.0f, 1);
geometryPath->LineTo(100.0f, 50.0f, 4);

shape->SetGeometryPath(geometryPath);

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IGeometryPath](../../igeometrypath/)
* Κλάση [GeometryShape](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)