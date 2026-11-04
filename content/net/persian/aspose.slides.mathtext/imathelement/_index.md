---
title: IMathElement
second_title: مرجع API Aspose.Sildes برای .NET
description: رابط پایه هر عنصر ریاضی: کسر، متن ریاضی، تابع، عبارت با چندین عنصر و غیره
type: docs
weight: 8250
url: /fa/aspose.slides.mathtext/imathelement/
---
## رابط IMathElement

رابط پایه هر عنصر ریاضی: کسر، متن ریاضی، تابع، عبارت با چندین عنصر و غیره

```csharp
public interface IMathElement
```

## متدها

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | یک علامت تلفظ را تنظیم می‌کند (یک کاراکتر در بالای این عنصر) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | تابعی مشخص را که این نمونه را به عنوان آرگومان می‌گیرد، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | تابعی مشخص را که این نمونه را به عنوان آرگومان می‌گیرد، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | تابعی مشخص را که این نمونه را به عنوان آرگومان می‌گیرد، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | تابعی مشخص را که این نمونه را به عنوان آرگومان و یک آرگومان اضافه مشخص می‌گیرد، می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | تابعی مشخص را که این نمونه را به عنوان آرگومان و یک آرگومان اضافه مشخص می‌گیرد، می‌گیرد |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | کسر را با این صورت و مخرج مشخص ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | کسر را با این صورت و مخرج مشخص ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | کسر از نوع مشخص شده را با این صورت و مخرج مشخص ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | کسر از نوع مشخص شده را با این صورت و مخرج مشخص ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | یک عنصر ریاضی را در پرانتز قرار می‌دهد |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | این عنصر را در کاراکترهای مشخص شده مانند پرانتز یا کاراکترهای دیگر به عنوان قاب قرار می‌دهد |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | تابعی از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | تابعی از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌شود |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | دریافت عناصر فرزند |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | این عنصر را در یک گروه با استفاده از براکت منحنی پایین قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را در یک گروه با استفاده از کاراکتر گروه‌بند مانند براکت منحنی پایین یا دیگری قرار می‌دهد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | انتگرال را بدون حدها می‌گیرد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | یک عنصر ریاضی را ملحق می‌کند و بلوک ریاضی ایجاد می‌کند |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | متن ریاضی را ملحق می‌کند و بلوک ریاضی تشکیل می‌دهد |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک N-ary operator ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | یک N-ary operator ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | نوار در بالای این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | ریشه ریاضی از درجه داده شده را از آرگومان مشخص می‌کند |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | ریشه ریاضی از درجه داده شده را از آرگومان مشخص می‌کند |
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
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | حد بالایی را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | حد بالایی را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | این عنصر را در یک جعبه مرزی قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبه مرزی قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | این عنصر را در یک جعبه غیر بصری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر متن‌های ریاضی استفاده می‌شود. یک شیء جعبه‌ای می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز، به عنوان نقطه شکست خط، یا به گونه‌ای گروه‌بندی شود که اجازه شکست خط درون آن را ندهد. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | در یک آرایه عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | نوار در پایین این عنصر تنظیم می‌کند |

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### مراجع

* فضای نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->