---
title: FindAndReplaceText()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: ค้นหาและแทนที่ข้อความในงานนำเสนอด้วยรูปแบบที่กำหนด
type: docs
weight: 40
url: /th/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) เมธอด


ค้นหาและแทนที่ข้อความในงานนำเสนอด้วยรูปแบบที่กำหนด

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | งานนำเสนอที่สแกน |
| withMasters | **bool** | กำหนดว่าควรสแกนสไลด์มาสเตอร์หรือไม่ |
| find | [System::String](../../../system/string/) | ค่าข้อความที่ต้องการค้นหา |
| replace | [System::String](../../../system/string/) | ค่าขข้อความที่ต้องการแทนที่ |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | รูปแบบสำหรับการแทนที่ส่วนของข้อความ หากเป็น null จะใช้รูปแบบของอักขระแรกของสตริงที่พบ |
## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto format = System::MakeObject<PortionFormat>();
format->set_FontHeight(24.0f);
format->set_FontItalic(NullableBool::True);
auto fillFormat = format->get_FillFormat();
fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());

SlideUtil::FindAndReplaceText(pres, true, u"[this block] ", u"my text ", format);
pres->Save(u"replaced", SaveFormat::Pptx);
```




## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPresentation](../../../aspose.slides/ipresentation/)
* คลาส [String](../../../system/string/)
* คลาส [PortionFormat](../../../aspose.slides/portionformat/)
* คลาส [SlideUtil](../)
* เนมสเปซ [Aspose::Slides::Util](../../)
* ไลบรารี [Aspose.Slides](../../../)