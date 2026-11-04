---
title: MathMatrix
second_title: مرجع API Aspose.Sildes برای .NET
description: شی Matrix را مشخص می‌کند که از عناصر فرزند در یک یا چند ردیف و ستون چیده شده تشکیل شده است. لازم است بدانید ماتریس‌ها جداکننده داخلی ندارند. برای قرار دادن ماتریس در براکت‌ها باید از شی جداکننده IMathDelimiter استفاده کنید. می‌توان از آرگومان‌های null برای ایجاد فواصل در ماتریس‌ها استفاده کرد.
type: docs
weight: 8870
url: /fa/aspose.slides.mathtext/mathmatrix/
---
## کلاس MathMatrix

شی Matrix را مشخص می‌کند که از عناصر فرزند در یک یا چند ردیف و ستون چیده شده تشکیل شده است. لازم است بدانید ماتریس‌ها جداکننده داخلی ندارند. برای قرار دادن ماتریس در براکت‌ها باید از شی جداکننده (IMathDelimiter) استفاده کنید. می‌توان از آرگومان‌های null برای ایجاد فواصل در ماتریس‌ها استفاده کرد.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | یک نمونه جدید از کلاس MathMatrix را مقداردهی اولیه می‌کند. |

## خصوصیات

| نام | توضیح |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | هم‌تراز عمودی نسبت به متن اطراف را تعیین می‌کند. مقادیر ممکن top، bottom و center هستند. Default: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | تعداد ستون‌ها در ماتریس |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 ("Exactly") باشد، واحد به عنوان twips (۱/۲۰ام نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 ("Multiple") باشد، واحد به عنوان تعداد گام‌های ۰٫۵ em تفسیر می‌شود. در سایر موارد نادیده گرفته می‌شود. Default: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به صورت twips ذخیره می‌شوند). Default: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | مکان‌گیرهای عناصر خالی ماتریس را مخفی می‌کند. Default: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | عنصر ماتریس |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | حداقل عرض ستون به twips (۱/۲۰ام نقطه). فاصله گپ (که به عنوان “Column Gap” یا “Gap Width” نیز شناخته می‌شود) به MinColumnWidth اضافه می‌شود تا کل فاصله ستون‌های ماتریس (فاصله بین لبه‌های مشابه ستون‌های مختلف) تعیین شود. Default: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | تعداد ردیف‌ها در ماتریس |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | مقدار فاصله عمودی بین ردیف‌های یک ماتریس؛ اگر RowGapRule برابر 3 ("Exactly") باشد، واحد به عنوان twips (۱/۲۰ام نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 ("Multiple") باشد، واحد به عنوان نیم‌خط‌ها تفسیر می‌شود. Default: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | نوع فاصله عمودی بین ردیف‌های یک ماتریس؛ واحدهای فاصله عمودی می‌توانند line یا point باشند (به صورت twips ذخیره می‌شوند). Default: SingleSpacingGap (0) |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت لهجه (یک کاراکتر در بالای این عنصر) را تنظیم می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان و یک آرگومان اضافی مشخص شده می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی رشته‌ای مشخص می‌گیرد |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | ستون مشخص شده را حذف می‌کند |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | ردیف مشخص شده را حذف می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | کسر با این صورت و مخرج مشخص شده را ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | کسر با این صورت و مخرج مشخص شده را ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | کسر از نوع مشخص شده را با این صورت و مخرج مشخص شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | کسر از نوع مشخص شده را با این صورت و مخرج مشخص شده ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز قرار می‌دهد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | یک عنصر ریاضی را در کاراکترهای مشخص شده مانند پرانتز یا سایر کاراکترها به عنوان قاب قرار می‌دهد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | هم‌ترازی افقی ستون مشخص شده را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از کروشهٔ پایینی در یک گروه قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از کاراکتر گروه‌بندی مانند کروشهٔ پایینی یا کاراکتر دیگر در یک گروه قرار می‌دهد |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | ستون جدیدی پس از ستون مشخص شده درج می‌کند. در ابتدا تمام عناصر ستون جدید null هستند. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | ستون جدیدی پیش از ستون مشخص شده درج می‌کند. در ابتدا تمام عناصر ستون جدید null هستند. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | ردیف جدیدی پس از ردیف مشخص شده درج می‌کند. در ابتدا تمام عناصر ردیف جدید null هستند. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | ردیف جدیدی پیش از ردیف مشخص شده درج می‌کند. در ابتدا تمام عناصر ردیف جدید null هستند. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال بدون حدود را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را می‌پیوندد و بلوک ریاضی ایجاد می‌کند |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را می‌پیوندد و بلوک ریاضی ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-ary ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-ary ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | نوار بالایی را روی این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشه ریاضی درجهٔ داده‌شده را از آرگومان مشخص شده تعیین می‌کند. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشه ریاضی درجهٔ داده‌شده را از آرگومان مشخص شده تعیین می‌کند. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | هم‌ترازی افقی ستون مشخص شده را تنظیم می‌کند |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | هم‌ترازی افقی ستون‌های مشخص شده را تنظیم می‌کند |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبه غیرقابل دید (گروه‌بندی منطقی) که برای گروه‌بندی اجزای یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود، قرار می‌دهد. یک شی جعبه‌ای می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، نقطه شکست خط باشد، یا به طوری گروه‌بندی شود که داخل آن شکست خط مجاز نباشد. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | یک آرایهٔ عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | نوار پایینی را روی این عنصر تنظیم می‌کند |

### مثال‌ها

مثال:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### موارد مرتبط

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathMatrix](../imathmatrix)
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->