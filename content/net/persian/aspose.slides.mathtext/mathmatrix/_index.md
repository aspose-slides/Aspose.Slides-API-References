---
title: MathMatrix
second_title: Aspose.Sildes برای مرجع API .NET
description: شی Matrix را مشخص می‌کند که از عناصر فرزند در یک یا چند ردیف و ستون چیده شده تشکیل شده است. مهم است که توجه داشته باشید ماتریس‌ها جداسازهای داخلی ندارند. برای قرار دادن ماتریس در پرانتزها باید از شی جداساز IMathDelimiter استفاده کنید. آرگومان‌های null می‌توانند برای ایجاد فواصل در ماتریس‌ها استفاده شوند.
type: docs
weight: 8850
url: /fa/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix کلاس

یک شیء Matrix را مشخص می‌کند که از عناصر فرزند در یک یا چند ردیف و ستون چیده شده تشکیل شده است. مهم است که توجه داشته باشید ماتریس‌ها جداکننده‌های داخلی ندارند. برای قرار دادن ماتریس در پرانتزها باید از شیء جداکننده (IMathDelimiter) استفاده کنید. آرگومان‌های null می‌توانند برای ایجاد فواصل در ماتریس‌ها استفاده شوند.

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
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | جهت‌گیری عمودی نسبت به متن اطراف را مشخص می‌کند. مقادیر ممکن top، bottom و center هستند. پیش‌فرض: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | تعداد ستون‌ها در ماتریس |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | مقدار فاصلهٔ افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 ("Exactly") باشد، واحد به صورت twips (۱/۲۰ی یک نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 ("Multiple") باشد، واحد به عنوان تعداد افزایش‌های ۰٫۵ em تفسیر می‌شود. در موارد دیگر نادیده گرفته می‌شود. پیش‌فرض: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | نوع فاصلهٔ افقی بین ستون‌های یک ماتریس؛ واحدهای فاصلهٔ افقی می‌توانند em یا پوینت (به صورت twips ذخیره) باشند. پیش‌فرض: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | مکان‌نگهدارهای عناصر خالی ماتریس را مخفی می‌کند. پیش‌فرض: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | عنصر ماتریس |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | حداقل عرض ستون به twips (۱/۲۰ی یک نقطه). فاصلهٔ گپ (که به عنوان “Column Gap” یا “Gap Width” نیز شناخته می‌شود) به MinColumnWidth اضافه می‌شود تا کل فاصلهٔ ستون‌های ماتریس (فاصله بین لبه‌های مشابه ستون‌های مختلف) محاسبه شود. پیش‌فرض: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | تعداد سطرها در ماتریس |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | مقدار فاصلهٔ عمودی بین سطرهای یک ماتریس؛ اگر RowGapRule برابر 3 ("Exactly") باشد، واحد به صورت twips (۱/۲۰ی یک نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 ("Multiple") باشد، واحد به صورت نیم‌خط (half-lines) تفسیر می‌شود. پیش‌فرض: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | نوع فاصلهٔ عمودی بین سطرهای یک ماتریس؛ واحدهای فاصلهٔ عمودی می‌توانند خط یا پوینت (به صورت twips ذخیره) باشند. پیش‌فرض: SingleSpacingGap (0) |

## متدها

| نام | توضیح |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | یک علامت اکسنت (یک کاراکتر در بالای این عنصر) را تنظیم می‌کند |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافه مشخص‌شده، تابع مشخص‌شده‌ای را می‌گیرد |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافه مشخص‌شده، تابع مشخص‌شده‌ای را می‌گیرد |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | ستون مشخص‌شده را حذف می‌کند |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | سطر مشخص‌شده را حذف می‌کند |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | یک کسر با این شمارنده و مخرج مشخص‌شده می‌سازد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | یک کسر با این شمارنده و مخرج مشخص‌شده می‌سازد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | یک کسر از نوع مشخص‌شده با این شمارنده و مخرج مشخص‌شده می‌سازد |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | یک کسر از نوع مشخص‌شده با این شمارنده و مخرج مشخص‌شده می‌سازد |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | یک عنصر ریاضی را در پرانتز محصور می‌کند |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | یک عنصر ریاضی را در کاراکترهای مشخص مانند پرانتز یا کاراکترهای دیگر به عنوان چارچوب محصور می‌کند |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | تابعی از یک آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | تابعی از یک آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | عناصر فرزند را دریافت می‌کند |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | ترازبندی افقی ستون مشخص‌شده را دریافت می‌کند |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | این عنصر را با استفاده از آکولاد پایینی در یک گروه قرار می‌دهد |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | این عنصر را با استفاده از کاراکتر گروه‌بندی مانند آکولاد پایینی یا کاراکتر دیگری در یک گروه قرار می‌دهد |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | یک ستون جدید پس از ستون مشخص‌شده وارد می‌کند. در ابتدا تمام عناصر ستون جدید مقدار null دارند. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | یک ستون جدید پیش از ستون مشخص‌شده وارد می‌کند. در ابتدا تمام عناصر ستون جدید مقدار null دارند. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | یک سطر جدید پس از سطر مشخص‌شده وارد می‌کند. در ابتدا تمام عناصر سطر جدید مقدار null دارند. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | یک سطر جدید پیش از سطر مشخص‌شده وارد می‌کند. در ابتدا تمام عناصر سطر جدید مقدار null دارند. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | انتگرال را بدون حدها می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | انتگرال را می‌گیرد |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | انتگرال را می‌گیرد |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی ایجاد می‌کند |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | یک متن ریاضی را می‌پیوندد و یک بلوک ریاضی ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | یک عملگر N-ary ایجاد می‌کند |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | یک عملگر N-ary ایجاد می‌کند |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | یک خط در بالای این عنصر تنظیم می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ریشه ریاضی از درجه داده شده را از آرگومان مشخص‌شده تعیین می‌کند |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ریشه ریاضی از درجه داده شده را از آرگومان مشخص‌شده تعیین می‌کند |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | ترازبندی افقی ستون مشخص‌شده را تنظیم می‌کند |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | ترازبندی افقی ستون‌های مشخص‌شده را تنظیم می‌کند |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | حد پایین را می‌گیرد |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | حد پایین را می‌گیرد |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | زیرنویس ایجاد می‌کند |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | زیرنویس ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | زیرنویس و فوق‌نویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | زیرنویس و فوق‌نویس را در سمت چپ ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | زیرنویس و فوق‌نویس را در سمت راست ایجاد می‌کند |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | زیرنویس و فوق‌نویس را در سمت راست ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | فوق‌نویس ایجاد می‌کند |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | فوق‌نویس ایجاد می‌کند |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | حد بالا را می‌گیرد |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | حد بالا را می‌گیرد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | این عنصر را در یک جعبه‌حاشیه‌ای قرار می‌دهد |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | این عنصر را در یک جعبه‌حاشیه‌ای قرار می‌دهد |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | این عنصر را در یک جعبه غیرقابل مشاهده (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی اجزای یک معادله یا نمونه دیگر متن ریاضی استفاده می‌شود. یک شیء جعبه‌ای می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطه تنظیم، به عنوان نقطهٔ شکست خط، یا به گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط درون آن داده نشود. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | در یک آرایهٔ عمودی قرار می‌دهد |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | یک خط در پایین این عنصر تنظیم می‌کند |

### مثال‌ها

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### همچنین‌ببینید

* کلاس [MathElementBase](../mathelementbase)
* رابط [IMathMatrix](../imathmatrix)
* فضای‌نام [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* مجموعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->