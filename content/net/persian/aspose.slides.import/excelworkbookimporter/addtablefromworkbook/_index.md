---
title: AddTableFromWorkbook
second_title: مرجع API Aspose.Sildes برای .NET
description: یک جدول را از کتاب‌کار Excel مشخص‌شده دریافت می‌کند و آن را به انتهای مجموعه‌ اشکال داده‌شده در مختصات تعیین‌شده اضافه می‌کند.
type: docs
weight: 20
url: /fa/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

یک جدول را از کتاب‌کار Excel مشخص شده دریافت می‌کند و آن را به انتهای مجموعه‌ اشکال داده‌شده در مختصات تعیین‌شده اضافه می‌کند.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | مجموعه‌ اشکالی که جدول به آن اضافه خواهد شد. |
| x | Single | مختصات X برای موقعیت‌یابی جدول. |
| y | Single | مختصات Y برای موقعیت‌یابی جدول. |
| workbook | IExcelDataWorkbook | کتاب‌کار Excel. |
| worksheetName | String | نام برگه‌ای که جدول در آن قرار دارد. |
| cellRange | String | محدوده سلولی که جدول را تعریف می‌کند (به عنوان مثال، "A1:D10"). |

### مقدار بازگشتی

جدولی که به مجموعه‌ اشکال اضافه شده بود.

### استثناها

| استثنا | شرط |
| --- | --- |
| ArgumentException | هنگامی که هر یک از پارامترهای لازم خالی یا null باشد، یا زمانی که برگه یا محدوده سلولی مشخص‌شده نامعتبر باشد، پرتاب می‌شود. |
| InvalidOperationException | هنگامی که داده‌های ورودی در قالب پشتیبانی‌نشده‌ای باشد، پرتاب می‌شود. |

### مثال‌ها

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### موارد مرتبط

* رابط [ITable](../../../aspose.slides/itable)
* رابط [IShapeCollection](../../../aspose.slides/ishapecollection)
* رابط [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* کلاس [ExcelWorkbookImporter](../../excelworkbookimporter)
* فضای نام [Aspose.Slides.Import](../../excelworkbookimporter)
* مجمع [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

یک جدول را از فایل کتاب‌کار Excel مشخص شده دریافت می‌کند و آن را به انتهای مجموعه‌ اشکال داده‌شده در مختصات تعیین‌شده اضافه می‌کند.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | مجموعه‌ اشکالی که جدول به آن اضافه خواهد شد. |
| x | Single | مختصات X برای موقعیت‌یابی جدول. |
| y | Single | مختصات Y برای موقعیت‌یابی جدول. |
| workbookPath | String | مسیر به فایل کتاب‌کار Excel. |
| worksheetName | String | نام برگه‌ای که جدول در آن قرار دارد. |
| cellRange | String | محدوده سلولی که جدول را تعریف می‌کند (به عنوان مثال، "A1:D10"). |

### مقدار بازگشتی

جدولی که به مجموعه‌ اشکال اضافه شده بود.

### استثناها

| استثنا | شرط |
| --- | --- |
| ArgumentException | هنگامی که هر یک از پارامترهای لازم خالی یا null باشد، یا زمانی که برگه یا محدوده سلولی مشخص‌شده نامعتبر باشد، پرتاب می‌شود. |
| IOException | هنگامی که هنگام دسترسی به فایل کتاب‌کار خطای ورودی/خروجی رخ دهد، پرتاب می‌شود. |
| InvalidOperationException | هنگامی که داده‌های ورودی در قالب پشتیبانی‌نشده‌ای باشد، پرتاب می‌شود. |

### مثال‌ها

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### موارد مرتبط

* رابط [ITable](../../../aspose.slides/itable)
* رابط [IShapeCollection](../../../aspose.slides/ishapecollection)
* کلاس [ExcelWorkbookImporter](../../excelworkbookimporter)
* فضای نام [Aspose.Slides.Import](../../excelworkbookimporter)
* مجمع [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

یک جدول را از فایل کتاب‌کار Excel مشخص شده دریافت می‌کند و آن را به انتهای مجموعه‌ اشکال داده‌شده در مختصات تعیین‌شده اضافه می‌کند.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | مجموعه‌ اشکالی که جدول به آن اضافه خواهد شد. |
| x | Single | مختصات X برای موقعیت‌یابی جدول. |
| y | Single | مختصات Y برای موقعیت‌یابی جدول. |
| workbookStream | Stream | جریانی که حاوی داده‌های کتاب‌کار است. |
| worksheetName | String | نام برگه‌ای که جدول در آن قرار دارد. |
| cellRange | String | محدوده سلولی که جدول را تعریف می‌کند (به عنوان مثال، "A1:D10"). |

### مقدار بازگشتی

جدولی که به مجموعه‌ اشکال اضافه شده بود.

### استثناها

| استثنا | شرط |
| --- | --- |
| ArgumentException | هنگامی که هر یک از پارامترهای لازم خالی یا null باشد، یا زمانی که برگه یا محدوده سلولی مشخص‌شده نامعتبر باشد، پرتاب می‌شود. |
| InvalidOperationException | هنگامی که داده‌های ورودی در قالب پشتیبانی‌نشده‌ای باشد، پرتاب می‌شود. |

### مثال‌ها

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### موارد مرتبط

* رابط [ITable](../../../aspose.slides/itable)
* رابط [IShapeCollection](../../../aspose.slides/ishapecollection)
* کلاس [ExcelWorkbookImporter](../../excelworkbookimporter)
* فضای نام [Aspose.Slides.Import](../../excelworkbookimporter)
* مجمع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->