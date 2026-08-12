---
title: Collect
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนของกลุ่มเมธอดที่มีจุดประสงค์เพื่อรวบรวมวัตถุโมเดลประเภทต่าง ๆ จาก Presentation.
type: docs
weight: 1
url: /th/aspose.slides.lowcode/collect/
---
## Collect คลาส

เป็นตัวแทนของกลุ่มเมธอดที่มีจุดประสงค์เพื่อรวบรวมวัตถุโมเดลประเภทต่าง ๆ จาก [Presentation](../../aspose.slides/presentation/).

```cpp
class Collect
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | รวบรวมอินสแตนซ์ทั้งหมดของ [Shape](../../aspose.slides/shape/) ใน [Presentation](../../aspose.slides/presentation/). |
## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... เปลี่ยนการจัดรูปแบบของ shape หรือคุณสมบัติอื่น ๆ
}
```

## ดูเพิ่มเติม

* เนมสเปซ [Aspose::Slides::LowCode](../)
* ไลบรารี [Aspose.Slides](../../)