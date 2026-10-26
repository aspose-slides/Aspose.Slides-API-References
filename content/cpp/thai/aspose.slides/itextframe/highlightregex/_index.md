---
title: HighlightRegex()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ไฮไลต์การจับคู่ทั้งหมดของนิพจน์ทั่วไปด้วยสีที่ระบุ
type: docs
weight: 131
url: /th/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) เมธอด

ไฮไลต์การจับคู่ทั้งหมดของนิพจน์ทั่วไปด้วยสีที่ระบุ.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### อาร์กิวเมนท์

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | นิพจน์ทั่วไป [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) เพื่อรับสตริงที่จะไฮไลต์. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีที่จะไฮไลต์ข้อความ. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | อ็อบเจกต์ callback เพื่อรับผลการค้นหา [IFindResultCallback](../../ifindresultcallback/). |

## หมายเหตุ

ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการไฮไลต์ข้อความใน [TextFrame](../../textframe/) โดยใช้นิพจน์ทั่วไป. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) เมธอด

ไฮไลต์การจับคู่ทั้งหมดของนิพจน์ทั่วไปด้วยสีที่ระบุ.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### อาร์กิวเมนท์

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | ข้อความของนิพจน์ทั่วไปเพื่อรับข้อความที่จะไฮไลต์. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีที่จะไฮไลต์ข้อความ. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | ตัวเลือกการไฮไลต์. |

เลิกใช้
:   ใช้เมธอด HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) แทน. เมธอดนี้จะถูกลบหลังจากการปล่อยเวอร์ชัน 24.10.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Regex](../../../system.text.regularexpressions/regex/)
* คลาส [Color](../../../system.drawing/color/)
* คลาส [IFindResultCallback](../../ifindresultcallback/)
* คลาส [ITextFrame](../)
* คลาส [String](../../../system/string/)
* คลาส [ITextHighlightingOptions](../../itexthighlightingoptions/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)