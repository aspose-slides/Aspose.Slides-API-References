---
title: AsArgumentOfFunction()
second_title: مرجع API Aspose.Slides للغة C++
description: تقوم بأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل
type: docs
weight: 66
url: /ar/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) طريقة

تأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | اسم الدالة |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathFunction](../../imathfunction/)

## ملاحظة



مثال: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) طريقة

تأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | اسم الدالة |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathFunction](../../imathfunction/)

## ملاحظة



مثال: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) طريقة

تأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | إحدى أنواع الدوال الشائعة ذات معامل واحد |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathFunction](../../imathfunction/)

## ملاحظة



مثال: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) طريقة

تأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل ومعامل إضافي محدد

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | إحدى أنواع الدوال الشائعة ذات معاملين: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | معامل إضافي يعتمد على نوع الدالة |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathFunction](../../imathfunction/)

## ملاحظة



مثال: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// إرجاع لوغاريتم 'x' إلى الأساس '5'
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) طريقة

تأخذ الدالة المحددة باستخدام هذه المثيلة كمعامل ومعامل إضافي محدد

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | إحدى أنواع الدوال الشائعة ذات معاملين: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | معامل إضافي يعتمد على نوع الدالة |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathFunction](../../imathfunction/)

## ملاحظة



مثال: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// إرجاع لوغاريتم 'x' إلى الأساس '5'
```

## راجع أيضًا

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)