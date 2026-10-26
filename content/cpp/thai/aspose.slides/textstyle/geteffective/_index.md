---
title: GetEffective()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับข้อมูลการจัดรูปแบบสไตล์ข้อความที่มีผลโดยมีการสืบทอดที่ใช้.
type: docs
weight: 27
url: /th/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() เมธอด


รับข้อมูลการจัดรูปแบบสไตล์ข้อความที่มีผลโดยมีการสืบทอดที่ใช้.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### ค่าที่ส่งกลับ

A [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## หมายเหตุ



ตัวอย่างนี้แสดงการดึงคุณลักษณะสไตล์ข้อความบางส่วนที่มีผล. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextStyle = shape->get_TextFrame()->get_TextFrameFormat()->get_TextStyle()->GetEffective();

for (int32_t i = 0; i <= 8; i++)
{
    auto effectiveStyleLevel = effectiveTextStyle->GetLevel(i);
    Console::WriteLine(String(u"= Effective paragraph formatting for style level #") + i + u" =");

    Console::WriteLine(String(u"Depth: ") + effectiveStyleLevel->get_Depth());
    Console::WriteLine(String(u"Indent: ") + effectiveStyleLevel->get_Indent());
    Console::WriteLine(String(u"Alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_Alignment()));
    Console::WriteLine(String(u"Font alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_FontAlignment()));
}
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* คลาส [TextStyle](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)