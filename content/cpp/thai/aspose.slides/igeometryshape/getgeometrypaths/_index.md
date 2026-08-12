---
title: GetGeometryPaths()
second_title: Aspose.Slides สำหรับ API ของ C++
description: ส่งคืนสำเนาของเส้นทางของรูปทรงเรขาคณิต พิกัดอ้างอิงจากมุมซ้ายบนของรูปทรง
type: docs
weight: 53
url: /th/aspose.slides/igeometryshape/getgeometrypaths/
---
## IGeometryShape::GetGeometryPaths() วิธีการ


ส่งคืนสำเนาของเส้นทางของรูปทรงเรขาคณิต พิกัดอ้างอิงจากมุมซ้ายบนของรูปทรง

```cpp
virtual System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::IGeometryShape::GetGeometryPaths()=0
```


### ค่าที่ส่งกลับ

อาร์เรย์ของ [IGeometryPath](../../igeometrypath/)
## หมายเหตุ



ตัวอย่าง: 
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
* คลาส [IGeometryPath](../../igeometrypath/)
* คลาส [IGeometryShape](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)