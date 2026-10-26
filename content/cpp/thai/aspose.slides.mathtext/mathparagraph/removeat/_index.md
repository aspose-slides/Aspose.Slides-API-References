---
title: RemoveAt()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ลบรายการที่ตำแหน่งดัชนีที่ระบุในคอลเลกชัน.
type: docs
weight: 157
url: /th/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph::RemoveAt(int32_t) เมธอด


ลบรายการที่ตำแหน่งที่ระบุในคอลเลกชัน.

```cpp
void Aspose::Slides::MathText::MathParagraph::RemoveAt(int32_t index) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเริ่มจากศูนย์ของรายการที่ต้องการลบ. |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->RemoveAt(0);
```

## ดูเพิ่มเติม

* คลาส [MathParagraph](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)