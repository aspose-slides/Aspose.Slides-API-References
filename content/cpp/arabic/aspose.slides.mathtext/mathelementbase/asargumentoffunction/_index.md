---
title: AsArgumentOfFunction()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يأخذ الدالة المحددة باستخدام هذا الكائن كمعامل
type: docs
weight: 53
url: /ar/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) طريقة


يأخذ الدالة المحددة باستخدام هذا الكائن كمعامل

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | اسم الدالة |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathFunction](../../imathfunction/)
## ملاحظات



مثال: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) طريقة


يأخذ الدالة المحددة باستخدام هذا الكائن كمعامل

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | اسم الدالة |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathFunction](../../imathfunction/)
## ملاحظات



مثال: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) طريقة


يأخذ الدالة المحددة باستخدام هذا الكائن كمعامل

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | أحد أنواع الدوال الشائعة ذات معامل واحد |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathFunction](../../imathfunction/)
## ملاحظات



مثال: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) طريقة


يأخذ الدالة المحددة باستخدام هذا الكائن كمعامل ويضيف معاملًا إضافيًا محددًا

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | أحد أنواع الدوال الشائعة ذات معاملين: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | معامل إضافي يعتمد على نوع الدالة |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathFunction](../../imathfunction/)
## ملاحظات



مثال: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// يرجع اللوغاريتم للـ 'x' للقاعدة '5'
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) طريقة


يأخذ الدالة المحددة باستخدام هذا الكائن كمعامل ويضيف معاملًا إضافيًا محددًا

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | أحد أنواع الدوال الشائعة ذات معاملين: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | معامل إضافي يعتمد على نوع الدالة |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathFunction](../../imathfunction/)
## ملاحظات



مثال: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// يرجع اللوغاريتم للـ 'x' للقاعدة '5'
```

## انظر أيضًا

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)