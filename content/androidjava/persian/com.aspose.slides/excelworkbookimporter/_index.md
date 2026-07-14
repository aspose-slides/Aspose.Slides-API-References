---
title: ExcelWorkbookImporter
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: قابلیت وارد کردن محتوا از یک کتاب‌کار Excel به یک ارائه را فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/excelworkbookimporter/
---
**Inheritance:**  
java.lang.Object  
```
public class ExcelWorkbookImporter
```

Provides functionality for importing content from an Excel workbook into a presentation.  
## متدها

| متد | توضیح |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | یک نمودار را از کتاب‌کار Excel مشخص دریافت کرده و در مختصات تعیین‌شده به انتهای مجموعه شکل‌های داده‌شده اضافه می‌کند. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | یک نمودار را از کتاب‌کار Excel مشخص دریافت کرده و در مختصات تعیین‌شده به انتهای مجموعه شکل‌های داده‌شده اضافه می‌کند. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | یک نمودار را از کتاب‌کار Excel مشخص دریافت کرده و در مختصات تعیین‌شده به انتهای مجموعه شکل‌های داده‌شده اضافه می‌کند. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | یک نمودار را از کتاب‌کار Excel مشخص دریافت کرده و در مختصات تعیین‌شده به انتهای مجموعه شکل‌های داده‌شده اضافه می‌کند. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | یک جدول را از کتاب‌کار Excel مشخص دریافت کرده و در مختصات تعیین‌شده به انتهای مجموعه شکل‌های داده‌شده اضافه می‌کند. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | یک جدول را از فایل کتاب‌کار Excel دریافت کرده و در مختصات تعیین‌شده به انتهای مجموعه شکل‌های داده‌شده اضافه می‌کند. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | یک جدول را از فایل کتاب‌کار Excel دریافت کرده و در مختصات تعیین‌شده به انتهای مجموعه شکل‌های داده‌شده اضافه می‌کند. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

یک نمودار را از کتاب‌کار Excel مشخص دریافت کرده و در مختصات تعیین‌شده به انتهای مجموعه شکل‌های داده‌شده اضافه می‌کند.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, wb, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعه شکل‌هایی که نمودار به آن اضافه خواهد شد. |
| x | float | مختصات X برای موقعیت‌یابی نمودار. |
| y | float | مختصات Y برای موقعیت‌یابی نمودار. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | کتاب‌کار Excel. |
| worksheetName | java.lang.String | نام شیت کاری که نمودار را شامل می‌شود. |
| chartIndex | int | شاخص صفر-پایهٔ شکل نمودار برای افزودن. این شاخص می‌تواند با استفاده از متد [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) به دست آید. |
| embedAllWorkbook | boolean | اگر درست باشد، تمام کتاب‌کار در نمودار جاسازی می‌شود؛ اگر غلط باشد، تنها داده‌های نمودار جاسازی می‌شود. |

**بازگشت:**
[IChart](../../com.aspose.slides/ichart) - نموداری که به مجموعه شکل‌ها اضافه شد.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

یک نمودار را از کتاب‌کار Excel مشخص دریافت کرده و در مختصات تعیین‌شده به انتهای مجموعه شکل‌های داده‌شده اضافه می‌کند.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      String worksheetName = "worksheet name";
>      Dictionary.Enumerator<Integer, String> worksheetCharts = wb.getChartsFromWorksheet(worksheetName).iterator();
>      while (worksheetCharts.hasNext())
>      {
>          KeyValuePair<Integer, String> chart = worksheetCharts.next();
>          ISlide slide = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>          ExcelWorkbookImporter.addChartFromWorkbook(slide.getShapes(), 10, 10, wb, worksheetName, chart.getKey(), false);
>      }
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعه شکل‌هایی که نمودار به آن اضافه خواهد شد. |
| x | float | مختصات X برای موقعیت‌یابی نمودار. |
| y | float | مختصات Y برای موقعیت‌یابی نمودار. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | کتاب‌کار Excel. |
| worksheetName | java.lang.String | نام شیت کاری که نمودار را شامل می‌شود. |
| chartName | java.lang.String | نام نموداری که باید اضافه شود. |
| embedAllWorkbook | boolean | اگر درست باشد، تمام کتاب‌کار در نمودار جاسازی می‌شود؛ اگر غلط باشد، تنها داده‌های نمودار جاسازی می‌شود. |

**بازگشت:**
[IChart](../../com.aspose.slides/ichart) - نموداری که به مجموعه شکل‌ها اضافه شد.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

یک نمودار را از کتاب‌کار Excel مشخص دریافت کرده و در مختصات تعیین‌شده به انتهای مجموعه شکل‌های داده‌شده اضافه می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fStream = new FileInputStream(workbookPath);
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getLayoutSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, chartName, true);
>      fStream.close();
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعه شکل‌هایی که نمودار به آن اضافه خواهد شد. |
| x | float | مختصات X برای موقعیت‌یابی نمودار. |
| y | float | مختصات Y برای موقعیت‌یابی نمودار. |
| workbookStream | java.io.InputStream | جریانی شامل داده‌های کتاب‌کار. |
| worksheetName | java.lang.String | نام شیت کاری که نمودار را شامل می‌شود. |
| chartName | java.lang.String | نام نموداری که باید اضافه شود. |
| embedAllWorkbook | boolean | اگر درست باشد، تمام کتاب‌کار در نمودار جاسازی می‌شود؛ اگر غلط باشد، تنها داده‌های نمودار جاسازی می‌شود. |

**بازگشت:**
[IChart](../../com.aspose.slides/ichart) - نموداری که به مجموعه شکل‌ها اضافه شد.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

یک نمودار را از کتاب‌کار Excel مشخص دریافت کرده و در مختصات تعیین‌شده به انتهای مجموعه شکل‌های داده‌شده اضافه می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعه شکل‌هایی که نمودار به آن اضافه خواهد شد. |
| x | float | مختصات X برای موقعیت‌یابی نمودار. |
| y | float | مختصات Y برای موقعیت‌یابی نمودار. |
| workbookPath | java.lang.String | مسیر فایل کتاب‌کار حاوی نمودار. |
| worksheetName | java.lang.String | نام شیت کاری که نمودار را شامل می‌شود. |
| chartName | java.lang.String | نام نموداری که باید اضافه شود. |
| embedWorkbook | boolean | اگر درست باشد، کتاب‌کار در نمودار جاسازی می‌شود؛ اگر غلط باشد، نمودار به کتاب‌کار خارجی لینک می‌کند. |

**بازگشت:**
[IChart](../../com.aspose.slides/ichart) - نموداری که به مجموعه شکل‌ها اضافه شد.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

یک جدول را از کتاب‌کار Excel مشخص دریافت کرده و در مختصات تعیین‌شده به انتهای مجموعه شکل‌های داده‌شده اضافه می‌کند.

--------------------

> ```
> IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbook, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعه شکل‌هایی که جدول به آن اضافه خواهد شد. |
| x | float | مختصات X برای موقعیت‌یابی جدول. |
| y | float | مختصات Y برای موقعیت‌یابی جدول. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | کتاب‌کار Excel. |
| worksheetName | java.lang.String | نام شیت کاری که جدول را شامل می‌شود. |
| cellRange | java.lang.String | محدوده سلولی که جدول را تعریف می‌کند (به عنوان مثال، "A1:D10"). |

**بازگشت:**
[ITable](../../com.aspose.slides/itable) - جدولی که به مجموعه شکل‌ها اضافه شد.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

یک جدول را از فایل کتاب‌کار Excel دریافت کرده و در مختصات تعیین‌شده به انتهای مجموعه شکل‌های داده‌شده اضافه می‌کند.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعه شکل‌هایی که جدول به آن اضافه خواهد شد. |
| x | float | مختصات X برای موقعیت‌یابی جدول. |
| y | float | مختصات Y برای موقعیت‌یابی جدول. |
| workbookPath | java.lang.String | مسیر فایل کتاب‌کار Excel. |
| worksheetName | java.lang.String | نام شیت کاری که جدول را شامل می‌شود. |
| cellRange | java.lang.String | محدوده سلولی که جدول را تعریف می‌کند (به عنوان مثال، "A1:D10"). |

**بازگشت:**
[ITable](../../com.aspose.slides/itable) - جدولی که به مجموعه شکل‌ها اضافه شد.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

یک جدول را از فایل کتاب‌کار Excel دریافت کرده و در مختصات تعیین‌شده به انتهای مجموعه شکل‌های داده‌شده اضافه می‌کند.

--------------------

> ```
> FileInputStream fStream = new FileInputStream(workbookPath);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعه شکل‌هایی که جدول به آن اضافه خواهد شد. |
| x | float | مختصات X برای موقعیت‌یابی جدول. |
| y | float | مختصات Y برای موقعیت‌یابی جدول. |
| workbookStream | java.io.InputStream | جریانی شامل داده‌های کتاب‌کار. |
| worksheetName | java.lang.String | نام شیت کاری که جدول را شامل می‌شود. |
| cellRange | java.lang.String | محدوده سلولی که جدول را تعریف می‌کند (به عنوان مثال، "A1:D10"). |

**بازگشت:**
[ITable](../../com.aspose.slides/itable) - جدولی که به مجموعه شکل‌ها اضافه شد.