---
title: Function()
second_title: Aspose.Slides برای C++ مرجع API
description: یک تابع از یک آرگومان را می‌گیرد که نام تابع با استفاده از این نمونه تعیین می‌شود
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) متد

یک تابع از یک آرگومان را می‌گیرد که نام تابع با استفاده از این نمونه تعیین می‌شود

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | یک آرگومان از تابع |

### مقدار بازگشتی

عنصر ریاضی جدید از نوع [IMathFunction](../../imathfunction/)
## توضیحات

مثال: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) متد

یک تابع از یک آرگومان را می‌گیرد که نام تابع با استفاده از این نمونه تعیین می‌شود

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | یک آرگومان از تابع |

### مقدار بازگشتی

عنصر ریاضی جدید از نوع [IMathFunction](../../imathfunction/)
## توضیحات

مثال: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathFunction](../../imathfunction/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathElementBase](../)
* کلاس [String](../../../system/string/)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)