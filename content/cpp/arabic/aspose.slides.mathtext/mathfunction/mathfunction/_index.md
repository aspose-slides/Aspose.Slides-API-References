---
title: MathFunction()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إنشاء مثيل جديد لفئة MathFunction.
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/mathfunction/mathfunction/
---
## MathFunction::MathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) المُنشئ

ينشئ مثيلًا جديدًا للفئة [MathFunction](../).

```cpp
Aspose::Slides::MathText::MathFunction::MathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)
```

## ملاحظات

مثال:
```cpp
auto func = System::MakeObject<MathFunction>(System::MakeObject<MathematicalText>(u"sin"), System::MakeObject<MathematicalText>(u"x"));
```

## MathFunction::MathFunction(System::String, System::SharedPtr\<IMathElement\>) المُنشئ

ينشئ مثيلًا جديدًا للفئة [MathFunction](../).

```cpp
Aspose::Slides::MathText::MathFunction::MathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)
```

## ملاحظات

مثال:
```cpp
auto func = System::MakeObject<MathFunction>(u"sin", System::MakeObject<MathematicalText>(u"x"));
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IMathElement](../../imathelement/)
* الفئة [MathFunction](../)
* الفئة [String](../../../system/string/)
* فضاء الاسم [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)