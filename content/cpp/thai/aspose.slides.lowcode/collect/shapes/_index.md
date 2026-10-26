---
title: Shapes()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เก็บรวบรวมทุกอินสแตนซ์ของ Shape ใน Presentation.
type: docs
weight: 1
url: /th/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) เมธอด

เก็บรวมรวมทุกอินสแตนซ์ของ [Shape](../../../aspose.slides/shape/) ใน [Presentation](../../../aspose.slides/presentation/).

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) เพื่อเก็บรูปร่าง |

### ค่าที่ส่งกลับ

คอลเล็กชันของรูปทรงทั้งหมดที่อยู่ในงานนำเสนอ
## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // หากรูปเป็น AutoShape ให้เพิ่มขอบสีดำแบบเติมเต็ม
    if (System::ObjectExt::Is<AutoShape>(shape))
    {
        auto autoShape = System::AsCast<AutoShape>(shape);
        autoShape->get_LineFormat()->set_Style(LineStyle::Single);
        autoShape->get_LineFormat()->set_Width(10.0f);
        autoShape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::Solid);
        autoShape->get_LineFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Black());
    }
}

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```




## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IEnumerable](../../../system.collections.generic/ienumerable/)
* คลาส [Shape](../../../aspose.slides/shape/)
* คลาส [Presentation](../../../aspose.slides/presentation/)
* คลาส [Collect](../)
* เนมสเปซ [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)