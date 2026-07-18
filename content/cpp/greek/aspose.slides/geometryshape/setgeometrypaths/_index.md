---
title: SetGeometryPaths()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Ενημερώνει τη γεωμετρία του σχήματος από έναν πίνακα των IGeometryPath. Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή πάνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος (ShapeType) σε ShapeType::Custom."
type: docs
weight: 79
url: /el/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) μέθοδος

Ενημερώνει τη γεωμετρία του σχήματος από έναν πίνακα των [IGeometryPath](../../igeometrypath/). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή πάνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([ShapeType](../../shapetype/)) σε [ShapeType::Custom](../../shapetype/).

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Διαδρομές γεωμετρίας πίνακα |
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

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IGeometryPath](../../igeometrypath/)
* Κλάση [GeometryShape](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)