---
title: AsArgumentOfFunction()
second_title: مرجع API Aspose.Slides برای C++
description: تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد
type: docs
weight: 66
url: /fa/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) متد

تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | نام تابع |

### مقدار برگشتی

عنصر ریاضی جدید از نوع [IMathFunction](../../imathfunction/)

## ملاحظات

مثال: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) متد

تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | نام تابع |

### مقدار برگشتی

عنصر ریاضی جدید از نوع [IMathFunction](../../imathfunction/)

## ملاحظات

مثال: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) متد

تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | یکی از انواع توابع رایج با یک آرگومان |

### مقدار برگشتی

عنصر ریاضی جدید از نوع [IMathFunction](../../imathfunction/)

## ملاحظه‌ها

مثال: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) متد

تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافهٔ مشخص‌شده می‌گیرد

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | یکی از انواع توابع رایج با دو آرگومان: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | آرگومان اضافه که بسته به نوع تابع متفاوت است |

### مقدار برگشتی

عنصر ریاضی جدید از نوع [IMathFunction](../../imathfunction/)

## ملاحظات

مثال: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// لگاریتم 'x' به پایه '5' را برمی‌گرداند
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) متد

تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافهٔ مشخص‌شده می‌گیرد

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | یکی از انواع توابع رایج با دو آرگومان: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | آرگومان اضافه که بسته به نوع تابع متفاوت است |

### مقدار برگشتی

عنصر ریاضی جدید از نوع [IMathFunction](../../imathfunction/)

## ملاحظات

مثال: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// لگاریتم 'x' به پایه '5' را برمی‌گرداند
```

## See Also

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)