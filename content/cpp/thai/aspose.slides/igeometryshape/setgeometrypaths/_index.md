---
title: SetGeometryPaths()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "อัปเดตรูปทรงเรขาคณิตของ shape จากอาเรย์ของ IGeometryPath. พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape (ShapeType) เป็น ShapeType::Custom."
type: docs
weight: 79
url: /th/aspose.slides/igeometryshape/setgeometrypaths/
---
## IGeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) method

อัปเดตรูปทรงเรขาคณิตของรูปจากอาเรย์ของ [IGeometryPath](../../igeometrypath/). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปทรง. เปลี่ยนประเภทของรูปทรง ([ShapeType](../../shapetype/)) เป็น [ShapeType::Custom](../../shapetype/).

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | อาร์เรย์ของเส้นทางเรขาคณิต |
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