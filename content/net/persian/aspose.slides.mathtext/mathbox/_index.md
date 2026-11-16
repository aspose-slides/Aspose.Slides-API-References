---
title: MathBox
second_title: Aspose.Sildes برای .NET مرجع API
description: پکیج-بندی منطقی جعبه‌گذاری یک عنصر ریاضی را مشخص می‌کند. به عنوان مثال، یک شیء بسته‌بندی‌شده می‌تواند به عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، به عنوان نقطه شکست خط عمل کند یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط درون آن را ندهد. به عنوان مثال، عملگر باید بسته‌بندی شود تا از شکست خط جلوگیری شود.
type: docs
weight: 8650
url: /fa/aspose.slides.mathtext/mathbox/
---
## کلاس MathBox

انتخاب بسته‌بندی منطقی (بسته‌گذاری) یک عنصر ریاضی را مشخص می‌کند. به عنوان مثال، یک شیء بسته‌بندی‌شده می‌تواند به عنوان یک شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، به عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط درون آن نباشد. به عنوان مثال، عملگر "==" باید بسته‌بندی شود تا از شکست خط جلوگیری شود.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | MathBox را با عنصری که به‌عنوان آرگومان مشخص شده است، مقداردهی اولیه می‌کند |

## خصوصیات

| نام | توضیح |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | زمانی که true باشد، این شبیه‌ساز عملگر به عنوان نقطه‌ تراز عمل می‌کند؛ یعنی نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن هم‌تراز شوند. مقدار پیش‌فرض: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | آرگومان پایه |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | متغیر: زمانی که true باشد، جعبه به عنوان یک تفاضل عمل می‌کند (مثلاً 𝑑𝑥 در یک انتگرال‌گر)، و فاصلهٔ افقی مناسب برای تفاضل ریاضی دریافت می‌کند. مقدار پیش‌فرض: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Explicit break تعیین می‌کند آیا در ابتدای شیء Box شکست خط وجود دارد یا خیر، به‌طوری که خط در ابتدای شیء جعبه شکسته شود. تعداد عملگری در خط قبلی متن ریاضی که به عنوان نقطه تراز برای خط جاری متن ریاضی استفاده می‌شود را مشخص می‌کند؛ مقادیر ممکن: 1..255. مقدار پیش‌فرض: 0 (بدون شکست صریح) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | No break این ویژگی خاصیت «قابل شکست نیست» را بر روی جعبه شیء مشخص می‌کند. زمانی که true باشد، هیچ شکستی درون جعبه رخ نمی‌دهد. این می‌تواند برای شبیه‌سازهای عملگر که شامل بیش از یک عملگر باینری هستند مهم باشد. وقتی این عنصر مشخص نشود، امکان شکست درون جعبه وجود دارد. مقدار پیش‌فرض: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator Emulator. زمانی که true باشد، جعبه و محتویات آن رفتار یک عملگر واحد را دارند و خصوصیات یک عملگر را به ارث می‌برند. به عنوان مثال، این به این معنی است که کاراکتر می‌تواند به عنوان نقطه‌ای برای شکست خط عمل کند و می‌تواند به سایر عملگرها هم‌تراز شود. شبیه‌سازهای عملگر معمولاً زمانی استفاده می‌شوند که یک یا چند گلیف ترکیب شوند تا یک عملگر مانند '==' تشکیل دهند. مقدار پیش‌فرض: false |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت اکسنت تنظیم می‌کند (کاراکتری در بالای این عنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | توابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | توابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | توابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافی مشخص‌شده می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافی رشته‌ای می‌گیرد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | کسر را با این صورت‌عدد و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | کسر را با این صورت‌عدد و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | کسر از نوع مشخص‌شده را با این صورت‌عدد و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | کسر از نوع مشخص‌شده را با این صورت‌عدد و مخرج مشخص‌شده ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز می‌گیرد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | یک عنصر ریاضی را در کاراکترهای مشخص‌شده‌ای مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان می‌گیرد به‌طوری که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان می‌گیرد به‌طوری که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از یک کروشه‌پایینی به‌صورت گروهی قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند پرانتز‌کروشی پایین یا دیگری در یک گروه قرار می‌دهد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال را بدون محدودیت می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را ملحق می‌کند و یک بلوک ریاضی ایجاد می‌سازد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را ملحق می‌کند و یک بلوک ریاضی ایجاد می‌سازد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-آی ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-آی ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | نوار را روی بالای این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشه ریاضی از درجهٔ داده‌شده را از آرگومان مشخص شده تعیین می‌کند. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشه ریاضی از درجهٔ داده‌شده را از آرگومان مشخص شده تعیین می‌کند. |
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
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالایی را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالایی را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبه مرز قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبه مرز قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبه غیر دیداری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود. یک شیء بسته‌بندی‌شده می‌تواند (برای مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز، به عنوان نقطه شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط درون آن نباشد. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایهٔ عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | نوار را در پایین این عنصر تنظیم می‌کند |

### مثال‌ها

مثال:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### موارد مرتبط

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathBox](../imathbox)
* فضای نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->