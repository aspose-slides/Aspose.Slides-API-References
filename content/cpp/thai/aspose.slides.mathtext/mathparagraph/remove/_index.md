---
title: Remove()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุออกจากคอลเลกชัน/>
type: docs
weight: 105
url: /th/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) เมธอด

ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุออกจากคอลเลกชัน/>.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | วัตถุที่จะลบออกจากคอลเลกชัน. |

### ค่าที่ส่งคืน

true หาก *mathBlock* ถูกลบสำเร็จจากคอลเลกชัน; หากไม่, false. เมธอดนี้ยังคืนค่า false หาก *mathBlock* ไม่พบในคอลเลกชันต้นฉบับ/>.

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBlock](../../imathblock/)
* คลาส [MathParagraph](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)