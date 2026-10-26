---
title: Clear()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ลบองค์ประกอบทั้งหมดออกจากคอลเลกชัน.
type: docs
weight: 79
url: /th/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() เมธอด

ลบองค์ประกอบทั้งหมดออกจากคอลเลกชัน.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## ดูเพิ่มเติม

* คลาส [MathParagraph](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)