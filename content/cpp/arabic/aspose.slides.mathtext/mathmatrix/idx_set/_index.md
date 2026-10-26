---
title: idx_set()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: عنصر من المصفوفة
type: docs
weight: 222
url: /ar/aspose.slides.mathtext/mathmatrix/idx_set/
---
## MathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) طريقة

عنصر من المصفوفة

```cpp
void Aspose::Slides::MathText::MathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value) override
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| row | **int32_t** | الفهرس الصفري للصف للحصول على العنصر |
| column | **int32_t** | الفهرس الصفري للعمود للحصول على العنصر |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |

## ملاحظات

مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathMatrix](../)
* نطاق الاسم [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)