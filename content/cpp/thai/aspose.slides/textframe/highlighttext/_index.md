---
title: HighlightText()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทำการไฮไลท์ข้อความทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ
type: docs
weight: 131
url: /th/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) เมธอด


ทำการไฮไลท์ข้อความที่ตรงกับข้อความตัวอย่างทั้งหมดด้วยสีที่ระบุ.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ตัวอย่างข้อความเพื่อไฮไลท์. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีที่จะใช้ไฮไลท์ข้อความ. |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) เมธอด


ทำการไฮไลท์ข้อความที่ตรงกับข้อความตัวอย่างทั้งหมดด้วยสีที่ระบุ.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความที่จะไฮไลท์. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีที่จะใช้ไฮไลท์ข้อความ. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | ตัวเลือกสำหรับการไฮไลท์. |
## หมายเหตุ


เลิกใช้แล้ว :   ใช้เมธอด HighlightText(string text, Color highlightColor, ITextSearchOptions options) แทน. เมธอดนี้จะถูกลบหลังจากการปล่อยเวอร์ชัน 24.10.


ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการไฮไลท์ข้อความใน [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) เมธอด


ทำการไฮไลท์ข้อความที่ตรงกับข้อความตัวอย่างทั้งหมดด้วยสีที่ระบุ.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความที่จะไฮไลท์. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | สีที่จะใช้ไฮไลท์ข้อความ. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | วัตถุ callback สำหรับรับผลลัพธ์การค้นหา [IFindResultCallback](../../ifindresultcallback/). |
## หมายเหตุ



ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการไฮไลท์ข้อความใน [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// ไฮไลท์คำทั้งหมด 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// ไฮไลท์การปรากฏแยกของ 'the' ทั้งหมด
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [Color](../../../system.drawing/color/)
* คลาส [TextFrame](../)
* คลาส [ITextHighlightingOptions](../../itexthighlightingoptions/)
* คลาส [ITextSearchOptions](../../itextsearchoptions/)
* คลาส [IFindResultCallback](../../ifindresultcallback/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)