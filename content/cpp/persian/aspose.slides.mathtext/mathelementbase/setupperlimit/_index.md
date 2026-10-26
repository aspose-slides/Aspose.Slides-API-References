---
title: SetUpperLimit()
second_title: Aspose.Slides برای مرجع API C++
description: حد بالایی را می‌گیرد
type: docs
weight: 131
url: /fa/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) متد


حد بالایی را می‌گیرد

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### مقدار بازگشتی

نمونه جدید از نوع [IMathLimit](../../imathlimit/)
## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) متد


حد بالایی را می‌گیرد

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### مقدار بازگشتی

نمونه جدید از نوع [IMathLimit](../../imathlimit/)
## توضیحات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathLimit](../../imathlimit/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathElementBase](../)
* کلاس [String](../../../system/string/)
* فضای نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)