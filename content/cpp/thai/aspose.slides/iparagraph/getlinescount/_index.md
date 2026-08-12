---
title: GetLinesCount()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับจำนวนบรรทัดในย่อหน้า.
type: docs
weight: 105
url: /th/aspose.slides/iparagraph/getlinescount/
---
## IParagraph::GetLinesCount() เมธอด


รับจำนวนบรรทัดในย่อหน้า.

```cpp
virtual int32_t Aspose::Slides::IParagraph::GetLinesCount()=0
```


### ค่าที่ส่งกลับ

จำนวนบรรทัดในย่อหน้า
## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```


## ดูเพิ่มเติม

* คลาส [IParagraph](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)