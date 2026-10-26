---
title: idx_set()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يعين IMathElement في الفهرس المحدد.
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/mathblock/idx_set/
---
## MathBlock::idx_set(int32_t, System::SharedPtr\<IMathElement\>) طريقة

يعين [IMathElement](../../imathelement/) في الفهرس المحدد.

```cpp
void Aspose::Slides::MathText::MathBlock::idx_set(int32_t index, System::SharedPtr<IMathElement> value)
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري للعنصر |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الرياضي. |
## ملاحظات



مثال:
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathBlock](../)
* مساحة أسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)