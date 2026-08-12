---
title: HighlightText()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ทำการไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ.
type: docs
weight: 495
url: /th/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) เมธอด

ทำการไฮไลท์ข้อความตัวอย่างที่ตรงกับทุกการจับคู่ด้วยสีที่ระบุ.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
|---|---|---|
| text | [System::String](../../../system/string/) | ข้อความที่ต้องการไฮไลท์ |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีที่จะใช้ไฮไลท์ข้อความ |

## หมายเหตุ

ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการไฮไลท์ข้อความในงานนำเสนอ PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// การไฮไลท์การปรากฏของ 'the' ทั้งหมดแยกกัน
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) เมธอด

ทำการไฮไลท์ข้อความตัวอย่างที่ตรงกับทุกการจับคู่ด้วยสีที่ระบุ.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
|---|---|---|
| text | [System::String](../../../system/string/) | ข้อความที่ต้องการไฮไลท์ |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีที่จะใช้ไฮไลท์ข้อความ |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../ifindresultcallback/). |

## หมายเหตุ

ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการไฮไลท์ข้อความในงานนำเสนอ PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// การไฮไลท์การปรากฏของ 'the' ทั้งหมดแยกกัน
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [Presentation](../)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)