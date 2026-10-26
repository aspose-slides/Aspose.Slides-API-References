---
title: Clear()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ลบทุกองค์ประกอบจากคอลเลกชัน.
type: docs
weight: 118
url: /th/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() เมธอด

ลบทุกองค์ประกอบจากคอลเลกชัน.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## ดูเพิ่มเติม

* คลาส [IMathBlockCollection](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)