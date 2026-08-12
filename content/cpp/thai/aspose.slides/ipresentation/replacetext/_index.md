---
title: ReplaceText()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทนที่การปรากฏทั้งหมดของข้อความที่ระบุด้วยข้อความที่ระบุอื่น.
type: docs
weight: 482
url: /th/aspose.slides/ipresentation/replacetext/
---
## IPresentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) เมธอด

แทนที่การปรากฏทั้งหมดของข้อความที่ระบุด้วยข้อความที่ระบุอื่น

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | สตริงที่จะถูกแทนที่. |
| newText | [System::String](../../../system/string/) | สตริงที่จะใช้แทนที่การปรากฏทั้งหมดของ oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | ตัวเลือกการค้นหาข้อความ [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | ออบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../ifindresultcallback/). |

## หมายเหตุ

โค้ดตัวอย่างต่อไปนี้แสดงวิธีการแทนที่สตริงที่ระบุหนึ่งด้วยสตริงที่ระบุอื่น.

```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// แทนที่การปรากฏของคำ 'the' ที่เป็นแยกทั้งหมดด้วย '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [ITextSearchOptions](../../itextsearchoptions/)
* คลาส [IFindResultCallback](../../ifindresultcallback/)
* คลาส [IPresentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)