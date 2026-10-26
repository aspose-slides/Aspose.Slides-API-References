---
title: Function()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تأخذ دالة ذات معامل باستخدام هذا الكائن كاسم الدالة
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) طريقة

تأخذ دالة ذات معامل باستخدام هذا الكائن كاسم الدالة

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | وسيط الدالة |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathFunction](../../imathfunction/)
## ملاحظات



مثال: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) طريقة


تأخذ دالة ذات معامل باستخدام هذا الكائن كاسم الدالة

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | وسيط الدالة |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathFunction](../../imathfunction/)
## ملاحظات



مثال: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathFunction](../../imathfunction/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathElementBase](../)
* فئة [String](../../../system/string/)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)