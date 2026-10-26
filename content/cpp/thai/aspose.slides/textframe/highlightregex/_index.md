---
title: HighlightRegex()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ไฮไลท์การจับคู่ทั้งหมดของนิพจน์ทั่วไปด้วยสีที่ระบุ
type: docs
weight: 157
url: /th/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method

ไฮไลท์การจับคู่ทั้งหมดของนิพจน์ทั่วไปด้วยสีที่ระบุ

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | ข้อความของนิพจน์ทั่วไปเพื่อรับข้อความที่ต้องไฮไลท์ |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีที่ใช้ไฮไลท์ข้อความ |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | ตัวเลือกการไฮไลท์ |

## หมายเหตุ

เลิกใช้
:   ใช้เมธอด HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) แทน เมธอดนี้จะถูกลบหลังจากการปล่อยเวอร์ชัน 24.10

ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการไฮไลท์ข้อความใน [TextFrame](../) ด้วยนิพจน์ทั่วไป
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// ทำการไฮไลท์คำทั้งหมดที่มีอักขระ 10 ตัวหรือมากกว่า
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method

ไฮไลท์การจับคู่ทั้งหมดของนิพจน์ทั่วไปด้วยสีที่ระบุ

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | นิพจน์ทั่วไป [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) เพื่อรับสตริงที่ต้องไฮไลท์ |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีที่ใช้ไฮไลท์ข้อความ |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | วัตถุ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../ifindresultcallback/) |

## หมายเหตุ



ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการไฮไลท์ข้อความใน [TextFrame](../) ด้วยนิพจน์ทั่วไป
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// ทำการไฮไลท์คำทั้งหมดที่มีอักขระ 10 ตัวหรือมากกว่า
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [TextFrame](../)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)