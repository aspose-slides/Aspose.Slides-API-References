---
title: IMathMatrix
second_title: Aspose.Sildes برای .NET مرجع API
description: شیء Matrix را مشخص می‌کند که از عناصر فرزندی تشکیل شده است که در یک یا چند ردیف و ستون چیده شده‌اند. مهم است که توجه داشته باشید ماتریس‌ها delimiters داخلی ندارند. برای قرار دادن ماتریس در براکت‌ها باید از شیء delimiter IMathDelimiter استفاده کنید. می‌توان از آرگومان‌های null برای ایجاد فواصل در ماتریس‌ها استفاده کرد.
type: docs
weight: 8340
url: /fa/aspose.slides.mathtext/imathmatrix/
---

## رابط IMathMatrix

ماتریس شیء Matrix را مشخص می‌کند که از عناصر فرزندی ترکیب شده‌اند که در یک یا چند ردیف و ستون چیده شده‌اند. مهم است که توجه داشته باشید ماتریس‌ها delimiters داخلی ندارند. برای قرار دادن ماتریس در پرانتزها باید از شیء delimiter (IMathDelimiter) استفاده کنید. می‌توان از آرگومان‌های null برای ایجاد فواصل در ماتریس‌ها استفاده کرد.

```csharp
public interface IMathMatrix : IMathElement
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | اجازه می‌دهد رابط پایه IMathElement را دریافت کنید [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | جهت‌گیری عمودی نسبت به متن اطراف را مشخص می‌کند. مقادیر ممکن top، bottom و center هستند. پیش‌فرض: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | تعداد ستون‌ها در ماتریس |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | مقدار فاصلهٔ افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 ("Exactly") باشد، واحد به صورت twips (۱/۲۰ ام نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 ("Multiple") باشد، واحد به‌عنوان تعداد گام‌های ۰٫۵ em تفسیر می‌شود. در سایر موارد نادیده گرفته می‌شود. پیش‌فرض: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | نوع فاصلهٔ افقی بین ستون‌های یک ماتریس؛ واحدهای فاصلهٔ افقی می‌توانند em یا point باشند (به‌صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | پنهان کردن نگهدارنده‌ها برای عناصر خالی ماتریس پیش‌فرض: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | عناصر ماتریس |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | حداقل عرض ستون به twips (۱/۲۰ ام نقطه) فاصلهٔ بین ستون‌ها (که به عنوان “Column Gap” یا “Gap Width” نیز نامیده می‌شود) به MinColumnWidth اضافه می‌شود تا فاصلهٔ کلی ستون‌های ماتریس (فاصله بین لبه‌های مشابه ستون‌های مختلف) تعیین شود. پیش‌فرض: 0 |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | تعداد ردیف‌ها در ماتریس |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | مقدار فاصلهٔ عمودی بین ردیف‌های یک ماتریس؛ اگر RowGapRule برابر 3 ("Exactly") باشد، واحد به صورت twips (۱/۲۰ ام نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 ("Multiple") باشد، واحد به‌عنوان نیم‌خط‌ها تفسیر می‌شود. پیش‌فرض: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | نوع فاصلهٔ عمودی بین ردیف‌های یک ماتریس؛ واحدهای فاصلهٔ عمودی می‌توانند line یا point باشند (به‌صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0) |

## متدها

| نام | توضیح |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | ستون مشخص‌شده را حذف می‌کند |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | ردیف مشخص‌شده را حذف می‌کند |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | جهت‌گیری افقی ستون مشخص‌شده را دریافت می‌کند |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | ستون جدیدی پس از ستون مشخص‌شده درج می‌کند. در ابتدا تمام عناصر ستون جدید مقدار null دارند. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | ستون جدیدی قبل از ستون مشخص‌شده درج می‌کند. در ابتدا تمام عناصر ستون جدید مقدار null دارند. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | ردیف جدیدی پس از ردیف مشخص‌شده درج می‌کند. در ابتدا تمام عناصر ردیف جدید مقدار null دارند. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | ردیف جدیدی قبل از ردیف مشخص‌شده درج می‌کند. در ابتدا تمام عناصر ردیف جدید مقدار null دارند. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | جهت‌گیری افقی ستون مشخص‌شده را تنظیم می‌کند |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | جهت‌گیری افقی ستون‌های مشخص‌شده را تنظیم می‌کند |

### مثال‌ها

مثال:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

## موارد مرتبط

* interface [IMathElement](../imathelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->