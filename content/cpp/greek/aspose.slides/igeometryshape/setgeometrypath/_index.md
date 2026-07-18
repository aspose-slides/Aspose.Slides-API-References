---
title: SetGeometryPath()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο IGeometryPath. Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή επάνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος (ShapeType) σε ShapeType::Custom."
type: docs
weight: 66
url: /el/aspose.slides/igeometryshape/setgeometrypath/
---
## IGeometryShape::SetGeometryPath(System::SharedPtr\<IGeometryPath\>) μέθοδος

Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [IGeometryPath](../../igeometrypath/). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή επάνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([ShapeType](../../shapetype/)) σε [ShapeType::Custom](../../shapetype/).

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPath(System::SharedPtr<IGeometryPath> geometryPath)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| geometryPath | [System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\> | Διαδρομή γεωμετρίας |

## Σχόλια



Παράδειγμα: 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>();

auto shape = AsCast<GeometryShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 200.0f, 100.0f));

auto geometryPath0 = MakeObject<GeometryPath>();
geometryPath0->MoveTo(0.0f, 0.0f);
geometryPath0->LineTo(shape->get_Width(), 0.0f);
geometryPath0->LineTo(shape->get_Width(), shape->get_Height() / 3);
geometryPath0->LineTo(0.0f, shape->get_Height() / 3);
geometryPath0->CloseFigure();

auto geometryPath1 = MakeObject<GeometryPath>();
geometryPath1->MoveTo(0.0f, shape->get_Height() / 3 * 2);
geometryPath1->LineTo(shape->get_Width(), shape->get_Height() / 3 * 2);
geometryPath1->LineTo(shape->get_Width(), shape->get_Height());
geometryPath1->LineTo(0.0f, shape->get_Height());
geometryPath1->CloseFigure();

shape->SetGeometryPaths(StaticCastArray<SharedPtr<IGeometryPath>>(MakeArray<SharedPtr<GeometryPath>>({geometryPath0, geometryPath1})));

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IGeometryPath](../../igeometrypath/)
* Κλάση [IGeometryShape](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)