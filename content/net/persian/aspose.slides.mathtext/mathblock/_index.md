---
title: MathBlock
second_title: Aspose.Sildes برای .NET مرجع API
description: یک نمونه از متن ریاضی که در داخل یک MathParagraph قرار دارد و در خط جداگانه‌ای آغاز می‌شود را مشخص می‌کند. تمام نواحی ریاضی شامل معادلات، عبارات، آرایه‌های معادلات یا عبارات و فرمول‌ها توسط math block نمایش داده می‌شوند.
type: docs
weight: 8590
url: /fa/aspose.slides.mathtext/mathblock/
---
## MathBlock کلاس

یک نمونه از متن ریاضی را که درون یک MathParagraph قرار دارد و در خط جداگانه‌ای آغاز می‌شود، مشخص می‌کند. تمام نواحی ریاضی، از جمله معادلات، عبارات، آرایه‌های معادلات یا عبارات، و فرمول‌ها توسط math block نمایش داده می‌شوند.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathBlock](mathblock#constructor)() | یک نمونه جدید از کلاس MathBlock را مقداردهی اولیه می‌کند. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | یک بلوک ریاضی جدید ایجاد می‌کند و عناصر مشخص‌شده را در آن قرار می‌دهد. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | یک بلوک ریاضی جدید ایجاد می‌کند و عنصر مشخص‌شده را در آن قرار می‌دهد. |

## خصوصیات

| نام | توضیح |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | تعداد عناصر ریاضی فرزندی که در مجموعه واقعاً موجود است را برمی‌گرداند. فقط-خواندنی Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | مقدار false را برمی‌گرداند زیرا مجموعه عناصر فرزند قابل تغییر است. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | عنصر IMathElement را در شاخص مشخص‌شده دریافت یا تنظیم می‌کند. |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت لهجه (یک کاراکتر در بالای این عنصر) را تنظیم می‌کند. |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | یک عنصر ریاضی را به انتهای مجموعه اضافه می‌کند. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان دریافت می‌کند. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان دریافت می‌کند. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان دریافت می‌کند. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافهٔ مشخص‌شده دریافت می‌کند. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافهٔ مشخص‌شده دریافت می‌کند. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | تمام عناصر را از مجموعه حذف می‌کند. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | تشخیص می‌دهد آیا مجموعه حاوی مقدار خاصی است یا خیر. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | به آرایهٔ مشخص‌شده کپی می‌کند. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | عناصر فرزند را با کاراکتر جداکننده (بدون براکت) تفکیک می‌کند. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | کسر با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | کسر با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | کسر از نوع مشخص‌شده با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | کسر از نوع مشخص‌شده با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز می‌گیرد. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | عناصر فرزند این بلوک را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | عناصر فرزند این بلوک را در کاراکترهای مشخص‌شده مانند پرانتز یا سایر کاراکترها به‌عنوان قاب می‌گیرد و با کاراکتر جداکننده تفکیک می‌کند. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع دریافت می‌کند. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع دریافت می‌کند. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | دریافت عناصر فرزند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از کروشهٔ پایین در یک گروه قرار می‌دهد. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از کاراکتر گروه‌بندی مانند کروشهٔ پایین یا کاراکتر دیگر در یک گروه قرار می‌دهد. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | شاخص یک عنصر ریاضی خاص را در مجموعه تعیین می‌کند. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | یک MathElement را در مجموعه در شاخص مشخص‌شده درج می‌کند. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال را بدون حد‌ها می‌گیرد. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | یک عنصر ریاضی را با این بلوک ریاضی می‌پیوندد. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | یک متن ریاضی را با این بلوک ریاضی می‌پیوندد. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | یک بلوک ریاضی دیگر را با این بلوک می‌پیوندد. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-آری ایجاد می‌کند. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-آری ایجاد می‌کند. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | نوار را در بالای این عنصر قرار می‌دهد. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشهٔ ریاضی از درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشهٔ ریاضی از درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | عنصر در شاخص مشخص‌شده از مجموعه را حذف می‌کند. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | حد پایین را می‌گیرد. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | حد پایین را می‌گیرد. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | زیرنویس ایجاد می‌کند. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | زیرنویس ایجاد می‌کند. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | بالانویس ایجاد می‌کند. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | بالانویس ایجاد می‌کند. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالا را می‌گیرد. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالا را می‌گیرد. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبهٔ غیر بصری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی اجزای یک معادله یا دیگر نمونه‌های متن ریاضی استفاده می‌شود. یک شیء جعبه‌دار می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز، به عنوان نقطهٔ شکست خط، یا به‌صورت گروه‌بندی شود به‌طوری که امکان شکست خط درون آن وجود نداشته باشد. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | عناصر فرزند را در یک آرایهٔ عمودی قرار می‌دهد. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | نوار را در پایین این عنصر قرار می‌دهد. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | محتویات این [`MathBlock`](../mathblock) را به صورت MathML ذخیره می‌کند. |

### مثال‌ها

مثال:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### مطالب مرتبط

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathBlock](../imathblock)
* فضای نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->