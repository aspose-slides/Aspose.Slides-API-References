---
title: SetUpperLimit()
second_title: Aspose.Slides لمرجع API C++
description: يأخذ الحد العلوي
type: docs
weight: 131
url: /ar/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) طريقة


يأخذ الحد العلوي

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | الحد |

### قيمة إرجاع

مثيل جديد من النوع [IMathLimit](../../imathlimit/)
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) طريقة


يأخذ الحد العلوي

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | الحد |

### قيمة إرجاع

مثيل جديد من النوع [IMathLimit](../../imathlimit/)
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathLimit](../../imathlimit/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathElementBase](../)
* فئة [String](../../../system/string/)
* المجال [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)