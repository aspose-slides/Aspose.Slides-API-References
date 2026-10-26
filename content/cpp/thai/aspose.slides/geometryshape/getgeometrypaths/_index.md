---
title: GetGeometryPaths()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนสำเนาของเส้นทางของรูปทรงเรขาคณิต พิกัดอ้างอิงจากมุมซ้ายบนของรูปทรง
type: docs
weight: 53
url: /th/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() เมธอด


ส่งคืนสำเนาของเส้นทางของรูปทรงเรขาคณิต พิกัดอ้างอิงจากมุมซ้ายบนของรูปทรง

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```


### ค่าที่ส่งคืน

Array of [IGeometryPath](../../igeometrypath/)
## หมายเหตุ



Example: 
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

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGeometryPath](../../igeometrypath/)
* Class [GeometryShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)