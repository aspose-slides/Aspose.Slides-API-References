---
title: GetEffective()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ดึงข้อมูลการจัดรูปย่อหน้าที่มีผลพร้อมการสืบทอดที่นำมาใช้
type: docs
weight: 365
url: /th/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() method


ดึงข้อมูลการจัดรูปย่อหน้าที่มีผลพร้อมการสืบทอดที่นำมาใช้

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### ค่าที่ส่งคืน

หนึ่ง [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## หมายเหตุ



ตัวอย่างนี้แสดงการดึงคุณลักษณะการจัดรูปย่อหน้าบางอย่างที่มีผล 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* คลาส [ParagraphFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)