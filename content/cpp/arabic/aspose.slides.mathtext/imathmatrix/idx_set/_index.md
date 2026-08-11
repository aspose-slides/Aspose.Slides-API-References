---
title: idx_set()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عناصر المصفوفة
type: docs
weight: 222
url: /ar/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) طريقة

عناصر المصفوفة

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| row | **int32_t** | المؤشر الصفري للصف للحصول على العنصر |
| column | **int32_t** | المؤشر الصفري للعمود للحصول على العنصر |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |

## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathMatrix](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)