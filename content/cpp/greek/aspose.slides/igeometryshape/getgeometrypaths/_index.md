---
title: GetGeometryPaths()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Επιστρέφει ένα αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με το πάνω αριστερό γωνιακό σημείο του σχήματος.
type: docs
weight: 53
url: /el/aspose.slides/igeometryshape/getgeometrypaths/
---
## IGeometryShape::GetGeometryPaths() μέθοδος


Επιστρέφει ένα αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με την πάνω αριστερή γωνία του σχήματος.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::IGeometryShape::GetGeometryPaths()=0
```


### Τιμή Επιστροφής

Array of [IGeometryPath](../../igeometrypath/)
## Παρατηρήσεις



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

* Ορισμός τύπου [ArrayPtr](../../../system/arrayptr/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IGeometryPath](../../igeometrypath/)
* Κλάση [IGeometryShape](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)