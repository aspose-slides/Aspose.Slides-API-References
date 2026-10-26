---
title: CreateMathAccent()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ تسليطًا رياضيًا يُطبق على عنصر رياضي محدد باستخدام قيمة حرف التسليط الافتراضية
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) طريقة

ينشئ تسليط رياضي يُطبق على عنصر رياضي محدد باستخدام قيمة حرف التسليط الافتراضية

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الرياضي لتطبيق التسليط |

### قيمة الإرجاع

تسليط رياضي جديد

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) طريقة

ينشئ تسليط رياضي يُطبق على عنصر رياضي محدد

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الرياضي لتطبيق التسليط |
| accentCharacter | char16_t | حرف التسليط |

### قيمة الإرجاع

تسليط رياضي جديد

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathAccent](../../imathaccent/)
* Class [IMathElement](../../imathelement/)
* Class [IMathAccentFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)