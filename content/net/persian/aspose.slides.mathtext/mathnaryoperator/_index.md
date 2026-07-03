---
title: MathNaryOperator
second_title: Aspose.Sildes برای .NET مرجع API
description: یک شیء ریاضی N-ار را مشخص می‌کند مانند جمع و انتگرال. این شامل یک عملگر، پایه یا عملوند و حدود بالایی و پایینی اختیاری است. نمونه‌های عملگرهای N-ار شامل جمع، اتحاد، تقاطع و انتگرال هستند.
type: docs
weight: 8870
url: /fa/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator کلاس

یک شیء ریاضی N-ار را مشخص می‌کند، مانند جمع و انتگرال. این شیء شامل یک عملگر، پایه (یا عملوند) و حدود بالایی و پایینی اختیاری است. نمونه‌هایی از عملگرهای N-ار عبارتند از: جمع، اتحاد، تقاطع، انتگرال

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | یک نمونه جدید از کلاس MathNaryOperator را مقداردهی اولیه می‌کند. |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | یک نمونه جدید از کلاس MathNaryOperator را مقداردهی اولیه می‌کند. |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | یک نمونه جدید از کلاس MathNaryOperator را مقداردهی اولیه می‌کند. |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | آرگومان پایه |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | کاراکتر عملگر به صورت عمودی رشد می‌کند تا با ارتفاع عملوند مطابقت پیدا کند |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | پنهان‌سازی زیرنویس |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | پنهان‌سازی بالانویس |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | مکان قرارگیری حدود (زیرنویس و بالانویس) |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | کاراکتر عملگر N-ار؛ برای مثال: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | زیرنویس را مشخص می‌کند؛ به عنوان مثال در مورد یک انتگرال، حد پایین را تعیین می‌کند |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | بالانویس را مشخص می‌کند؛ به عنوان مثال در مورد یک انتگرال، حد بالا را تعیین می‌کند |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت اکسنت (کاراکتر در بالای این عنصر) را تنظیم می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | با استفاده از این نمونه به‌عنوان آرگومان، تابع مشخص‌شده را می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | با استفاده از این نمونه به‌عنوان آرگومان، تابع مشخص‌شده را می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | با استفاده از این نمونه به‌عنوان آرگومان، تابع مشخص‌شده را می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافی مشخص‌شده، تابع مشخص‌شده را می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافی مشخص‌شده، تابع مشخص‌شده را می‌گیرد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | با این صورت‌حساب تا‌ک (numerator) و مخرج مشخص‌شده، یک کسر ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | با این صورت‌حساب تا‌ک (numerator) و مخرج مشخص‌شده، یک کسر ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | با این تا‌ک و مخرج مشخص‌شده، یک کسر از نوع مشخص شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | با این تا‌ک و مخرج مشخص‌شده، یک کسر از نوع مشخص شده ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | عنصر ریاضی را در پرانتز می‌گیرد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | عنصر ریاضی را در کاراکترهای مشخص‌شده‌ای مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | یک تابع از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | یک تابع از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از یک کروشهٔ پایین در یک گروه قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند کروشهٔ پایین یا کاراکتر دیگری در گروه قرار می‌دهد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال را بدون حدود می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی ایجاد می‌کند |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را می‌پیوندد و یک بلوک ریاضی ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-ار ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-ار ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک نوار در بالای این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشهٔ ریاضی از درجهٔ داده‌شده را از آرگومان مشخص‌شده استخراج می‌کند. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشهٔ ریاضی از درجهٔ داده‌شده را از آرگومان مشخص‌شده استخراج می‌کند. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | حد پایین را می‌گیرد |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | حد پایین را می‌گیرد |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | زیرنویس ایجاد می‌کند |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | زیرنویس ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | بالانویس ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | بالانویس ایجاد می‌کند |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالا را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالا را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبه‌مرز قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبه‌مرز قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبهٔ غیر دیداری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی اجزای یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود. یک شیء جعبه‌دار می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، به‌عنوان نقطهٔ شکست خط عمل کند یا به‌گونه‌ای گروه‌بندی شود که از شکست خط داخل آن جلوگیری شود. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایهٔ عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک نوار در پایین این عنصر تنظیم می‌کند |

### مثال‌ها

مثال:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### موارد مرتبط

* کلاس [MathElementBase](../mathelementbase)
* اینترفیس [IMathNaryOperator](../imathnaryoperator)
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->