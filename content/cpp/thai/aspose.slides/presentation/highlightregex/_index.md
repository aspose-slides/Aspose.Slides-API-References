---
title: HighlightRegex()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ทำไฮไลท์การจับคู่ทั้งหมดของนิพจน์ปกติโดยใช้สีที่ระบุ.
type: docs
weight: 508
url: /th/aspose.slides/presentation/highlightregex/
---
## Presentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method


ไฮไลท์การจับคู่ทั้งหมดของนิพจน์ปกติด้วยสีที่ระบุ

```cpp
void Aspose::Slides::Presentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | นิพจน์ปกติ [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) เพื่อรับสตริงที่จะทำการไฮไลท์ |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีสำหรับทำไฮไลท์ข้อความ |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../ifindresultcallback/) |
## หมายเหตุ



ตัวอย่างโค้ดต่อไปนี้แสดงวิธีทำไฮไลท์ข้อความใน PowerPoint [Presentation](../) โดยใช้นิพจน์ปกติ 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// ไฮไลท์คำทั้งหมดที่มี 10 หรือมากกว่าตัวอักษร
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Regex](../../../system.text.regularexpressions/regex/)
* คลาส [Color](../../../system.drawing/color/)
* คลาส [IFindResultCallback](../../ifindresultcallback/)
* คลาส [Presentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)