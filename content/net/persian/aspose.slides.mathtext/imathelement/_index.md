---
title: IMathElement
second_title: Aspose.Sildes برای مرجع API .NET
description: رابط پایهٔ هر عنصر ریاضی شامل کسر، متن ریاضی، تابع، عبارت با چندین عنصر و غیره
type: docs
weight: 8230
url: /fa/aspose.slides.mathtext/imathelement/
---
## IMathElement رابط

رابط پایه هر عنصر ریاضی: کسر، متن ریاضی، تابع، عبارت با چندین عنصر و غیره

```csharp
public interface IMathElement
```

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | یک علامت له‌گذاری تنظیم می‌کند (یک کاراکتر در بالای این عنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | تابع مشخص‌شده‌ای را که این نمونه را به عنوان آرگومان استفاده می‌کند، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | تابع مشخص‌شده‌ای را که این نمونه را به عنوان آرگومان استفاده می‌کند، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | تابع مشخص‌شده‌ای را که این نمونه را به عنوان آرگومان استفاده می‌کند، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص‌شده‌ای را که این نمونه را به عنوان آرگومان استفاده می‌کند و آرگومان اضافی مشخص را می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | تابع مشخص‌شده‌ای را که این نمونه را به عنوان آرگومان استفاده می‌کند و آرگومان اضافی مشخص را می‌گیرد |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | یک کسر را با این صورت و مخرج مشخص می‌سازد |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | یک کسر را با این صورت و مخرج مشخص می‌سازد |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | کسر از نوع مشخص را با این صورت و مخرج مشخص می‌سازد |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | کسر از نوع مشخص را با این صورت و مخرج مشخص می‌سازد |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | یک عنصر ریاضی را در پرانتز می‌گیرد |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | این عنصر را در کاراکترهای مشخص شده مانند پرانتز یا سایر کاراکترها به عنوان چارچوب می‌پوشاند |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | تابعی از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | تابعی از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | این عنصر را با استفاده از آکولاد پایین در یک گروه می‌گذارد |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند آکولاد پایین یا کاراکتر دیگر در یک گروه می‌گذارد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | انتگرال بدون حدها را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی می‌سازد |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | متن ریاضی را می‌پیوندد و یک بلوک ریاضی می‌سازد |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMMathElement, IMathElement) | یک عملگر N-آری ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | یک عملگر N-آری ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | یک خط افقی در بالای این عنصر قرار می‌دهد |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | ریشه ریاضی به درجه داده‌شده را از آرگومان مشخص تعیین می‌کند |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | ریشه ریاضی به درجه داده‌شده را از آرگومان مشخص تعیین می‌کند |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | حد پایین را می‌گیرد |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | حد پایین را می‌گیرد |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | پایین‌نویس می‌سازد |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | پایین‌نویس می‌سازد |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | پایین‌نویس و بالانویس را در سمت چپ می‌سازد |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | پایین‌نویس و بالانویس را در سمت چپ می‌سازد |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | پایین‌نویس و بالانویس را در سمت راست می‌سازد |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | پایین‌نویس و بالانویس را در سمت راست می‌سازد |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | بالانویس می‌سازد |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | بالانویس می‌سازد |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | حد بالا را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | حد بالا را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | این عنصر را در یک جعبه‌مرزی قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبه‌مرزی قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | این عنصر را در یک جعبه غیر‌دیداری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی اجزای یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود. یک شیء جعبه‌ای می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطه هم‌ترازی عمل کند، به عنوان نقطه قطع خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ قطع خط درون آن داده نشود. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | یک آرایهٔ عمودی می‌گذارد |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | یک خط افقی در پایین این عنصر قرار می‌دهد |

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### موارد مرتبط

* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->