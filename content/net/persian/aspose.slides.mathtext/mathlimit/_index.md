---
title: MathLimit
second_title: مرجع API Aspose.Sildes برای .NET
description: آبجکت Limit را که شامل متنی بر روی خط پایه و متنی با اندازهٔ کوچک‌تر بلافاصله بالای یا پایین آن است، مشخص می‌کند.
type: docs
weight: 8820
url: /fa/aspose.slides.mathtext/mathlimit/
---
## کلاس MathLimit

آبجکت Limit را مشخص می‌کند که شامل متن روی خط پایه و متن با اندازهٔ کوچک‌تر بلافاصله بالای یا پایین آن است.

```csharp
public sealed class MathLimit : MathElementBase, IMathLimit
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathLimit](mathlimit#constructor)(IMathElement, IMathElement) | یک نمونهٔ جدید از کلاس MathLimit را با حد پایین مقداردهی اولیه می‌کند |
| [MathLimit](mathlimit#constructor_1)(IMathElement, IMathElement, bool) | یک نمونهٔ جدید از کلاس MathLimit را مقداردهی اولیه می‌کند |

## خصوصیات

| نام | توضیح |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathlimit/base) { get; } | آرگومان پایه |
| [Limit](../../aspose.slides.mathtext/mathlimit/limit) { get; } | آرگومان حد |
| [UpperLimit](../../aspose.slides.mathtext/mathlimit/upperlimit) { get; set; } | حد بالایی یا پایینی را مشخص می‌کند |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت اکسنت تنظیم می‌کند (یک کاراکتر در بالای این عنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخص‌شده‌ای را که این نمونه به عنوان آرگومان استفاده می‌کند، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخص‌شده‌ای را که این نمونه به عنوان آرگومان استفاده می‌کند، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخص‌شده‌ای را که این نمونه به عنوان آرگومان استفاده می‌کند، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص‌شده‌ای را که این نمونه به عنوان آرگومان و آرگومان اضافی مشخص‌شده استفاده می‌کند، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخص‌شده‌ای را که این نمونه به عنوان آرگومان و آرگومان اضافی مشخص‌شده استفاده می‌کند، می‌گیرد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | یک کسر با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | یک کسر با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | یک کسر از نوع مشخص‌شده با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | یک کسر از نوع مشخص‌شده با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز می‌گیرد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | یک عنصر ریاضی را در کاراکترهای مشخص‌شده مانند پرانتز یا سایر کاراکترها به‌عنوان قاب می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | یک تابع از یک آرگومان که این نمونه به عنوان نام تابع استفاده می‌کند، می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | یک تابع از یک آرگومان که این نمونه به عنوان نام تابع استفاده می‌کند، می‌گیرد |
| [GetChildren](../../aspose.slides.mathtext/mathlimit/getchildren)() | دریافت عناصر فرزندان |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از کروشهٔ پایین در یک گروه قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند کروشهٔ پایین یا کاراکتر دیگری در یک گروه قرار می‌دهد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال بدون حدها را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را ترکیب کرده و یک بلوک ریاضی تشکیل می‌دهد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را ترکیب کرده و یک بلوک ریاضی تشکیل می‌دهد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-آری ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-آری ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک خط در بالای این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشه ریاضی درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشه ریاضی درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبه‌مرزی قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبه‌مرزی قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبه غیررؤية (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر متن‌های ریاضی استفاده می‌شود. یک شیء جعبه‌دار می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز، به‌عنوان نقطهٔ شکست خط، یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط در داخل آن نباشد. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در آرایهٔ عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک خط در پایین این عنصر تنظیم می‌کند |

### مثال‌ها

مثال:

```csharp
[C#]
MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("𝑛→∞"));
```

### مراجع

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathLimit](../imathlimit)
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->