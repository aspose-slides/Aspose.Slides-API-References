---
title: ReplaceRegex()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แทนที่ทุกการจับคู่ของนิพจน์ปกติกับสตริงที่ระบุ.
type: docs
weight: 183
url: /th/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) เมธอด

แทนที่ทุกการจับคู่ของนิพจน์ปกติกับสตริงที่ระบุ.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | นิพจน์ปกติ [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) เพื่อรับสตริงที่จะถูกแทนที่. |
| newText | [System::String](../../../system/string/) | สตริงที่ใช้แทนที่ทุกการปรากฏของสตริงที่จะถูกแทนที่. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | อ็อบเจ็กต์ Callback สำหรับบันทึกผลการดำเนินการแทนที่ [IFindResultCallback](../../ifindresultcallback/). |

## หมายเหตุ

โค้ดตัวอย่างต่อไปนี้แสดงวิธีการแทนที่ข้อความโดยใช้นิพจน์ปกติกับสตริงที่ระบุ. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)