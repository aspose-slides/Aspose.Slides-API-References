---
title: SetUpperLimit()
second_title: Aspose.Slides برای C++ مرجع API
description: حد بالایی را می‌گیرد
type: docs
weight: 144
url: /fa/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) روش

حد بالایی را می‌گیرد

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### مقدار بازگشت

نمونه‌ای جدید از نوع [IMathLimit](../../imathlimit/)

## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) روش


حد بالایی را می‌گیرد

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### مقدار بازگشت

نمونه‌ای جدید از نوع [IMathLimit](../../imathlimit/)

## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathLimit](../../imathlimit/)
* کلاس [IMathElement](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)