---
title: MathematicalText
second_title: Aspose.Sildes برای .NET مرجع API
description: متن ریاضی
type: docs
weight: 9060
url: /fa/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText کلاس

Mathematical text

```csharp
public sealed class MathematicalText : MathElementBase, IMathematicalText
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathematicalText](mathematicaltext#constructor)() | سازنده پیش‌فرض (ایجاد مقدار String.Empty) |
| [MathematicalText](mathematicaltext#constructor_1)(char) | MathText را با یک نماد واحد ایجاد می‌کند |
| [MathematicalText](mathematicaltext#constructor_2)(string) | MathematicalText را از متن ایجاد می‌کند |
| [MathematicalText](mathematicaltext#constructor_3)(string, IPortionFormat) | MathematicalText را از متن و تنظیمات قالب ایجاد می‌کند |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Format](../../aspose.slides.mathtext/mathematicaltext/format) { get; } | ویژگی‌های قالب‌بندی متن |
| [Value](../../aspose.slides.mathtext/mathematicaltext/value) { get; set; } | مقدار متن |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | علامت تجمعی را تنظیم می‌کند (یک کاراکتر در بالای این عنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان اصلی و آرگومان اضافی مشخص‌شده می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخص شده را با استفاده از این نمونه به‌عنوان آرگومان اصلی و آرگومان اضافی (string) می‌گیرد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | کسر را با این صورت‌عدد و مخرج مشخص ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | کسر را با این صورت‌عدد (string) و مخرج مشخص ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | کسر از نوع مشخص‌شده را با این صورت‌عدد و مخرج مشخص می‌سازد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | کسر از نوع مشخص‌شده را با این صورت‌عدد (string) و مخرج مشخص می‌سازد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز می‌گیرد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | عنصر ریاضی را در کاراکترهای مشخص‌شده (مانند پرانتز یا کاراکترهای دیگر) به‌صورت قاب می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان می‌گیرد به‌طوری که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان می‌گیرد به‌طوری که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از کروشه‌ پایین در یک گروه می‌گذارد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از یک کاراکتر گروه‌بندی (مانند کروشه‌ پایین یا دیگر) در یک گروه می‌گذارد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال را بدون حدود می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را ترکیب می‌کند و یک بلوک ریاضی ایجاد می‌سازد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را ترکیب می‌کند و یک بلوک ریاضی می‌سازد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-ary ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-ary ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | نوار را در بالای این عنصر قرار می‌دهد |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشه ریاضی با درجه داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشه ریاضی با درجه داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | حد پایین را می‌گیرد |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | حد پایین را می‌گیرد |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | زیرنویس می‌سازد |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | زیرنویس می‌سازد |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | بالانویس می‌سازد |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | بالانویس می‌سازد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالایی را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالایی را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در جعبه‌ای حاوی حاشیه قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در جعبه‌ای با حاشیه قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبه غیرقابل نمایش (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی اجزای یک معادله یا سایر متن‌های ریاضی استفاده می‌شود. یک شیء جعبه‌دار می‌تواند (به‌عنوان مثال) به‌ عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، یا به‌عنوان نقطه شکست خط، یا به‌ گونه‌ای گروه شود که اجازه شکست خط درون آن را ندهد. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایه عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | نوار را در پایین این عنصر قرار می‌دهد |

### مثال‌ها

مثال:

```csharp
[C#]
MathematicalText mathText = new MathematicalText("x+y");
```

### موارد مرتبط

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathematicalText](../imathematicaltext)
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->