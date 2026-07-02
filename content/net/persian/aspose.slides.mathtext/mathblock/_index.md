---
title: MathBlock
second_title: مرجع API Aspose.Sildes برای .NET
description: یک نمونه از متن ریاضی را که در داخل یک MathParagraph قرار دارد و در خط خود شروع می‌شود، تعیین می‌کند. تمام نواحی ریاضی شامل معادلات، عبارات، آرایه‌های معادلات یا عبارات و فرمول‌ها توسط بلاک ریاضی نمایش داده می‌شوند.
type: docs
weight: 8590
url: /fa/aspose.slides.mathtext/mathblock/
---
## کلاس MathBlock

یک نمونه از متن ریاضی را که درون یک MathParagraph قرار دارد و در خط خود شروع می‌شود، تعیین می‌کند. تمام نواحی ریاضی، از جمله معادلات، عبارات، آرایه‌های معادلات یا عبارات، و فرمول‌ها توسط بلاک ریاضی نشان داده می‌شوند.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathBlock](mathblock#constructor)() | یک نمونه جدید از کلاس MathBlock را مقداردهی اولیه می‌کند. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | یک بلاک ریاضی جدید ایجاد می‌کند و عناصر مشخص‌شده را در آن قرار می‌دهد. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | یک بلاک ریاضی جدید ایجاد می‌کند و عنصر مشخص‌شده را در آن قرار می‌دهد. |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | تعداد عناصر ریاضی فرزند که واقعاً در مجموعه موجود هستند را برمی‌گرداند. فقط خواندنی Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | مقدار false را برمی‌گرداند چون مجموعه عناصر فرزند می‌تواند تغییر کند. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | یک IMathElement را در ایندکس مشخص دریافت یا تنظیم می‌کند. |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت لهجه (یک کاراکتر در بالای این عنصر) را تنظیم می‌کند. |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | یک عنصر ریاضی را به انتهای مجموعه اضافه می‌کند. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان و یک آرگومان اضافی مشخص می‌گیرد. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان و یک آرگومان اضافی مشخص می‌گیرد. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | تمام عناصر را از مجموعه حذف می‌کند. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | تشخیص می‌دهد آیا مجموعه شامل مقدار خاصی است یا نه. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | به آرایه مشخص‌شده کپی می‌کند. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | عناصر فرزند را با کاراکتر جداکننده (بدون کروشه) محدود می‌کند. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | یک کسر با این صورت و مخرج مشخص‌شده ایجاد می‌کند. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | یک کسر با این صورت و مخرج مشخص‌شده ایجاد می‌کند. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | کسر از نوع مشخص‌شده را با این صورت و مخرج مشخص ایجاد می‌کند. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | کسر از نوع مشخص‌شده را با این صورت و مخرج مشخص ایجاد می‌کند. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز می‌گیرد. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | عناصر فرزند این بلاک را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به عنوان قاب می‌گیرد. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | عناصر فرزند این بلاک را در کاراکترهای مشخص‌شده مانند پرانتز یا دیگر به عنوان قاب می‌گیرد و با کاراکتر جداکننده محدود می‌کند. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | عناصر فرزند را دریافت می‌کند. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از کروشهٔ پایین در یک گروه قرار می‌دهد. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از کاراکتر گروه‌بندی مانند کروشهٔ پایین یا دیگری در یک گروه قرار می‌دهد. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | اندیس یک عنصر ریاضی خاص در مجموعه را تعیین می‌کند. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | یک MathElement را در ایندکس مشخص به مجموعه وارد می‌کند. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال بدون حدها را می‌گیرد. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | یک عنصر ریاضی را با این بلاک ریاضی ترکیب می‌کند. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | یک متن ریاضی را با این بلاک ریاضی ترکیب می‌کند. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | یک بلاک ریاضی دیگر را به این بلاک می‌پیوندد. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-آری ایجاد می‌کند. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-آری ایجاد می‌کند. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک خط افقی در بالای این عنصر تنظیم می‌کند. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشهٔ ریاضی از درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشهٔ ریاضی از درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | عنصر در ایندکس مشخص را از مجموعه حذف می‌کند. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | حد پایین را می‌گیرد. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | حد پایین را می‌گیرد. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | نمای پایین (زیرنویس) ایجاد می‌کند. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | نمای پایین (زیرنویس) ایجاد می‌کند. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | نمای زیر و بالا را در سمت چپ ایجاد می‌کند. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | نمای زیر و بالا را در سمت چپ ایجاد می‌کند. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | نمای زیر و بالا را در سمت راست ایجاد می‌کند. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | نمای زیر و بالا را در سمت راست ایجاد می‌کند. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | نمای بالا (بالنویس) ایجاد می‌کند. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | نمای بالا (بالنویس) ایجاد می‌کند. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالا را می‌گیرد. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالا را می‌گیرد. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبه مرزی قرار می‌دهد. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبه مرزی قرار می‌دهد. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبه غیر دیداری (گروه‌بندی منطقی) که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود، قرار می‌دهد. یک شیء بسته‌شده می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز، به عنوان نقطهٔ شکست خط، یا به صورتی گروه‌بندی شود که شکست خط درون آن اجازه داده نشود. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | عناصر فرزند را در آرایهٔ عمودی قرار می‌دهد. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک خط افقی در پایین این عنصر تنظیم می‌کند. |
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
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* اسسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->