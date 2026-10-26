---
title: SplitTextByColumns()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แยกเนื้อหาข้อความของ ITextFrame เป็นอาร์เรย์ของสตริง, โดยแต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกต่าง ๆ ภายในกรอบ.
type: docs
weight: 144
url: /th/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() เมธอด


แยกเนื้อหาข้อความของ [ITextFrame](../../itextframe/) เป็นอาร์เรย์ของสตริง, 

โดยแต่ละองค์ประกอบจะสอดคล้องกับคอลัมน์ข้อความแยกต่าง ๆ ภายในกรอบ.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```


### ค่าที่ส่งคืน

อาร์เรย์ของสตริง, โดยแต่ละสตริงจะแสดงเนื้อหาข้อความของคอลัมน์เฉพาะ 

ใน [ITextFrame](../../itextframe/).
## หมายเหตุ



หากเฟรมข้อความไม่ได้มีหลายคอลัมน์, อาร์เรย์ที่ส่งกลับจะมีหนึ่งองค์ประกอบ 

ที่มีข้อความเต็ม. 

คอลัมน์ที่ว่างจะถูกแสดงเป็นสตริงว่างในอาร์เรย์. 

ตัวอย่างต่อไปนี้แสดงวิธีใช้ [TextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// ดึงรูปร่างแรกบนสไลด์และแคสต์เป็น ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// แยกเนื้อหาใน text frame เป็นคอลัมน์
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// พิมพ์ข้อความของแต่ละคอลัมน์ไปยังคอนโซล
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [TextFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)