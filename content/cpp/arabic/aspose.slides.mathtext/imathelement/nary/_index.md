---
title: Nary()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ مشغلًا N-ary
type: docs
weight: 170
url: /ar/aspose.slides.mathtext/imathelement/nary/
---
## IMathElement::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) طريقة

ينشئ مشغلًا N-ary

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | نوع مشغل N-ary |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | الحد الأدنى |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | الحد الأعلى |

### Return Value

مثال جديد من النوع [IMathNaryOperator](../../imathnaryoperator/)
## ملاحظات



مثال: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"i-1");
System::SharedPtr<IMathElement> lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
System::SharedPtr<IMathElement> upperLimit = System::MakeObject<MathematicalText>(u"\U0001d45b");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## IMathElement::Nary(MathNaryOperatorTypes, System::String, System::String) طريقة

ينشئ مشغلًا N-ary

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | نوع مشغل N-ary |
| lowerLimit | [System::String](../../../system/string/) | الحد الأدنى |
| upperLimit | [System::String](../../../system/string/) | الحد الأعلى |

### Return Value

مثال جديد من النوع [IMathNaryOperator](../../imathnaryoperator/)
## ملاحظات



مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d45b");
```

## انظر أيضًا

* تعداد [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* صف [IMathNaryOperator](../../imathnaryoperator/)
* صف [IMathElement](../)
* صف [String](../../../system/string/)
* فضاء الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)