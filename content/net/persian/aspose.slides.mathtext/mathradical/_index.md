---
title: MathRadical
second_title: Aspose.Sildes برای .NET مرجع API
description: عملکرد رادیکال را که شامل یک پایه و یک درجه اختیاری است، مشخص می‌کند. مثال یک شی رادیکال .
type: docs
weight: 8940
url: /fa/aspose.slides.mathtext/mathradical/
---
## کلاس MathRadical

عملکرد رادیکل را مشخص می‌کند که شامل یک پایه و یک درجه اختیاری است. مثال یک شی رادیکل √𝑥 است.

```csharp
public sealed class MathRadical : MathElementBase, IMathRadical
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathRadical](mathradical)(IMathElement, IMathElement) | یک نمونه جدید از کلاس MathRadical را مقداردهی اولیه می‌کند. |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathradical/base) { get; } | آرگومان پایه |
| [Degree](../../aspose.slides.mathtext/mathradical/degree) { get; } | آرگومان درجه |
| [HideDegree](../../aspose.slides.mathtext/mathradical/hidedegree) { get; set; } | زمانیکه مقدار true باشد، درجه نشان داده نمی‌شود، مانند √𝑥 |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت اکسنت (یک کاراکتر در بالای این عنصر) را تنظیم می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافه مشخص شده می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافه مشخص شده می‌گیرد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | یک کسر با صورت این عنصر و مخرج مشخص شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | یک کسر با صورت این عنصر و مخرج مشخص شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | یک کسر از نوع مشخص شده با صورت این عنصر و مخرج مشخص شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | یک کسر از نوع مشخص شده با صورت این عنصر و مخرج مشخص شده ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز محصور می‌کند |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | یک عنصر ریاضی را در کاراکترهای مشخص شده (مانند پرانتز یا کاراکترهای دیگر) به‌عنوان قاب محصور می‌کند |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | یک تابع از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | یک تابع از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [GetChildren](../../aspose.slides.mathtext/mathradical/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از یک براکت منحنی پایین در یک گروه قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از کاراکتر گروه‌بندی مانند براکت منحنی پایین یا دیگر در یک گروه قرار می‌دهد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال بدون حدها را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی شکل می‌دهد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را می‌پیوندد و یک بلوک ریاضی شکل می‌دهد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-ary ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-ary ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک نوار در بالای این عنصر قرار می‌دهد |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشه ریاضی از درجه داده‌شده برای آرگومان مشخص شده را تعیین می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشه ریاضی از درجه داده‌شده برای آرگومان مشخص شده را تعیین می‌کند |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | حد پایین را می‌گیرد |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | حد پایین را می‌گیرد |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | یک زیرنویس ایجاد می‌کند |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | یک زیرنویس ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | بالانویس ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | بالانویس ایجاد می‌کند |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالا را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالا را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبه‌حاشیه‌ای قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبه‌حاشیه‌ای قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبه غیر‌دیداری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود. یک شی جعبه‌شده می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطه‌ترازبندی، به‌عنوان نقطه شکست خط، یا به‌صورت گروه‌بندی شده باشد به‌طوری که اجازه شکست خط درون آن را ندهد. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایه عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک نوار در پایین این عنصر قرار می‌دهد |

### مثال‌ها

مثال:

```csharp
[C#]
MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```

### مراجع

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathRadical](../imathradical)
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->