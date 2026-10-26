---
title: Function()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يأخذ دالة ذات معلمة باستخدام هذه المثيل كاسم الدالة
type: docs
weight: 53
url: /ar/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) طريقة


يأخذ دالة ذات معلمة باستخدام هذه المثيل كاسم الدالة

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | معامل للدالة |

### قيمة الإرجاع

New math element of type [IMathFunction](../../imathfunction/)
## ملاحظات



مثال: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) طريقة


يأخذ دالة ذات معلمة باستخدام هذه المثيل كاسم الدالة

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | معامل للدالة |

### قيمة الإرجاع

New math element of type [IMathFunction](../../imathfunction/)
## ملاحظات



مثال: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [IMathFunction](../../imathfunction/)
* الفئة [IMathElement](../)
* الفئة [String](../../../system/string/)
* المجال [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)