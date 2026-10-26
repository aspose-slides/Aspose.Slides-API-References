---
title: SetLowerLimit()
second_title: Aspose.Slides برای C++ مرجع API
description: حد پایین را می‌گیرد
type: docs
weight: 144
url: /fa/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) متد

حد پایین را می‌گیرد

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | حد |

### مقدار بازگشتی

نمونه جدید از نوع [IMathLimit](../../imathlimit/)

## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) متد

حد پایین را می‌گیرد

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | حد |

### مقدار بازگشتی

نمونه جدید از نوع [IMathLimit](../../imathlimit/)

## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## موارد مرتبط

* نوع‌تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathLimit](../../imathlimit/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathElementBase](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)