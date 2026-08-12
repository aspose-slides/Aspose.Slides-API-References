---
title: HighlightText()
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: ไฮไลท์ข้อความที่ตรงกับตัวอย่างทั้งหมดด้วยสีที่ระบุ.
type: docs
weight: 456
url: /th/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) เมธอด

ไฮไลท์ข้อความที่ตรงกับตัวอย่างทั้งหมดด้วยสีที่ระบุ

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความที่จะไฮไลท์ |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีที่จะใช้ไฮไลท์ข้อความ |

## หมายเหตุ

ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการไฮไลท์ข้อความในงานนำเสนอ PowerPoint  
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// ไฮไลท์การปรากฏตัวของ 'the' ทั้งหมดที่แยกจากกัน
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) เมธอด

ไฮไลท์ข้อความที่ตรงกับตัวอย่างทั้งหมดด้วยสีที่ระบุ

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความที่จะไฮไลท์ |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีที่จะใช้ไฮไลท์ข้อความ |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../itextsearchoptions/) |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | วัตถุ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../ifindresultcallback/) |

## หมายเหตุ

ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการไฮไลท์ข้อความในงานนำเสนอ PowerPoint  
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// ไฮไลท์การปรากฏของ 'the' ทั้งหมดที่แยกจากกัน
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [Color](../../../system.drawing/color/)
* คลาส [IPresentation](../)
* คลาส [ITextSearchOptions](../../itextsearchoptions/)
* คลาส [IFindResultCallback](../../ifindresultcallback/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)