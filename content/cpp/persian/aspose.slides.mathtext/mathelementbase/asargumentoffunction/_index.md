---
title: AsArgumentOfFunction()
second_title: Aspose.Slides برای C++ - مرجع API
description: تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد
type: docs
weight: 53
url: /fa/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) متد

تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | نام تابع |

### مقدار بازگشت

عنصر ریاضی جدید از نوع [IMathFunction](../../imathfunction/)
## نکات



مثال: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) متد

تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | نام تابع |

### مقدار بازگشت

عنصر ریاضی جدید از نوع [IMathFunction](../../imathfunction/)
## نکات



مثال: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) متد

تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | یکی از انواع توابع رایج با یک آرگومان |

### مقدار بازگشت

عنصر ریاضی جدید از نوع [IMathFunction](../../imathfunction/)
## نکات



مثال: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) متد

تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی مشخص می‌گیرد

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | یکی از انواع توابع رایج با دو آرگومان: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | آرگومان اضافه بسته به نوع تابع |

### مقدار بازگشت

عنصر ریاضی جدید از نوع [IMathFunction](../../imathfunction/)
## نکات



مثال: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// مقدار لگاریتم 'x' با پایه '5' را برمی‌گرداند
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) متد

تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی مشخص می‌گیرد

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | یکی از انواع توابع رایج با دو آرگومان: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | آرگومان اضافه بسته به نوع تابع |

### مقدار بازگشت

عنصر ریاضی جدید از نوع [IMathFunction](../../imathfunction/)
## نکات



مثال: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// مقدار لگاریتم 'x' با پایه '5' را برمی‌گرداند
```

## موارد مرتبط

* شمارنده [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* شمارنده [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathFunction](../../imathfunction/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathElementBase](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)