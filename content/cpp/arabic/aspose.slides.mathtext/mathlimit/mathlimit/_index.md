---
title: MathLimit()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بتهيئة مثال جديد من الفئة MathLimit.
type: docs
weight: 53
url: /ar/aspose.slides.mathtext/mathlimit/mathlimit/
---
## MathLimit::MathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) constructor


يقوم بتهيئة مثال جديد من الفئة [MathLimit](../).

```cpp
Aspose::Slides::MathText::MathLimit::MathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)
```

## ملاحظات


مثال: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"\U0001d45b→∞"), false);
```

## MathLimit::MathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor


يقوم بتهيئة مثال جديد من الفئة [MathLimit](../) مع الحد الأدنى

```cpp
Aspose::Slides::MathText::MathLimit::MathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)
```

## ملاحظات


مثال: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"\U0001d45b→∞"));
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathLimit](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)