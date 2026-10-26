---
title: ReplaceRegex()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แทนที่การจับคู่ทั้งหมดของนิพจน์ปกติกับสตริงที่ระบุ
type: docs
weight: 534
url: /th/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) เมธอด

แทนที่การจับคู่ทั้งหมดของนิพจน์ปกติกับสตริงที่ระบุ

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | นิพจน์ปกติ [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) เพื่อรับสตริงที่ต้องการแทนที่ |
| newText | [System::String](../../../system/string/) | สตริงที่จะใช้แทนที่ทุกตำแหน่งของสตริงที่ต้องการแทนที่ |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | อ็อบเจกต์ callback สำหรับรับผลการค้นหา [IFindResultCallback](../../ifindresultcallback/) |
## หมายเหตุ



ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการแทนที่ข้อความโดยใช้นิพจน์ปกติกับสตริงที่ระบุ
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* กำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [Regex](../../../system.text.regularexpressions/regex/)
* คลาส [String](../../../system/string/)
* คลาส [IFindResultCallback](../../ifindresultcallback/)
* คลาส [Presentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)