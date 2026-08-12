---
title: GetEffective()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับข้อมูลการจัดรูปแบบกรอบข้อความที่มีผลโดยใช้การสืบทอด
type: docs
weight: 391
url: /th/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() เมธอด


รับข้อมูลการจัดรูปแบบกรอบข้อความที่มีผลโดยใช้การสืบทอด

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```


### ค่ารีเทิร์น

เป็น [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## หมายเหตุ



ตัวอย่างนี้แสดงการรับคุณลักษณะการจัดรูปแบบกรอบข้อความที่มีผลบางส่วน 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextFrameFormat = shape->get_TextFrame()->get_TextFrameFormat()->GetEffective();

Console::WriteLine(String(u"Anchoring type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AnchoringType()));
Console::WriteLine(String(u"Autofit type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AutofitType()));
Console::WriteLine(String(u"Text vertical type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_TextVerticalType()));
Console::WriteLine(u"Margins");
Console::WriteLine(String(u"   Left: ") + effectiveTextFrameFormat->get_MarginLeft());
Console::WriteLine(String(u"   Top: ") + effectiveTextFrameFormat->get_MarginTop());
Console::WriteLine(String(u"   Right: ") + effectiveTextFrameFormat->get_MarginRight());
Console::WriteLine(String(u"   Bottom: ") + effectiveTextFrameFormat->get_MarginBottom());
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* คลาส [TextFrameFormat](../)
* เนมสเปส [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)