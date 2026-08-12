---
title: get_DefaultTextLanguage()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "คืนค่าภาษาเริ่มต้นสำหรับข้อความในงานนำเสนอ อ่าน System::String."
type: docs
weight: 313
url: /th/aspose.slides/loadoptions/get_defaulttextlanguage/
---
## LoadOptions::get_DefaultTextLanguage() เมธอด

คืนค่าภาษาเริ่มต้นสำหรับข้อความในงานนำเสนอ อ่าน [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultTextLanguage() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DefaultTextLanguage(u"en-US");

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(loadOptions);

// Add new rectangle shape with text
System::SharedPtr<IAutoShape> shp = pres->get_Slide(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 50.0f, 50.0f, 150.0f, 50.0f);
shp->get_TextFrame()->set_Text(u"New Text");

// Check the first portion language
System::SharedPtr<IPortion> portion = shp->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
System::Console::WriteLine(portion->get_PortionFormat()->get_LanguageId());
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [LoadOptions](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)