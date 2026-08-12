---
title: GetEffective()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ดึงข้อมูลการจัดรูปแบบ 3-D ที่มีผลพร้อมการสืบทอดที่ใช้
type: docs
weight: 183
url: /th/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() เมธอด

ดึงข้อมูลการจัดรูปแบบ 3-D ที่มีผลพร้อมกับการสืบทอดที่ใช้.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```

### ค่าที่ส่งคืน

อ็อบเจ็กต์ [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).
## หมายเหตุ

ตัวอย่างนี้สาธิตวิธีการดึงคุณสมบัติที่มีผลสำหรับกล้อง, โครงแสงและ bevel ด้านบนของรูปร่าง. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto threeDEffectiveData = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_ThreeDFormat()->GetEffective();

Console::WriteLine(u"= Effective camera properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_Camera()->get_CameraType()));
Console::WriteLine(String(u"Field of view: ") + threeDEffectiveData->get_Camera()->get_FieldOfViewAngle());
Console::WriteLine(String(u"Zoom: ") + threeDEffectiveData->get_Camera()->get_Zoom());

Console::WriteLine(u"= Effective light rig properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_LightRig()->get_LightType()));
Console::WriteLine(String(u"Direction: ") + ObjectExt::ToString(threeDEffectiveData->get_LightRig()->get_Direction()));

Console::WriteLine(u"= Effective shape's top face relief properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_BevelTop()->get_BevelType()));
Console::WriteLine(String(u"Width: ") + threeDEffectiveData->get_BevelTop()->get_Width());
Console::WriteLine(String(u"Height: ") + threeDEffectiveData->get_BevelTop()->get_Height());
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* คลาส [ThreeDFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)