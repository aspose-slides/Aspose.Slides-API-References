---
title: IMathElement
second_title: Aspose.Sildes برای .NET مرجع API
description: رابط پایه برای هر عنصر ریاضی مانند کسر، متن ریاضی، تابع، عبارت با چندین عنصر و غیره
type: docs
weight: 8230
url: /fa/aspose.slides.mathtext/imathelement/
---
## IMathElement رابط

رابط پایه برای هر عنصر ریاضی: کسر، متن ریاضی، تابع، عبارت با چندین عنصر و غیره

```csharp
public interface IMathElement
```

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | یک علامت اکسنت تنظیم می‌کند (یک کاراکتر در بالای این عنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | تابع مشخص‌شده از نوع MathFunctionsOfOneArgument را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی مشخص‌شده می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی مشخص‌شده می‌گیرد |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | یک کسر با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | یک کسر با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | کسر از نوع MathFractionTypes با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | کسر از نوع MathFractionTypes با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | یک عنصر ریاضی را در پرانتز می‌گیرد |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | این عنصر را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | تابعی از یک آرگومان می‌گیرد و این نمونه را به‌عنوان نام تابع استفاده می‌کند |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | تابعی از یک آرگومان می‌گیرد و این نمونه را به‌عنوان نام تابع استفاده می‌کند |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | این عنصر را در یک گروه با استفاده از کروشهٔ پایین قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را در یک گروه با استفاده از کاراکتر گروه‌بندی مانند کروشهٔ پایین یا کاراکتر دیگر قرار می‌دهد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | انتگرال را بدون حدود می‌گیرد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی شکل می‌دهد |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | یک متن ریاضی را می‌پیوندد و یک بلوک ریاضی شکل می‌دهد |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | عملگر N-تایی ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | عملگر N-تایی ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | یک بار بر بالای این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | ریشه ریاضی از درجه داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | ریشه ریاضی از درجه داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | حد پایین را می‌گیرد |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | حد پایین را می‌گیرد |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | زیرنویس ایجاد می‌کند |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | زیرنویس ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | بالانویس ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | بالانویس ایجاد می‌کند |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | حد بالا را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | حد بالا را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | این عنصر را در یک جعبه مرزی قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبه مرزی قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | این عنصر را در یک جعبه غیر‌قابل مشاهده (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود. یک شیء در جعبه می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، به‌عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازه شکست خط درون آن نباشد. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | در یک آرایهٔ عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | یک بار بر پایین این عنصر تنظیم می‌کند |

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### مراجع

* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->