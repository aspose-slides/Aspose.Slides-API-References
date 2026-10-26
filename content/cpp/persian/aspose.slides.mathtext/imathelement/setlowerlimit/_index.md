---
title: SetLowerLimit()
second_title: Aspose.Slides برای C++ مرجع API
description: حد پایین را می‌گیرد
type: docs
weight: 157
url: /fa/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) متد

تعیین حد پایین

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### مقدار بازگشت

نمونه جدید از نوع [IMathLimit](../../imathlimit/)
## یادداشت‌ها



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) متد

تعیین حد پایین

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### مقدار بازگشت

نمونه جدید از نوع [IMathLimit](../../imathlimit/)
## یادداشت‌ها



مثال: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathLimit](../../imathlimit/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)