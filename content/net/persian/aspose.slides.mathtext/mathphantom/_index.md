---
title: MathPhantom
second_title: Aspose.Sildes برای مرجع API .NET
description: یک شیء ریاضی فانتوم ltmphantgt را نمایندگی می‌کند که طرح‌بندی عنصر فرزند خود را تحت تأثیر قرار می‌دهد بدون اینکه لزوماً آن را نمایش دهد. فانتوم می‌تواند عبارت پایه خود را مخفی کند در حالی که عرض، ارتفاع یا عمق آن را حفظ می‌کند تا فرمول‌ها را هم‌تراز یا فضا را رزرو کند. قابلیت مشاهده و رفتار هندسی توسط ویژگی‌هایی مانند Show، ZeroWid، ZeroAsc، ZeroDesc و Transp کنترل می‌شود.
type: docs
weight: 8940
url: /fa/aspose.slides.mathtext/mathphantom/
---
## کلاس MathPhantom

یک شیء ریاضی فانتوم (&lt;m:phant&gt;) را نمایندگی می‌کند که طرح‌بندی عنصر فرزند خود را تحت تأثیر قرار می‌دهد بدون اینکه لزوماً آن را نمایش دهد. فانتوم می‌تواند عبارت پایه خود را مخفی کند در حالی که عرض، ارتفاع یا عمق آن را حفظ می‌کند تا فرمول‌ها را هم‌تراز یا فضا را رزرو کند. قابلیت مشاهده و رفتار هندسی توسط ویژگی‌هایی مانند Show، ZeroWid، ZeroAsc، ZeroDesc و Transp کنترل می‌شود.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## سازندگان

| نام | توضیح |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | یک نمونهٔ جدید از کلاس [`MathPhantom`](../mathphantom) را با استفاده از عنصر ریاضی پایهٔ مشخص ایجاد می‌کند. |

## خصوصیات

| نام | توضیح |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | آرگومان پایه |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | مقدار نشان‌دهندهٔ این که آیا عنصر پایه نمایش داده می‌شود را دریافت یا تنظیم می‌کند. |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | مقدار نشان‌دهندهٔ این که آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف است را دریافت یا تنظیم می‌کند. |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | مقدار نشان‌دهندهٔ این که آیا صعود (ارتفاع بالای خط پایه) عنصر پایه به صفر درنظر گرفته شود را دریافت یا تنظیم می‌کند. |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | مقدار نشان‌دهندهٔ این که آیا نزول (عمق زیر خط پایه) عنصر پایه به صفر درنظر گرفته شود را دریافت یا تنظیم می‌کند. |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | مقدار نشان‌دهندهٔ این که آیا عرض عنصر پایه به صفر درنظر گرفته شود را دریافت یا تنظیم می‌کند. |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت تأکید (کاراکتر در بالای این عنصر) تنظیم می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافهٔ مشخص‌شده می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخصی را با استفاده از این نمونه به‌عنوان آرگومان و آرگومان اضافهٔ مشخص‌شده می‌گیرد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | یک کسر با این صورت‌حاصل و مخرج مشخص‌شده می‌سازد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | یک کسر با این صورت‌حاصل و مخرج مشخص‌شده می‌سازد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | کسر از نوع مشخص‌شده را با این صورت‌حاصل و مخرج مشخص‌شده می‌سازد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | کسر از نوع مشخص‌شده را با این صورت‌حاصل و مخرج مشخص‌شده می‌سازد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز می‌گیرد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | یک عنصر ریاضی را با کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان چارچوب می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با یک براکت پهنی در کف به یک گروه می‌گذارد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با یک کاراکتر گروه‌بندی مانند براکت پهنی در کف یا کاراکتر دیگر به یک گروه می‌گذارد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال را بدون حدود می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را متصل کرده و بلوک ریاضی شکل می‌دهد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را متصل کرده و بلوک ریاضی شکل می‌دهد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-ary می‌سازد |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-ary می‌سازد |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک خط در بالای این عنصر قرار می‌دهد |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشهٔ ریاضی به توان مشخص‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشهٔ ریاضی به توان مشخص‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | حد پایین را می‌گیرد |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | حد پایین را می‌گیرد |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | زیرنویس می‌سازد |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | زیرنویس می‌سازد |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت چپ می‌سازد |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | زیرنویس و بالانویس را در سمت چپ می‌سازد |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت راست می‌سازد |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | زیرنویس و بالانویس را در سمت راست می‌سازد |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | بالانویس می‌سازد |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | بالانویس می‌سازد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالا را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالا را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبه مرزی می‌گذارد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبه مرزی می‌گذارد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبهٔ غیر‌نمایشی (گروه‌بندی منطقی) می‌گذارد که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود. یک شیء جعبه‌شده می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز، به‌عنوان نقطهٔ شکست خط یا به‌عنوان گروهی که اجازهٔ شکست خط درون آن را نمی‌دهد، عمل کند. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایهٔ عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک خط در پایین این عنصر قرار می‌دهد |

### مثال‌ها

مثال:

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // مخفی کردن محتوا
phantom.ZeroWidth = false;     // حفظ عرض
```

### منابع مرتبط

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathPhantom](../imathphantom)
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->