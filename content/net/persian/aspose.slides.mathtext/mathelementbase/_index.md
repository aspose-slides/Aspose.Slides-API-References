---
title: MathElementBase
second_title: Aspose.Sildes برای .NET مرجع API
description: کلاس پایه برای IMathElement با پیاده‌سازی برخی متدهایی که برای تمام کلاس‌های ارث‌برده مشترک هستند. فقط برای استفاده داخلی. کلاس ارث‌برده باید IMimeElement باشد.
type: docs
weight: 8680
url: /fa/aspose.slides.mathtext/mathelementbase/
---
## کلاس MathElementBase

کلاس پایه برای IMathElement با پیاده‌سازی برخی متدهایی که برای تمام کلاس‌های وارث مشترک هستند. فقط برای استفاده داخلی. کلاس وارث باید IMathElement باشد.

```csharp
public abstract class MathElementBase : IMathElement
```

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت شمایل (یک کاراکتر در بالای این عنصر) را تنظیم می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان و یک آرگومان اضافه مشخص می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان و یک آرگومان اضافه مشخص می‌گیرد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | کسر را با این صورت‌حاصل (numerator) و مخرج مشخص شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | کسر را با این صورت‌حاصل و مخرج مشخص شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | کسر از نوع مشخص شده را با این صورت‌حاصل و مخرج مشخص شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | کسر از نوع مشخص شده را با این صورت‌حاصل و مخرج مشخص شده ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | یک عنصر ریاضی را درون پرانتز قرار می‌دهد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | یک عنصر ریاضی را درون کاراکترهای مشخص شده (مانند پرانتز یا سایر کاراکترها) به عنوان قاب قرار می‌دهد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | تابعی از یک آرگومان را با این نمونه به عنوان نام تابع می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | تابعی از یک آرگومان را با این نمونه به عنوان نام تابع می‌گیرد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | این عنصر را در یک گروه قرار می‌دهد با استفاده از یک کروشهٔ پایین |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را در یک گروه قرار می‌دهد با استفاده از کاراکتر گروه‌بندی مانند کروشهٔ پایین یا دیگر |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | انتگرال را بدون حدود می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | متن ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-ary ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | یک عملگر N-ary ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک خط بالای این عنصر را تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | ریشه ریاضی از درجهٔ مشخص شده را از آرگومان مشخص شده تعیین می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | ریشه ریاضی از درجهٔ مشخص شده را از آرگومان مشخص شده تعیین می‌کند |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMathElement) | حد پایین را می‌گیرد |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | حد پایین را می‌گیرد |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMathElement) | زیرنویس ایجاد می‌کند |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | زیرنویس ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMathElement) | بالانویس ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | بالانویس ایجاد می‌کند |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMathElement) | حد بالا را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | حد بالا را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | این عنصر را در یک جعبهٔ حاشیه‌دار قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبهٔ حاشیه‌دار قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبهٔ غیر‌دیداری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر متن‌های ریاضی استفاده می‌شود. یک شیء جعبه‌دار می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز استفاده شود، به‌عنوان نقطهٔ شکست خط عمل کند یا به‌صورت گروه‌بندی شده باشد تا از شکست خط درون آن جلوگیری شود. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایهٔ عمودی قرار می‌گیرد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک خط در پایین این عنصر تنظیم می‌کند |

### موارد مرتبط

* interface [IMathElement](../imathelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->