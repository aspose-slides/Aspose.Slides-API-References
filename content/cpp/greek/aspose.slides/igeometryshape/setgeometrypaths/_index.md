---
title: SetGeometryPaths()
second_title: Αναφορά API του Aspose.Slides για C++
description: "Ενημερώνει τη γεωμετρία του σχήματος από πίνακα των IGeometryPath. Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή άνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος (ShapeType) σε ShapeType::Custom."
type: docs
weight: 79
url: /el/aspose.slides/igeometryshape/setgeometrypaths/
---
## IGeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) μέθοδος

Ενημερώνει τη γεωμετρία του σχήματος από πίνακα των [IGeometryPath](../../igeometrypath/). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή άνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([ShapeType](../../shapetype/)) σε [ShapeType::Custom](../../shapetype/).

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths)=0
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Διαδρομές γεωμετρίας πίνακα |
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

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Τάξη [IGeometryPath](../../igeometrypath/)
* Τάξη [IGeometryShape](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)