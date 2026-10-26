---
title: SplitTextByColumns()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แยกเนื้อหาข้อความของ ITextFrame เป็นอาร์เรย์ของสตริง โดยแต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกภายในกรอบ.
type: docs
weight: 118
url: /th/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() เมธอด


แยกเนื้อหาข้อความของ [ITextFrame](../) เป็นอาร์เรย์ของสตริง,
โดยที่แต่ละองค์ประกอบสอดคล้องกับคอลัมน์ข้อความแยกภายในกรอบ.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```


### ค่าที่ส่งคืน

อาร์เรย์ของสตริง,
โดยแต่ละสตริงแทนเนื้อหาข้อความของคอลัมน์เฉพาะใน [ITextFrame](../).
## หมายเหตุ



หากกรอบข้อความไม่ได้มีหลายคอลัมน์ อาร์เรย์ที่ส่งกลับจะมีเพียงองค์ประกอบเดียวซึ่งบรรจุข้อความทั้งหมด. 

คอลัมน์ที่ว่างเปล่าจะถูกแสดงเป็นสตริงว่างในอาร์เรย์. 

ตัวอย่างต่อไปนี้แสดงวิธีการใช้ [ITextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// ดึงรูปร่างแรกบนสไลด์และแคสต์เป็น ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// แยกเนื้อหากรอบข้อความเป็นคอลัมน์
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
* คลาส [ITextFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)