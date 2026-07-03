---
title: AddTableFromWorkbook
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يسترجع جدولًا من مصنف Excel المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.
type: docs
weight: 20
url: /ar/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

تسترجع جدولًا من مصنف Excel المحدد وتضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | مجموعة الأشكال التي سيتم إضافة الجدول إليها. |
| x | Single | إحداثي X لتحديد موضع الجدول. |
| y | Single | إحداثي Y لتحديد موضع الجدول. |
| workbook | IExcelDataWorkbook | مصنف Excel. |
| worksheetName | String | اسم ورقة العمل التي تحتوي على الجدول. |
| cellRange | String | نطاق الخلايا الذي يحدد الجدول (على سبيل المثال، "A1:D10"). |

### Return Value
قيمة الإرجاع

الجدول الذي تم إضافته إلى مجموعة الأشكال.

### Exceptions
الاستثناءات

| exception | condition |
| --- | --- |
| ArgumentException | يُرمى عندما يكون أي من المعاملات المطلوبة فارغًا أو غير موجود، أو عندما تكون ورقة العمل أو نطاق الخلايا المحدد غير صالح. |
| InvalidOperationException | يُرمى عندما تكون البيانات المدخلة بتنسيق غير مدعوم. |

### Examples
أمثلة

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### See Also
انظر أيضاً

* interface [ITable](../../../aspose.slides/itable)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

تسترجع جدولًا من ملف مصنف Excel المحدد وتضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | مجموعة الأشكال التي سيتم إضافة الجدول إليها. |
| x | Single | إحداثي X لتحديد موضع الجدول. |
| y | Single | إحداثي Y لتحديد موضع الجدول. |
| workbookPath | String | المسار إلى ملف مصنف Excel. |
| worksheetName | String | اسم ورقة العمل التي تحتوي على الجدول. |
| cellRange | String | نطاق الخلايا الذي يحدد الجدول (على سبيل المثال، "A1:D10"). |

### Return Value
قيمة الإرجاع

الجدول الذي تم إضافته إلى مجموعة الأشكال.

### Exceptions
الاستثناءات

| exception | condition |
| --- | --- |
| ArgumentException | يُرمى عندما يكون أي من المعاملات المطلوبة فارغًا أو غير موجود، أو عندما تكون ورقة العمل أو نطاق الخلايا المحدد غير صالح. |
| IOException | يُرمى عندما يحدث خطأ إدخال/إخراج أثناء الوصول إلى ملف المصنف. |
| InvalidOperationException | يُرمى عندما تكون البيانات المدخلة بتنسيق غير مدعوم. |

### Examples
أمثلة

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### See Also
انظر أيضاً

* interface [ITable](../../../aspose.slides/itable)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

تسترجع جدولًا من ملف مصنف Excel المحدد وتضيفه إلى نهاية مجموعة الأشكال المعطاة عند الإحداثيات المحددة.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | مجموعة الأشكال التي سيتم إضافة الجدول إليها. |
| x | Single | إحداثي X لتحديد موضع الجدول. |
| y | Single | إحداثي Y لتحديد موضع الجدول. |
| workbookStream | Stream | تدفق يحتوي على بيانات المصنف. |
| worksheetName | String | اسم ورقة العمل التي تحتوي على الجدول. |
| cellRange | String | نطاق الخلايا الذي يحدد الجدول (على سبيل المثال، "A1:D10"). |

### Return Value
قيمة الإرجاع

الجدول الذي تم إضافته إلى مجموعة الأشكال.

### Exceptions
الاستثناءات

| exception | condition |
| --- | --- |
| ArgumentException | يُرمى عندما يكون أي من المعاملات المطلوبة فارغًا أو غير موجود، أو عندما تكون ورقة العمل أو نطاق الخلايا المحدد غير صالح. |
| InvalidOperationException | يُرمى عندما تكون البيانات المدخلة بتنسيق غير مدعوم. |

### Examples
أمثلة

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### See Also
انظر أيضاً

* interface [ITable](../../../aspose.slides/itable)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->