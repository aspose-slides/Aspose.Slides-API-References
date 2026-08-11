---
title: CreateMathLimit()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ IMathLimit
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) طريقة

ينشئ [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```


### المعلمات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | المُعامل الأساسي لتطبيق الحد |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر الحد |
| upperLimit | **bool** | يضبط موضع الحد في الأعلى |

### قيمة الإرجاع

حد رياضي جديد

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) طريقة

ينشئ [IMathLimit](../../imathlimit/) مع الحد في الأسفل

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```


### المعلمات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | المُعامل الأساسي لتطبيق الحد |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر الحد |

### قيمة الإرجاع

حد رياضي جديد

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathLimit](../../imathlimit/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathLimitFactory](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)