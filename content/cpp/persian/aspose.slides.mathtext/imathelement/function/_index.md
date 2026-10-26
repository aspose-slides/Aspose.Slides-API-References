---
title: Function()
second_title: مرجع API Aspose.Slides برای C++
description: یک تابع را با یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود
type: docs
weight: 53
url: /fa/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) متد


یک تابع را با یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | یک آرگومان از تابع |

### مقدار بازگشت

یک عنصر ریاضی جدید از نوع [IMathFunction](../../imathfunction/)
## توضیحات



مثال: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) متد


یک تابع را با یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | یک آرگومان از تابع |

### مقدار بازگشت

یک عنصر ریاضی جدید از نوع [IMathFunction](../../imathfunction/)
## توضیحات



مثال: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## یک‌نظری

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)