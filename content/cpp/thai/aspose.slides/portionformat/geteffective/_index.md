---
title: GetEffective()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับข้อมูลการจัดรูปแบบส่วนที่มีผลโดยมีการสืบทอดนำไปใช้
type: docs
weight: 131
url: /th/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() เมธอด


รับข้อมูลการจัดรูปแบบส่วนที่มีผลโดยมีการสืบทอดนำไปใช้

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```


### ค่าที่ส่งกลับ

หนึ่ง [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## หมายเหตุ



ตัวอย่างนี้สาธิตการรับคุณสมบัติการจัดรูปแบบส่วนที่มีผลบางอย่าง 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* คลาส [PortionFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)