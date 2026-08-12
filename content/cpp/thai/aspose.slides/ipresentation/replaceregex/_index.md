---
title: ReplaceRegex()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แทนที่การจับคู่ทั้งหมดของนิพจน์ปกติกับสตริงที่ระบุ
type: docs
weight: 495
url: /th/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) เมธอด

แทนที่การจับคู่ทั้งหมดของนิพจน์ปกติกับสตริงที่ระบุ

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | นิพจน์ปกติ [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) เพื่อรับสตริงที่จะทำการแทนที่ |
| newText | [System::String](../../../system/string/) | สตริงที่ใช้แทนที่การเกิดซ้ำทั้งหมดของสตริงที่จะถูกแทนที่ |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | อ็อบเจ็กต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../ifindresultcallback/) |

## หมายเหตุ

ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการแทนที่ข้อความโดยใช้นิพจน์ปกติพร้อมสตริงที่ระบุ
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Regex](../../../system.text.regularexpressions/regex/)
* คลาส [String](../../../system/string/)
* คลาส [IFindResultCallback](../../ifindresultcallback/)
* คลาส [IPresentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)