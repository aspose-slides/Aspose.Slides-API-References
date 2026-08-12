---
title: ReplaceText()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แทนที่การปรากฏทั้งหมดของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ
type: docs
weight: 144
url: /th/aspose.slides/itextframe/replacetext/
---
## ITextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) เมธอด

แทนที่ข้อความที่ระบุทั้งหมดด้วยข้อความอื่นที่ระบุ

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | สตริงที่จะถูกแทนที่ |
| newText | [System::String](../../../system/string/) | สตริงที่จะแทนที่การปรากฏทั้งหมดของ oldText |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../itextsearchoptions/) |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../ifindresultcallback/) |

## หมายเหตุ

โค้ดตัวอย่างต่อไปนี้แสดงวิธีการแทนที่สตริงที่ระบุหนึ่งด้วยสตริงที่ระบุอีกหนึ่ง
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// แทนที่การปรากฏของ 'the' แยกเป็นคำทั้งหมดด้วย '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [ITextSearchOptions](../../itextsearchoptions/)
* คลาส [IFindResultCallback](../../ifindresultcallback/)
* คลาส [ITextFrame](../)
* เนมสเปส [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)