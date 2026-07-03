---
title: MathSuperscriptElement
second_title: مرجع API Aspose.Sildes برای .NET
description: شی superscript را مشخص می‌کند که از یک پایه و یک superscript با اندازهٔ کوچک‌تر که بالای آن و به سمت راست قرار دارد، تشکیل شده است
type: docs
weight: 9020
url: /fa/aspose.slides.mathtext/mathsuperscriptelement/
---
## MathSuperscriptElement کلاس

شی superscript را مشخص می‌کند که از یک پایه و یک superscript با اندازهٔ کوچکتر که بالای آن و به سمت راست قرار دارد، تشکیل شده است.

```csharp
public sealed class MathSuperscriptElement : BaseScript, IMathSuperscriptElement
```

## سازنده‌ها

| Name | Description |
| --- | --- |
| [MathSuperscriptElement](mathsuperscriptelement)(IMathElement, IMathElement) | یک نمونهٔ جدید از کلاس MathSuperscriptElement را مقداردهی اولیه می‌کند. |

## خصوصیات

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | آرگومان پایه |
| [Superscript](../../aspose.slides.mathtext/mathsuperscriptelement/superscript) { get; } | فوق‌نویس |

## متدها

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت لهجه تنظیم می‌کند (یک کاراکتر در بالای این عنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | یک تابع مشخص را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | یک تابع مشخص را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | یک تابع مشخص را می‌گیرد که این نمونه به‌عنوان آرگومان استفاده می‌شود |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | یک تابع مشخص را می‌گیرد که این نمونه به‌عنوان آرگومان و آرگومان اضافهٔ مشخص شده را دارد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | یک تابع مشخص را می‌گیرد که این نمونه به‌عنوان آرگومان و آرگومان اضافهٔ مشخص شده را دارد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | یک کسر با صورت این عنصر و مخرج مشخص ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | یک کسر با صورت این عنصر و مخرج مشخص ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | کسر از نوع مشخص با صورت این عنصر و مخرج مشخص ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | کسر از نوع مشخص با صورت این عنصر و مخرج مشخص ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز می‌گیرد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | یک عنصر ریاضی را در کاراکترهای مشخص شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان می‌گیرد که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان می‌گیرد که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| [GetChildren](../../aspose.slides.mathtext/mathsuperscriptelement/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را در گروهی با استفاده از براکت پایین می‌گذارد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را در گروهی با استفاده از کاراکتر گروه‌بندی مانند براکت پایین یا کاراکتر دیگر می‌گذارد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال را بدون حدود می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را می‌پیوندد و بلوک ریاضی تشکیل می‌دهد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را می‌پیوندد و بلوک ریاضی تشکیل می‌دهد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-ary ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-ary ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک خط افقی در بالای این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشهٔ ریاضی درجهٔ داده شده را از آرگومان مشخص شده تعیین می‌کند. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشهٔ ریاضی درجهٔ داده شده را از آرگومان مشخص شده تعیین می‌کند. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | حد پایین را می‌گیرد |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | حد پایین را می‌گیرد |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | زیرنویس ایجاد می‌کند |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | زیرنویس ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | زیرنویس و فوق‌نویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | زیرنویس و فوق‌نویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | زیرنویس و فوق‌نویس را در سمت راست ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | زیرنویس و فوق‌نویس را در سمت راست ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | فوق‌نویس ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | فوق‌نویس ایجاد می‌کند |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالا را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالا را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبهٔ حاشیه‌ای قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبهٔ حاشیه‌ای قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبهٔ غیر‌مشهود (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر متن‌های ریاضی استفاده می‌شود. یک شیء جعبه‌دار می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز، به‌عنوان نقطهٔ شکست خط، یا به‌صورت گروه‌بندی شده باشد تا از شکستن خط درون آن جلوگیری کند. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایهٔ عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک خط افقی در پایین این عنصر تنظیم می‌کند |

### مثال‌ها

مثال:

```csharp
[C#]
MathSuperscriptElement superscriptElement = new MathematicalText("N").SetSuperscript("i");
```

### موارد مرتبط

* کلاس [BaseScript](../basescript)
* رابط [IMathSuperscriptElement](../imathsuperscriptelement)
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->