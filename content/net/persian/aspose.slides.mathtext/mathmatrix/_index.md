---
title: MathMatrix
second_title: Aspose.Sildes برای .NET مرجع API
description: شی Matrix را مشخص می‌کند که از عناصر فرزند تشکیل شده و در یک یا چند ردیف و ستون چیده شده‌اند. لازم به ذکر است که ماتریس‌ها تقسیم‌کننده‌های داخلی ندارند. برای قرار دادن ماتریس در پرانتزها باید از شی delimiter به نام IMathDelimiter استفاده کنید. می‌توانید از آرگومان‌های null برای ایجاد فواصل در ماتریس‌ها استفاده کنید.
type: docs
weight: 8850
url: /fa/aspose.slides.mathtext/mathmatrix/
---
## کلاس MathMatrix

شی Matrix را مشخص می‌کند که از عناصر فرزند تشکیل شده‌اند که در یک یا چند ردیف و ستون چیده شده‌اند. لازم به ذکر است که ماتریس‌ها تقسیم‌کننده‌های داخلی ندارند. برای قرار دادن ماتریس در پرانتزها باید از شی delimiter (IMathDelimiter) استفاده کنید. می‌توانید از آرگومان‌های null برای ایجاد فواصل در ماتریس‌ها استفاده کنید.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | یک نمونه جدید از کلاس MathMatrix را مقداردهی اولیه می‌کند. |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | جهت‌گیری عمودی نسبت به متن پیرامونی را مشخص می‌کند. مقادیر ممکن top، bottom و center هستند. پیش‌فرض: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | تعداد ستون‌ها در ماتریس |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | مقدار فاصله افقی بین ستون‌های ماتریس؛ اگر ColumnGapRule برابر 3 ("Exactly") باشد، واحد به صورت twips (۱/۲۰ ام نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 ("Multiple") باشد، واحد به صورت تعداد گام‌های ۰.۵ em تفسیر می‌شود. در سایر موارد نادیده گرفته می‌شود. پیش‌فرض: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | نوع فاصله افقی بین ستون‌های ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | مخفی کردن نگهدارنده‌ها برای عناصر خالی ماتریس. پیش‌فرض: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | عنصر ماتریس |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | حداقل عرض ستون به twips (۱/۲۰ ام نقطه). فاصله بین ستون‌ها (که به “Column Gap” یا “Gap Width” نیز گفته می‌شود) به MinColumnWidth اضافه می‌شود تا کل فاصله ستون‌های ماتریس (فاصله بین لبه‌های یکسان ستون‌های مختلف) تعیین شود. پیش‌فرض: 0 |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | تعداد ردیف‌ها در ماتریس |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | مقدار فاصله عمودی بین ردیف‌های ماتریس؛ اگر RowGapRule برابر 3 ("Exactly") باشد، واحد به صورت twips (۱/۲۰ ام نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 ("Multiple") باشد، واحد به صورت نیم‌خط تفسیر می‌شود. پیش‌فرض: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | نوع فاصله عمودی بین ردیف‌های ماتریس؛ واحدهای فاصله عمودی می‌توانند line یا point باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0) |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت شفاف (کاراکتر در بالای این عنصر) تنظیم می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان فرا می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان فرا می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان فرا می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان و یک آرگومان اضافی مشخص شده فرا می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان و یک آرگومان اضافی مشخص شده فرا می‌گیرد |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | ستون مشخص شده را حذف می‌کند |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | ردیف مشخص شده را حذف می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | کسر با این صورت‌حاصل و مخرج مشخص شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | کسر با این صورت‌حاصل و مخرج مشخص شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | کسر از نوع مشخص شده را با این صورت‌حاصل و مخرج مشخص شده ایجاد می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | کسر از نوع مشخص شده را با این صورت‌حاصل و مخرج مشخص شده ایجاد می‌کند |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | عنصر ریاضی را در پرانتز قرار می‌دهد |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | عنصر ریاضی را در کاراکترهای مشخص شده (مانند پرانتز یا کاراکترهای دیگر) محاط می‌کند |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان را با استفاده از این نمونه به عنوان نام تابع فرا می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان را با استفاده از این نمونه به عنوان نام تابع فرا می‌گیرد |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | تراز افقی ستون مشخص شده را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با یک براکت منحنی پایین در یک گروه قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با یک کاراکتر گروه‌بندی (مانند براکت منحنی پایین یا دیگری) در گروه قرار می‌دهد |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | ستون جدیدی بعد از ستون مشخص شده درج می‌کند. ابتدا تمام عناصر در ستون جدید null هستند. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | ستون جدیدی قبل از ستون مشخص شده درج می‌کند. ابتدا تمام عناصر در ستون جدید null هستند. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | ردیف جدیدی بعد از ردیف مشخص شده درج می‌کند. ابتدا تمام عناصر در ردیف جدید null هستند. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | ردیف جدیدی قبل از ردیف مشخص شده درج می‌کند. ابتدا تمام عناصر در ردیف جدید null هستند. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال را بدون حدها می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را پیوند می‌دهد و یک بلوک ریاضی ایجاد می‌کند |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | متن ریاضی را پیوند می‌دهد و یک بلوک ریاضی ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-ary ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-ary ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک خط افقی در بالای این عنصر می‌گذارد |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشه ریاضی درجه داده شده را از آرگومان مشخص شده استخراج می‌کند. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشه ریاضی درجه داده شده را از آرگومان مشخص شده استخراج می‌کند. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | تراز افقی ستون مشخص شده را تنظیم می‌کند |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | تراز افقی ستون‌های مشخص شده را تنظیم می‌کند |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبه حاشیه‌دار قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبه حاشیه‌دار قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبه غیر‌نمایشی (گروه‌بندی منطقی) که برای گروه‌بندی اجزای معادله یا سایر متن‌های ریاضی استفاده می‌شود، قرار می‌دهد. یک شی جعبه‌دار می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، به عنوان نقطه شکست خط عمل کند یا به گونه‌ای گروه‌بندی شود که شکست خط درون آن مجاز نباشد. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایه عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک خط افقی در پایین این عنصر می‌گذارد |

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
* فضای‌نامی [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->