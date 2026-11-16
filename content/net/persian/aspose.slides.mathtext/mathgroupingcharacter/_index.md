---
title: MathGroupingCharacter
second_title: Aspose.Sildes برای .NET مرجع API
description: نماد گروه‌بندی را که بالای یا پایین یک عبارت قرار می‌گیرد، معمولاً برای برجسته‌سازی رابطه بین عناصر مشخص می‌کند
type: docs
weight: 8780
url: /fa/aspose.slides.mathtext/mathgroupingcharacter/
---
## کلاس MathGroupingCharacter

نماد گروه‌بندی را که بالای یا پایین یک عبارت قرار می‌گیرد، معمولاً برای برجسته‌سازی رابطه بین عناصر مشخص می‌کند

```csharp
public sealed class MathGroupingCharacter : MathElementBase, IMathGroupingCharacter
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathGroupingCharacter](mathgroupingcharacter#constructor)(IMathElement) | یک نمونه جدید از کلاس MathGroupingCharacter را با نماد گروه‌بندی پیش‌فرض U+23DF (کروشهٔ پایین) مقداردهی اولیه می‌کند |
| [MathGroupingCharacter](mathgroupingcharacter#constructor_1)(IMathElement, char, MathTopBotPositions, MathTopBotPositions) | یک نمونه جدید از کلاس MathGroupingCharacter را مقداردهی اولیه می‌کند |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathgroupingcharacter/base) { get; } | آرگومان پایه |
| [Character](../../aspose.slides.mathtext/mathgroupingcharacter/character) { get; set; } | نماد گروه‌بندی. مقدار پیش‌فرض: U+23DF (کروشهٔ پایین) |
| [Position](../../aspose.slides.mathtext/mathgroupingcharacter/position) { get; set; } | موقعیت نماد گروه‌بندی. مقدار پیش‌فرض: پایین |
| [VerticalJustification](../../aspose.slides.mathtext/mathgroupingcharacter/verticaljustification) { get; set; } | ترازبندی عمودی نماد گروه. تعیین می‌کند که شیء نسبت به خط پایه چگونه تراز شود. برای مثال، وقتی نماد گروه بالای شیء باشد، ترازبندی عمودی Top نشان می‌دهد که بالای شیء بر روی خط پایه قرار می‌گیرد؛ وقتی ترازبندی عمودی Bottom باشد، پایین شیء بر روی خط پایه است. مقدار پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت لحن (یک کاراکتر در بالای این عنصر) تنظیم می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان دریافت می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان دریافت می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان دریافت می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافهٔ مشخص دریافت می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافهٔ مشخص دریافت می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | کسر را با این صورت‌حساب و مخرج مشخص ساخته می‌شود |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | کسر را با این صورت‌حساب و مخرج مشخص ساخته می‌شود |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | کسر از نوع مشخص را با این صورت‌حساب و مخرج مشخص ساخته می‌شود |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | کسر از نوع مشخص را با این صورت‌حساب و مخرج مشخص ساخته می‌شود |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | عنصر ریاضی را در پرانتز می‌گیرد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | عنصر ریاضی را در کاراکترهای مشخص شده مانند پرانتز یا سایر کاراکترها به عنوان قاب می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی با یک آرگومان را با استفاده از این نمونه به عنوان نام تابع دریافت می‌کند |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی با یک آرگومان را با استفاده از این نمونه به عنوان نام تابع دریافت می‌کند |
| [GetChildren](../../aspose.slides.mathtext/mathgroupingcharacter/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از یک کروشهٔ پایین در یک گروه قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از نماد گروه‌بندی مانند کروشهٔ پایین یا دیگر نمادها در یک گروه قرار می‌دهد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال را بدون حدها دریافت می‌کند |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را دریافت می‌کند |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را دریافت می‌کند |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را دریافت می‌کند |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را دریافت می‌کند |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را متصل کرده و بلوک ریاضی تشکیل می‌دهد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را متصل کرده و بلوک ریاضی تشکیل می‌دهد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | عملگر N-ary را ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | عملگر N-ary را ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | میله‌ای در بالای این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشهٔ ریاضی از درجهٔ داده‌شده را با آرگومان مشخص شده تعیین می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشهٔ ریاضی از درجهٔ داده‌شده را با آرگومان مشخص شده تعیین می‌کند |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | حد پایین را دریافت می‌کند |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | حد پایین را دریافت می‌کند |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | زیرنویس ایجاد می‌کند |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | زیرنویس ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | بالانویس ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | بالانویس ایجاد می‌کند |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالا را دریافت می‌کند |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالا را دریافت می‌کند |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبهٔ غیر بصری (گروه‌بندی منطقی) که برای گروه‌بندی مؤلفه‌های یک معادله یا متن ریاضی استفاده می‌شود، قرار می‌دهد. یک شیء داخل جعبه می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، به عنوان نقطهٔ قطع خط عمل کند یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط درون آن داده نشود. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایهٔ عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | میله‌ای در پایین این عنصر تنظیم می‌کند |

### مثال‌ها

مثال:

```csharp
[C#]
MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

### موارد مرتبط

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathGroupingCharacter](../imathgroupingcharacter)
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->