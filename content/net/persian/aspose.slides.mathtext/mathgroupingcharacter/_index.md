---
title: MathGroupingCharacter
second_title: مرجع API Aspose.Sildes برای .NET
description: نماد گروه‌بندی را که بالای یا زیر یک عبارت قرار می‌گیرد، معمولاً برای برجسته‌سازی رابطه بین عناصر مشخص می‌کند
type: docs
weight: 8760
url: /fa/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter کلاس

نماد گروه‌بندی را که بالای یا زیر یک عبارت قرار می‌گیرد، مشخص می‌کند و معمولاً برای برجسته‌سازی رابطه بین عناصر استفاده می‌شود

```csharp
public sealed class MathGroupingCharacter : MathElementBase, IMathGroupingCharacter
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathGroupingCharacter](mathgroupingcharacter#constructor)(IMathElement) | یک نمونه جدید از کلاس MathGroupingCharacter را با نماد گروه‌بندی پیش‌فرض U+23DF (پرانتز کروی پایین) مقداردهی اولیه می‌کند |
| [MathGroupingCharacter](mathgroupingcharacter#constructor_1)(IMathElement, char, MathTopBotPositions, MathTopBotPositions) | یک نمونه جدید از کلاس MathGroupingCharacter را مقداردهی اولیه می‌کند |

## خصوصیات

| نام | توضیح |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathgroupingcharacter/base) { get; } | آرگومان پایه |
| [Character](../../aspose.slides.mathtext/mathgroupingcharacter/character) { get; set; } | نماد گروه‌بندی مقدار پیش‌فرض: U+23DF (پرانتز کروی پایین) |
| [Position](../../aspose.slides.mathtext/mathgroupingcharacter/position) { get; set; } | موقعیت نماد گروه‌بندی. پیش‌فرض: Bottom |
| [VerticalJustification](../../aspose.slides.mathtext/mathgroupingcharacter/verticaljustification) { get; set; } | تراز عمودی نماد گروه. هم‌راستایی شیء را نسبت به پایه خط مشخص می‌کند. به عنوان مثال، وقتی نماد گروه بالای شیء باشد، مقدار VerticalJustification برابر Top نشان می‌دهد که بالای شیء بر روی پایه خط قرار دارد؛ وقتی VerticalJustification برابر Bottom باشد، پایین شیء بر روی پایه خط قرار می‌گیرد. پیش‌فرض: Bottom برای Position=Top، و Top برای Position=Bottom |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت اکسنت (کاراکتری در بالای این عنصر) را تنظیم می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابعی را که این نمونه به عنوان آرگومان استفاده می‌کند، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابعی را که این نمونه به عنوان آرگومان استفاده می‌کند، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابعی را که این نمونه به عنوان آرگومان استفاده می‌کند، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابعی را که این نمونه به عنوان آرگومان و یک آرگومان اضافه مشخص‌شده استفاده می‌کند، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابعی را که این نمونه به عنوان آرگومان و یک آرگومان اضافه مشخص‌شده استفاده می‌کند، می‌گیرد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | کسر با این صورت و مخرج مشخص شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | کسر با این صورت و مخرج مشخص شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | کسر از نوع مشخص‌شده با این صورت و مخرج مشخص شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | کسر از نوع مشخص‌شده با این صورت و مخرج مشخص شده ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز قرار می‌دهد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | یک عنصر ریاضی را در کاراکترهای مشخص شده مانند پرانتز یا دیگر کاراکترها به عنوان قاب قرار می‌دهد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان که این نمونه به عنوان نام تابع استفاده می‌کند، می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان که این نمونه به عنوان نام تابع استفاده می‌کند، می‌گیرد |
| [GetChildren](../../aspose.slides.mathtext/mathgroupingcharacter/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از پرانتز کروی پایین در گروهی قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از نماد گروه‌بندی مانند پرانتز کروی پایین یا دیگر در گروهی قرار می‌دهد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال بدون حد را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را به هم می‌پیوندد و بلوک ریاضی تشکیل می‌دهد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را به هم می‌پیوندد و بلوک ریاضی تشکیل می‌دهد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-ary ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-ary ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | نوار در بالای این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشه ریاضی درجه داده‌شده از آرگومان مشخص‌شده را مشخص می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشه ریاضی درجه داده‌شده از آرگومان مشخص‌شده را مشخص می‌کند |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | حد پایین را می‌گیرد |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | حد پایین را می‌گیرد |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | زیرنویس می‌سازد |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | زیرنویس می‌سازد |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMMathElement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | بالانویس می‌سازد |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | بالانویس می‌سازد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالا را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالا را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبه‌مرز قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبه‌مرز قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبه غیر‌نمایشی (گروه‌بندی منطقی) که برای گروه‌بندی اجزای یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود، قرار می‌دهد. یک شیء جعبه‌بندی‌شده می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، به عنوان نقطه شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازه شکست خط درون آن داده نشود |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایه عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | نوار در پایین این عنصر تنظیم می‌کند |

## مثال‌ها

مثال:

```csharp
[C#]
MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

## مراجع

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathGroupingCharacter](../imathgroupingcharacter)
* فضای نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->