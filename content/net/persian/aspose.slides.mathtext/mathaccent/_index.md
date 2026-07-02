---
title: MathAccent
second_title: Aspose.Sildes برای .NET مرجع API
description: عملکرد اکسنت را که از یک پایه و یک علامت ترکیبی اعراب تشکیل شده است مشخص می‌کند. مثال: ́
type: docs
weight: 8530
url: /fa/aspose.slides.mathtext/mathaccent/
---
## کلاس MathAccent

عملکرد اکسنت را مشخص می‌کند که شامل یک پایه و یک علامت ترکیبی اعراب است مثال: 𝑎́

```csharp
public sealed class MathAccent : MathElementBase, IMathAccent
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathAccent](mathaccent#constructor)(IMathElement) | یک اکسنت ریاضی ایجاد می‌کند که بر روی یک عنصر ریاضی مشخص اعمال می‌شود و مقدار پیش‌فرض کاراکتر اکسنت را دارد |
| [MathAccent](mathaccent#constructor_1)(IMathElement, char) | یک اکسنت ریاضی ایجاد می‌کند که بر روی یک عنصر ریاضی مشخص اعمال می‌شود |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathaccent/base) { get; } | آرگومانی که اکسنت به آن اعمال شده است |
| [Character](../../aspose.slides.mathtext/mathaccent/character) { get; set; } | کاراکتر اکسنت مقدار باید در بازه (U+0300–U+036F) یا (U+20D0–U+20EF) باشد مقدار پیش‌فرض: ترکیب‌گر کشیده (U+0302) |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت اکسنت تنظیم می‌کند (یک کاراکتر در بالای این عنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابعی مشخص می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابعی مشخص می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابعی مشخص می‌گیرد که این نمونه به عنوان آرگومان استفاده می‌شود |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابعی مشخص می‌گیرد که این نمونه به عنوان آرگومان و یک آرگومان اضافی مشخص استفاده می‌شود |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابعی مشخص می‌گیرد که این نمونه به عنوان آرگومان و یک آرگومان اضافی مشخص استفاده می‌شود |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | کسر با صورت این و مخرج مشخص ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | کسر با صورت این و مخرج مشخص ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | کسر از نوع مشخص‌شده‌ای را با این صورت و مخرج مشخص ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | کسر از نوع مشخص‌شده‌ای را با این صورت و مخرج مشخص ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را داخل پرانتز می‌گیرد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | یک عنصر ریاضی را با کاراکترهای مشخصی مانند پرانتز یا سایر کاراکترها در قاب می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود |
| [GetChildren](../../aspose.slides.mathtext/mathaccent/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از براکت‌های پایین در یک گروه قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند براکت پایین یا سایر کاراکترها در گروهی قرار می‌دهد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال بدون حد را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را ترکیب می‌کند و بلوک ریاضی ایجاد می‌کند |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را ترکیب می‌کند و بلوک ریاضی می‌سازد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | عملگر N-ary ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | عملگر N-ary ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک نوار در بالای این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشه ریاضی درجهٔ داده‌شده را از آرگومان مشخص تعیین می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشه ریاضی درجهٔ داده‌شده را از آرگومان مشخص تعیین می‌کند |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبهٔ غیر قابل مشاهده (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی اجزای یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود. یک شیء جعبه‌ای می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، به عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که از ایجاد شکست خط داخل آن جلوگیری شود. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایهٔ عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک نوار در پایین این عنصر تنظیم می‌کند |

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("x");
MathAccent accent = new MathAccent(baseElement, '~');
```

### موارد مرتبط

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathAccent](../imathaccent)
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->