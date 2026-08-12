---
title: HighlightText()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: ไฮไลท์ข้อความที่ตรงกับตัวอย่างทั้งหมดด้วยสีที่ระบุ.
type: docs
weight: 105
url: /th/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) เมธ็อด

ไฮไลท์ข้อความที่ตรงกับตัวอย่างทั้งหมดด้วยสีที่ระบุ.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความที่จะไฮไลท์ |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีที่จะใช้ไฮไลท์ข้อความ |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) เมธ็อด

ไฮไลท์ข้อความที่ตรงกับตัวอย่างทั้งหมดด้วยสีที่ระบุ.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความที่จะไฮไลท์ |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีที่จะใช้ไฮไลท์ข้อความ |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | ตัวเลือกการไฮไลท์ |

เลิกใช้
:   ใช้เมธ็อด HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) แทน วิธีนี้จะถูกลบหลังการออกเวอร์ชัน 24.10.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) เมธ็อด

ไฮไลท์ข้อความที่ตรงกับตัวอย่างทั้งหมดด้วยสีที่ระบุ.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความที่จะไฮไลท์ |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีที่จะใช้ไฮไลท์ข้อความ |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../itextsearchoptions/) |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | วัตถุ callback เพื่อรับผลการค้นหา [IFindResultCallback](../../ifindresultcallback/) |

## หมายเหตุ

ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการไฮไลท์ข้อความใน [TextFrame](../../textframe/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [Color](../../../system.drawing/color/)
* คลาส [ITextFrame](../)
* คลาส [ITextHighlightingOptions](../../itexthighlightingoptions/)
* คลาส [ITextSearchOptions](../../itextsearchoptions/)
* คลาส [IFindResultCallback](../../ifindresultcallback/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)