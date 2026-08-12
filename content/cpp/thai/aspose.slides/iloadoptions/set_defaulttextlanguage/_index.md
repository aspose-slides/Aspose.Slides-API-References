---
title: set_DefaultTextLanguage()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ตั้งค่าภาษาเริ่มต้นสำหรับข้อความในงานนำเสนอ. เขียน System::String."
type: docs
weight: 326
url: /th/aspose.slides/iloadoptions/set_defaulttextlanguage/
---
## ILoadOptions::set_DefaultTextLanguage(System::String) เมธอด

ตั้งค่าภาษาเริ่มต้นสำหรับข้อความในงานนำเสนอ. เขียน [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DefaultTextLanguage(System::String value)=0
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
* คลาส [ILoadOptions](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)