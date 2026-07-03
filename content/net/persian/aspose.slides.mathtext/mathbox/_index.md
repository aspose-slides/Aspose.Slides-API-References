---
title: MathBox
second_title: Aspose.Sildes برای .NET مرجع API
description: مشخص می‌کند بسته‌بندی منطقی جعبه‌ای عنصر ریاضی چگونه است. به عنوان مثال یک شیء جعبه‌بندی‌شده می‌تواند به عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، به عنوان نقطه شکست خط عمل کند یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط درون آن را ندهد. برای مثال عملگر باید جعبه‌بندی شود تا از شکست خطوط جلوگیری شود.
type: docs
weight: 8630
url: /fa/aspose.slides.mathtext/mathbox/
---
## MathBox کلاس

جعبه‌بندی منطقی (بسته‌بندی) عنصر ریاضی را مشخص می‌کند. به عنوان مثال، یک شیء جعبه‌بندی‌شده می‌تواند به عنوان یک شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، به عنوان نقطه شکستن خط عمل کند یا به‌گونه‌ای گروه‌بندی شود که اجازه شکست خط درون آن را ندهد. به عنوان مثال، عملگر "==" باید جعبه‌بندی شود تا از شکستن خط جلوگیری شود.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | MathBox را با عنصر مشخص‌شده به‌عنوان آرگومان مقداردهی اولیه می‌کند |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | زمانی که true باشد، این شبیه‌ساز عملگر به‌عنوان نقطه تراز عمل می‌کند؛ به این معنا که نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن تراز شوند. پیش‌فرض: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | آرگومان پایه |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differential زمانی که true باشد، جعبه به‌عنوان دیفرانسیل عمل می‌کند (مثلاً 𝑑𝑥 در یک انتگرال) و فاصله افقی مناسب برای دیفرانسیل ریاضی را دریافت می‌کند. پیش‌فرض: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | شکست صریح مشخص می‌کند آیا در ابتدای شیء Box یک شکست خط وجود دارد یا خیر، به‌طوری که خط در ابتدای شیء جعبه شکست بخورد. عدد عملگر در خط قبلی متن ریاضی را که به‌عنوان نقطه تراز برای خط فعلی متن ریاضی استفاده می‌شود، مشخص می‌کند. مقادیر ممکن: 1..255 پیش‌فرض: 0 (بدون شکست صریح) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | بدون شکست این ویژگی خاصیت «قابل شکست نیست» را بر روی شیء جعبه تعریف می‌کند. زمانی که true باشد، هیچ شکست خطی نمی‌تواند درون جعبه رخ دهد. این می‌تواند برای شبیه‌سازهای عملگر که شامل بیش از یک عملگر دودویی هستند مهم باشد. زمانی که این عنصر مشخص نشود، شکست‌ها می‌توانند درون جعبه رخ دهند. پیش‌فرض: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | شبیه‌ساز عملگر. زمانی که true باشد، جعبه و محتویات آن مشابه یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. این به معنای این است که برای مثال، کاراکتر می‌تواند به‌عنوان نقطه‌ی شکست خط عمل کند و می‌تواند با عملگرهای دیگر تراز شود. Emulatorهای عملگر اغلب زمانی استفاده می‌شوند که یک یا چند glyph برای تشکیل یک عملگر ترکیب می‌شوند، مانند '=='. پیش‌فرض: false |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت تلفظی (یک کاراکتر در بالای این عنصر) را تنظیم می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان فراخوانی می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان فراخوانی می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان فراخوانی می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافی مشخص‌شده فراخوانی می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافی مشخص‌شده فراخوانی می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | کسر را با این صورت‌حاصل و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | کسر را با این صورت‌حاصل و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | کسر از نوع مشخص‌شده را با این صورت‌حاصل و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | کسر از نوع مشخص‌شده را با این صورت‌حاصل و مخرج مشخص‌شده ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز می‌گیرد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | یک عنصر ریاضی را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع فراخوانی می‌کند |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع فراخوانی می‌کند |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | دریافت عناصر فرزند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از یک براکت خمیده پایین در یک گروه قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند براکت خمیده پایین یا کاراکتر دیگر در یک گروه قرار می‌دهد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال را بدون حدود می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را ترکیب کرده و یک بلوک ریاضی تشکیل می‌دهد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را ترکیب کرده و یک بلوک ریاضی تشکیل می‌دهد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-ary ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-ary ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک خط افقی در بالای این عنصر قرار می‌دهد |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشه ریاضی با درجه داده‌شده از آرگومان مشخص‌شده را تعیین می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشه ریاضی با درجه داده‌شده از آرگومان مشخص‌شده را تعیین می‌کند |
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
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالایی را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالایی را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبه مرزی قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبه مرزی قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبه غیر‌دیداری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود. یک شیء جعبه‌بندی‌شده می‌تواند (به‌عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز، به‌عنوان نقطه شکست خط عمل کند یا به‌گونه‌ای گروه‌بندی شود که اجازه شکست خط درون آن را ندهد |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایه عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک خط افقی در پایین این عنصر قرار می‌دهد |

### مثال‌ها

مثال:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### همچنین ببینید

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathBox](../imathbox)
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->