---
title: idx_get()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึงรายการที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว IMathBlock.
type: docs
weight: 40
url: /th/aspose.slides.mathtext/mathparagraph/idx_get/
---
## MathParagraph::idx_get(int32_t) เมธอด

ดึงรายการที่ตำแหน่งระบุเป็นค่าอ่านอย่างเดียว [IMathBlock](../../imathblock/).

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathParagraph::idx_get(int32_t index) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเริ่มต้นจากศูนย์ของรายการที่ต้องการดึง |

### ค่าที่ส่งกลับ

บล็อกของข้อความคณิตศาสตร์

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)