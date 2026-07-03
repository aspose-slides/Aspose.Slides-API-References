---
title: MathArray
second_title: مرجع API Aspose.Sildes برای .NET
description: یک آرایه عمودی از معادلات یا هر شیء ریاضی را مشخص می‌کند
type: docs
weight: 8550
url: /fa/aspose.slides.mathtext/matharray/
---
## MathArray کلاس

یک آرایه عمودی از معادلات یا هر شیء ریاضی را مشخص می‌کند

```csharp
public sealed class MathArray : MathElementBase, IMathArray
```

## سازنده‌ها

| Name | Description |
| --- | --- |
| [MathArray](matharray#constructor_1)(IEnumerable&lt;IMathElement&gt;) | یک آرایه ریاضی ایجاد می‌کند و عناصر مشخص‌شده را در آن قرار می‌دهد |
| [MathArray](matharray#constructor)(IMathElement) | یک آرایه ریاضی ایجاد می‌کند و عنصر مشخص‌شده را در آن قرار می‌دهد |

## ویژگی‌ها

| Name | Description |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/matharray/arguments) { get; } | مجموعه‌ای از آیتم‌های آرایه |
| [BaseJustification](../../aspose.slides.mathtext/matharray/basejustification) { get; set; } | ترازبندی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز شیء آرایه هم‌تراز شود. مقدار پیش‌فرض: Center |
| [MaximumDistribution](../../aspose.slides.mathtext/matharray/maximumdistribution) { get; set; } | توزیع حداکثری. هنگامی که مقدار true باشد، آرایه به حداکثر پهنای عنصر حاوی (صفحه، ستون، سلول و غیره) فاصله‌گذاری می‌شود. |
| [ObjectDistribution](../../aspose.slides.mathtext/matharray/objectdistribution) { get; set; } | توزیع شیء. هنگامی که مقدار true باشد، محتویات آرایه به حداکثر پهنای شیء آرایه فاصله‌گذاری می‌شوند. |
| [RowSpacing](../../aspose.slides.mathtext/matharray/rowspacing) { get; set; } | فاصله بین ردیف‌های آرایه. این ویژگی فقط زمانی که RowSpacingRule روی 3 تنظیم شده باشد، مورد استفاده قرار می‌گیرد؛ در این حالت واحد اندازه‌گیری نقاط است یا در حالت Multiple واحد اندازه‌گیری نیم‌خط‌ها. مقدار پیش‌فرض: 0 |
| [RowSpacingRule](../../aspose.slides.mathtext/matharray/rowspacingrule) { get; set; } | نوع فاصله عمودی بین عناصر آرایه. مقدار پیش‌فرض: SingleLineGap |

## متدها

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت صدا (یک کاراکتر در بالای این عنصر) تنظیم می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان و یک آرگومان اضافی مشخص می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان و یک آرگومان اضافی مشخص می‌گیرد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | یک کسر با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | یک کسر با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | یک کسر از نوع مشخص‌شده با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | یک کسر از نوع مشخص‌شده با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز می‌گیرد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | یک عنصر ریاضی را در کاراکترهای مشخص‌شده مانند پرانتز یا سایر کاراکترها به‌عنوان چارچوب می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | یک تابع از آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | یک تابع از آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد |
| [GetChildren](../../aspose.slides.mathtext/matharray/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از یک پرانتز محکم پایین در یک گروه قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند پرانتز محکم پایین یا دیگر، در یک گروه قرار می‌دهد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال بدون حدود را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | یک متن ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-ary ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-ary ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک خط افقی بالای این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشه ریاضی با درجه داده‌شده از آرگومان مشخص‌شده را تعیین می‌کند. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشه ریاضی با درجه داده‌شده از آرگومان مشخص‌شده را تعیین می‌کند. |
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
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالا را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالا را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبه‌حاشیه‌ای قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبه‌حاشیه‌ای قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبه غیرقابل مشاهده (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی اجزای یک معادله یا سایر متون ریاضی استفاده می‌شود. یک شیء جعبه‌ای می‌تواند (به‌عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطه هم‌ترازی عمل کند، به‌عنوان نقطه شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازه شکست خط درون آن نشود. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایه عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک خط افقی در پایین این عنصر تنظیم می‌کند |

### مثال‌ها

مثال:

```csharp
[C#]
MathArray mathArray = new MathArray(new MathematicalText("item1"));
```

### مراجع

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathArray](../imatharray)
* فضای نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->