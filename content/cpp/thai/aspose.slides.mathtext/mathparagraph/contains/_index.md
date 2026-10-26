---
title: Contains()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าคอลเลกชันมีค่าที่ระบุหรือไม่
type: docs
weight: 118
url: /th/aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph::Contains(System::SharedPtr\<IMathBlock\>) เมธอด


กำหนดว่าคอลเลกชันมีค่าที่ระบุหรือไม่

```cpp
bool Aspose::Slides::MathText::MathParagraph::Contains(System::SharedPtr<IMathBlock> mathBlock) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | อ็อบเจ็กต์ที่ต้องการค้นหาในคอลเลกชัน. |

### ค่าที่ส่งกลับ

true หากพบ *mathBlock* ในคอลเลกชัน; มิฉะนั้น false.
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
bool contains = mathParagraph->Contains(block);
```

## ดูเพิ่มเติม

* การกำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBlock](../../imathblock/)
* คลาส [MathParagraph](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)