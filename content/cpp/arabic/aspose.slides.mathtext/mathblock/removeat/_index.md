---
title: RemoveAt()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يزيل العنصر في الفهرس المحدد للمجموعة.
type: docs
weight: 170
url: /ar/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) طريقة

يزيل العنصر في الفهرس المحدد للمجموعة.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري للعنصر الذي سيتم إزالته. |
## ملاحظات



مثال: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## انظر أيضًا

* الفئة [MathBlock](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)