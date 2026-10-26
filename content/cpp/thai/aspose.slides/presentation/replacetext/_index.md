---
title: ReplaceText()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทนที่การปรากฏทั้งหมดของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ
type: docs
weight: 521
url: /th/aspose.slides/presentation/replacetext/
---
## Presentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) เมธอด

แทนที่ข้อความที่ระบุทั้งหมดด้วยข้อความอื่นที่ระบุ

```cpp
void Aspose::Slides::Presentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | The string to be replaced. |
| newText | [System::String](../../../system/string/) | The string to replace all occurrences of oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Text search options [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | The callback object for receiving search results [IFindResultCallback](../../ifindresultcallback/). |

## หมายเหตุ

โค้ดตัวอย่างต่อไปนี้แสดงวิธีการแทนที่สตริงที่ระบุหนึ่งด้วยสตริงอื่นที่ระบุ
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// แทนที่การเกิดขึ้นทั้งหมดของ 'the' ที่แยกจากกันด้วย '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)