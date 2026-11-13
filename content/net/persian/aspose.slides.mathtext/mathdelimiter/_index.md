---
title: MathDelimiter
second_title: Aspose.Sildes برای مرجع API .NET
description: شیء جداکننده را که از نویسه‌های باز و بسته مانند پرانتزها، آکولادها، کروشه‌ها و خطوط عمودی تشکیل شده و یک یا بیش از یک عنصر ریاضی داخل آن که با یک نویسهٔ مشخص جدا شده‌اند، مشخص می‌کند. مثال‌ها 2 2x7C2
type: docs
weight: 8670
url: /fa/aspose.slides.mathtext/mathdelimiter/
---
## کلاس MathDelimiter

شیء جداکننده را مشخص می‌کند که شامل نویسه‌های باز و بسته (مانند پرانتزها، آکولادها، کروشه‌ها و خطوط عمودی) و یک یا چند عنصر ریاضی درون آن است که با یک نویسهٔ مشخص جدا می‌شوند. مثال‌ها: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | MathDelimiter را با عنصری که به‌عنوان آرگومان پایهٔ واحد مشخص شده، مقداردهی اولیه می‌کند |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | یک یا چند عنصر ریاضی که با نویسه‌های جداکننده جدا شده‌اند |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | کاراکتر آغازگر جداکننده شروع یا کاراکتر باز شدن جداکننده را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای محاط‌کننده‌ای مانند پرانتزها، کروشه‌ها و آکولادها هستند. مقدار پیش‌فرض: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | شکل جداکننده‌ها را در شیء جداکننده مشخص می‌کند. وقتی MathDelimiterShape.Centered باشد، جداکننده‌ها حول محور ریاضی متن ریاضی مرکزیت دارند و همچنان می‌توانند برای متناسب شدن با تمام ارتفاع محتوا تنظیم شوند. وقتی MathDelimiterShape.Match باشد، ارتفاع و شکل آن‌ها دقیقاً مطابق محتوا تغییر می‌کند. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | کاراکتر پایانگر جداکننده پایان یا کاراکتر بسته شدن جداکننده را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای محاط‌کننده‌ای مانند پرانتزها، کروشه‌ها و آکولادها هستند. مقدار پیش‌فرض: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | رشد BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی مقدار true باشد، جداکننده‌ها به صورت عمودی رشد می‌کنند تا با ارتفاع عملوند مطابقت داشته باشند. مقدار پیش‌فرض true است. |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | کاراکتر جداکنندهٔ جداکننده را مشخص می‌کند که آرگومان‌ها را در شیء جداکننده جدا می‌کند. مقدار پیش‌فرض: '&#x7C;'. |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت اکسنت تنظیم می‌کند (یک نویسه در بالای این عنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان دریافت می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان دریافت می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان دریافت می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافی مشخص‌شده دریافت می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافی مشخص‌شده دریافت می‌کند |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | آرگومان‌ها را با استفاده از کاراکتر جداکنندهٔ مشخص‌شده محدود می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | یک کسر با این صورت‌عدد و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | یک کسر با این صورت‌عدد و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | یک کسر از نوع مشخص‌شده با این صورت‌عدد و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | یک کسر از نوع مشخص‌شده با این صورت‌عدد و مخرج مشخص‌شده ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز می‌گیرد |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | یک عنصر ریاضی را در کاراکترهای مشخص‌شده مانند پرانتز یا سایر کاراکترها به‌صورت قاب می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع دریافت می‌کند |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع دریافت می‌کند |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از کروشهٔ پایین به یک گروه می‌گذارد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از کاراکتر گروه‌بندی مانند کروشهٔ پایین یا کاراکتر دیگری به یک گروه می‌گذارد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال بدون حدود را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی شکل می‌دهد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | یک متن ریاضی را می‌پیوندد و یک بلوک ریاضی شکل می‌دهد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-آری ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-آری ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک میله در بالای این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشهٔ ریاضی از درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشهٔ ریاضی از درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | حد پایین را می‌گیرد |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | حد پایین را می‌گیرد |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | زیرنویس ایجاد می‌کند |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | زیرنویس ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | در سمت چپ زیرنویس و بالانویس ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | در سمت چپ زیرنویس و بالانویس ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | در سمت راست زیرنویس و بالانویس ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | در سمت راست زیرنویس و بالانویس ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | بالانویس ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | بالانویس ایجاد می‌کند |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالا را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالا را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبهٔ قاب‌دار قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبهٔ قاب‌دار قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبهٔ غیر‌تصویری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی اجزای یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود. یک شیء جعبه‌دار می‌تواند (به‌عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، به‌عنوان نقطهٔ قطع خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ قطع خط درون آن را ندهد. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایهٔ عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک میله در پایین این عنصر تنظیم می‌کند |

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### موارد مرتبط

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathDelimiter](../imathdelimiter)
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->