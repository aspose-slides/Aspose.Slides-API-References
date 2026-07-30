---
title: SetGeometryPaths()
second_title: Aspose.Slides pro C++ API Reference
description: "Aktualizuje geometrii tvaru z pole IGeometryPath. Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru (ShapeType) na ShapeType::Custom."
type: docs
weight: 79
url: /cs/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) metoda

Aktualizuje geometrii tvaru z pole [IGeometryPath](../../igeometrypath/). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru ([ShapeType](../../shapetype/)) na [ShapeType::Custom](../../shapetype/).

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Pole geometrických cest |

## Poznámky



Příklad: 
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

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IGeometryPath](../../igeometrypath/)
* Třída [GeometryShape](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)