---
title: MathBox
second_title: مرجع API Aspose.Sildes برای .NET
description: بسته‌بندی منطقی جعبه‌بندی عنصر ریاضی را مشخص می‌کند. به عنوان مثال، یک شیء جعبه‌شده می‌تواند به عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، به عنوان نقطهٔ شکست خط عمل کند یا به‌ گونه‌ای گروه‌بندی شود که اجازهٔ شکست خطوط درون آن داده نشود. به عنوان مثال، عملگر باید جعبه‌بندی شود تا از شکست خطوط جلوگیری شود.
type: docs
weight: 8630
url: /fa/aspose.slides.mathtext/mathbox/
---
## MathBox کلاس

جعبه‌بندی منطقی (بسته‌بندی) عنصر ریاضی را مشخص می‌کند. به عنوان مثال، یک شیء جعبه‌شده می‌تواند به عنوان یک شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، به عنوان نقطهٔ شکست خط عمل کند، یا به‌ گونه‌ای گروه‌بندی شود که اجازهٔ شکست خطوط درون آن داده نشود. به عنوان مثال، عملگر "==" باید جعبه‌بندی شود تا از شکست خطوط جلوگیری شود.

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
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | وقتی true ، این شبیه‌ساز عملگر به‌عنوان نقطهٔ تراز عمل می‌کند؛ یعنی نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن تراز شوند. پیش‌فرض: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | آرگومان پایه |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | تفاضل وقتی true ، جعبه به‌عنوان تفاضل عمل می‌کند (مثلاً 𝑑𝑥 در یک انتگرال‌گیری) و فاصلهٔ افقی مناسب برای تفاضل ریاضی دریافت می‌کند. پیش‌فرض: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | شکست صریح مشخص می‌کند آیا در شروع شیء Box خط شکسته وجود دارد یا خیر، به‌طوری که خط در شروع شیء جعبه شکسته شود. تعداد عملگر در خط قبلی متن ریاضی که به‌عنوان نقطهٔ تراز برای خط جاری متن ریاضی استفاده می‌شود را تعیین می‌کند. مقادیر ممکن: 1..255 پیش‌فرض: 0 (بدون شکست صریح) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | بدون شکست این ویژگی خاصیت «قابل شکست نیست» را برای جعبهٔ شیء مشخص می‌کند. وقتی true ، هیچ شکست خطی نمی‌تواند درون جعبه رخ دهد. این می‌تواند برای شبیه‌سازهای عملگری که از بیش از یک عملگر دودویی تشکیل شده‌اند مهم باشد. وقتی این عنصر مشخص نشده باشد، شکست‌ها می‌توانند داخل جعبه رخ دهند. پیش‌فرض: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | شبیه‌ساز عملگر. وقتی true ، جعبه و محتوای آن همانند یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را ارث می‌برند. این به این معنی است که، به عنوان مثال، کاراکتر می‌تواند به‌عنوان نقطهٔ شکست خط عمل کند و می‌تواند به عملگرهای دیگر تراز شود. شبیه‌سازهای عملگر غالباً زمانی استفاده می‌شوند که یک یا چند گلیف ترکیب شده و یک عملگر را تشکیل می‌دهند، مثل '=='. مقدار پیش‌فرض: false |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت ترکیبی (یک حرف در بالای این عنصر) تنظیم می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافی مشخص‌شده می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافی مشخص‌شده می‌گیرد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | یک کسر با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | یک کسر با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | کسر از نوع مشخص‌شده را با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | کسر از نوع مشخص‌شده را با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز می‌گیرد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | یک عنصر ریاضی را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از براکت کروی پایین در یک گروه قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند براکت کروی پایین یا سایر کاراکترها در یک گروه قرار می‌دهد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال بدون حدها را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را پیوست می‌کند و یک بلوک ریاضی تشکیل می‌دهد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را پیوست می‌کند و یک بلوک ریاضی تشکیل می‌دهد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-ary ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-ary ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک نوار در بالای این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشهٔ ریاضی با درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشهٔ ریاضی با درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | حد پایین را می‌گیرد |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | حد پایین را می‌گیرد |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | زیرنوشته ایجاد می‌کند |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | زیرنوشته ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | زیرنوشته و بالانوشته را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | زیرنوشته و بالانوشته را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | زیرنوشته و بالانوشته را در سمت راست ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | زیرنوشته و بالانوشته را در سمت راست ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | بالانوشته ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | بالانوشته ایجاد می‌کند |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالا را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالا را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبهٔ غیر‌نمایش (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های یک معادله یا نمونهٔ دیگری از متن ریاضی استفاده می‌شود. یک شیء جعبه‌شده می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، به‌عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکست خطوط درون آن داده نشود. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایهٔ عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک نوار در پایین این عنصر تنظیم می‌کند |

### مثال‌ها

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### موارد مرتبط

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathBox](../imathbox)
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->