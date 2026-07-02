---
title: MathDelimiter
second_title: Aspose.Sildes برای .NET مرجع API
description: شیء جداساز را که شامل کاراکترهای باز و بسته مانند پرانتز، کروشه، براکت و خطوط عمودی است و یک یا چند عنصر ریاضی داخل آن که با یک کاراکتر مشخص جدا می‌شوند، مشخص می‌کند. مثال‌ها: 2 2x|2
type: docs
weight: 8650
url: /fa/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter کلاس

شیء جداکننده را مشخص می‌کند که شامل کاراکترهای باز و بسته (مانند پرانتز، کروشه، براکت و خطوط عمودی) و یک یا چند عنصر ریاضی در داخل آن است که با یک کاراکتر مشخص جدا می‌شوند. مثال‌ها: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | MathDelimiter را با عنصر مشخص شده به عنوان آرگومان پایهٔ تک مقداردهی می‌کند |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | یک یا چند عنصر ریاضی که با کاراکترهای جداکننده جدا شده‌اند |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | کاراکتر آغاز جداساز مشخص‌کننده کاراکتر شروع یا بازکننده جداکننده است. جداسازهای ریاضی کاراکترهای احاطه‌کننده‌ای مانند پرانتز، براکت و کروشه هستند. مقدار پیش‌فرض: '(' |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | شکل جداسازها را در شیء جداساز مشخص می‌کند. وقتی مقدار MathDelimiterShape.Centered باشد، جداسازها حول محور ریاضی متن ریاضی مرکزی می‌شوند و برای تطبیق با تمام ارتفاع محتواهایشان تنظیم می‌گردند. وقتی مقدار MathDelimiterShape.Match باشد، ارتفاع و شکل آن‌ها دقیقاً با محتواهایشان منطبق می‌شود |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | کاراکتر پایان جداساز مشخص‌کننده کاراکتر بسته یا پایان جداساز است. جداسازهای ریاضی کاراکترهای احاطه‌کننده‌ای مانند پرانتز، براکت و کروشه هستند. مقدار پیش‌فرض: ')' |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | رشد BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی مقدار true باشد، جداسازها به‌صورت عمودی رشد می‌کنند تا با ارتفاع عملوندشان منطبق شوند. مقدار پیش‌فرض true است |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | کاراکتر جداساز جداکننده مشخص می‌کند که کدام کاراکتر بین آرگومان‌ها در شیء جداکننده قرار می‌گیرد. مقدار پیش‌فرض: '&#x7C;' |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت اکسنت (کاراکتر در بالای این عنصر) تنظیم می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخص‌شده را با این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخص‌شده را با این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخص‌شده را با این نمونه به‌عنوان آرگومان رشته‌ای می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص‌شده را با این نمونه به‌عنوان آرگومان و یک آرگومان اضافی از نوع IMathElement می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخص‌شده را با این نمونه به‌عنوان آرگومان و یک آرگومان رشته‌ای می‌گیرد |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | آرگومان‌ها را با استفاده از کاراکتر جداکنندهٔ مشخص شده محدود می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | کسر با این عنصر به‌عنوان صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | کسر با این عنصر به‌عنوان صورت و مخرج رشته‌ای مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | کسر از نوع مشخص‌شده با این عنصر به‌عنوان صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | کسر از نوع مشخص‌شده با این عنصر به‌عنوان صورت و مخرج رشته‌ای مشخص‌شده ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز محصور می‌کند |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | یک عنصر ریاضی را در کاراکترهای مشخص‌شده مانند پرانتز یا سایر کاراکترها قاب می‌کند |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان می‌گیرد که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان می‌گیرد که این نمونه به‌عنوان نام تابع رشته‌ای استفاده می‌شود |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از یک کروشهٔ پایینی در یک گروه قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند کروشهٔ پایینی یا کاراکتر دیگری در یک گروه قرار می‌دهد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال بدون حدها را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-ary ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-ary ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک نوار در بالای این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشه ریاضی با درجهٔ داده‌شده از آرگومان مشخص‌شده را تعیین می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشه ریاضی با درجهٔ داده‌شده از آرگومان رشته‌ای مشخص‌شده را تعیین می‌کند |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | حد پایین را می‌گیرد |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | حد پایین را می‌گیرد |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | پایین‌نویس ایجاد می‌کند |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | پایین‌نویس ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | پایین‌نویس و فوق‌نویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | پایین‌نویس و فوق‌نویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | پایین‌نویس و فوق‌نویس را در سمت راست ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | پایین‌نویس و فوق‌نویس را در سمت راست ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | فوق‌نویس ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | فوق‌نویس ایجاد می‌کند |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالا را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالا را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبهٔ حاشیه‌دار قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبهٔ حاشیه‌دار قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبهٔ غیر‌دیداری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی اجزای یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود. یک شیء جعبه‌دار می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، به‌عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که از شکست خط درون آن جلوگیری شود |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایهٔ عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک نوار در پایین این عنصر تنظیم می‌کند |

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### همچنین ببینید

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathDelimiter](../imathdelimiter)
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->