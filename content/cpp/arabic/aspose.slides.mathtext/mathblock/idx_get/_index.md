---
title: idx_get()
second_title: مرجع API Aspose.Slides للغة C++
description: يحصل على IMathElement في الفهرس المحدد.
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) طريقة


يحصل على [IMathElement](../../imathelement/) في الفهرس المحدد.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري للعنصر |

### قيمة الإرجاع

العنصر الرياضي.
## ملاحظات



مثال: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathBlock](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)