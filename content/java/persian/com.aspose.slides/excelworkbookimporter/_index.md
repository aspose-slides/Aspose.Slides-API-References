---
title: ExcelWorkbookImporter
second_title: مرجع API Aspose.Slides برای جاوا
description: قابلیت وارد کردن محتوای یک کتاب‌کار اکسل به یک ارائه را فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/excelworkbookimporter/
---
**ارث‌بری:**  
java.lang.Object  
```
public class ExcelWorkbookImporter
```

قابلیت وارد کردن محتوای یک کتاب‌کار اکسل به یک ارائه را فراهم می‌کند.

## متدها

| متد | توضیح |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | یک نمودار را از کتاب‌کار اکسل مشخص بازیابی می‌کند و آن را در انتهای مجموعه شکل‌های داده شده در مختصات تعیین شده اضافه می‌نماید. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | یک نمودار را از کتاب‌کار اکسل مشخص بازیابی می‌کند و آن را در انتهای مجموعه شکل‌های داده شده در مختصات تعیین شده اضافه می‌نماید. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | یک نمودار را از کتاب‌کار اکسل مشخص بازیابی می‌کند و آن را در انتهای مجموعه شکل‌های داده شده در مختصات تعیین شده اضافه می‌نماید. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | یک نمودار را از کتاب‌کار اکسل مشخص بازیابی می‌کند و آن را در انتهای مجموعه شکل‌های داده شده در مختصات تعیین شده اضافه می‌نماید. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | یک جدول را از کتاب‌کار اکسل مشخص بازیابی می‌کند و آن را در انتهای مجموعه شکل‌های داده شده در مختصات تعیین شده اضافه می‌نماید. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | یک جدول را از فایل کتاب‌کار اکسل مشخص بازیابی می‌کند و آن را در انتهای مجموعه شکل‌های داده شده در مختصات تعیین شده اضافه می‌نماید. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | یک جدول را از فایل کتاب‌کار اکسل مشخص بازیابی می‌کند و آن را در انتهای مجموعه شکل‌های داده شده در مختصات تعیین شده اضافه می‌نماید. |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

یک نمودار را از کتاب‌کار اکسل مشخص بازیابی می‌کند و آن را در انتهای مجموعه شکل‌های داده شده در مختصات تعیین شده اضافه می‌نماید.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعه شکل‌هایی که نمودار به آن اضافه می‌شود. |
| x | float | مختصات X برای موقعیت‌یابی نمودار. |
| y | float | مختصات Y برای موقعیت‌یابی نمودار. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | کتاب‌کار اکسل. |
| worksheetName | java.lang.String | نام صفحه کاری که نمودار را شامل می‌شود. |
| chartIndex | int | شاخص صفر-محور شکل نمودار برای درج. این شاخص می‌تواند با استفاده از متد [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) به‌دست آید. |
| embedAllWorkbook | boolean | اگر true باشد، تمام کتاب‌کار در نمودار جاسازی می‌شود؛ اگر false باشد، فقط داده‌های نمودار جاسازی می‌شوند. |

**بازگشت:**  
[IChart](../../com.aspose.slides/ichart) - نموداری که به مجموعه شکل‌ها اضافه شده است.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

یک نمودار را از کتاب‌کار اکسل مشخص بازیابی می‌کند و آن را در انتهای مجموعه شکل‌های داده شده در مختصات تعیین شده اضافه می‌نماید.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعه شکل‌هایی که نمودار به آن اضافه می‌شود. |
| x | float | مختصات X برای موقعیت‌یابی نمودار. |
| y | float | مختصات Y برای موقعیت‌یابی نمودار. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | کتاب‌کار اکسل. |
| worksheetName | java.lang.String | نام صفحه کاری که نمودار را شامل می‌شود. |
| chartName | java.lang.String | نام نموداری که باید اضافه شود. |
| embedAllWorkbook | boolean | اگر true باشد، تمام کتاب‌کار در نمودار جاسازی می‌شود؛ اگر false باشد، فقط داده‌های نمودار جاسازی می‌شوند. |

**بازگشت:**  
[IChart](../../com.aspose.slides/ichart) - نموداری که به مجموعه شکل‌ها اضافه شده است.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

یک نمودار را از کتاب‌کار اکسل مشخص بازیابی می‌کند و آن را در انتهای مجموعه شکل‌های داده شده در مختصات تعیین شده اضافه می‌نماید.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعه شکل‌هایی که نمودار به آن اضافه می‌شود. |
| x | float | مختصات X برای موقعیت‌یابی نمودار. |
| y | float | مختصات Y برای موقعیت‌یابی نمودار. |
| workbookStream | java.io.InputStream | جریانی که شامل داده‌های کتاب‌کار است. |
| worksheetName | java.lang.String | نام صفحه کاری که نمودار را شامل می‌شود. |
| chartName | java.lang.String | نام نموداری که باید اضافه شود. |
| embedAllWorkbook | boolean | اگر true باشد، تمام کتاب‌کار در نمودار جاسازی می‌شود؛ اگر false باشد، فقط داده‌های نمودار جاسازی می‌شوند. |

**بازگشت:**  
[IChart](../../com.aspose.slides/ichart) - نموداری که به مجموعه شکل‌ها اضافه شده است.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

یک نمودار را از کتاب‌کار اکسل مشخص بازیابی می‌کند و آن را در انتهای مجموعه شکل‌های داده شده در مختصات تعیین شده اضافه می‌نماید.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعه شکل‌هایی که نمودار به آن اضافه می‌شود. |
| x | float | مختصات X برای موقعیت‌یابی نمودار. |
| y | float | مختصات Y برای موقعیت‌یابی نمودار. |
| workbookPath | java.lang.String | مسیر فایل کتاب‌کاری که نمودار را شامل می‌شود. |
| worksheetName | java.lang.String | نام صفحه کاری که نمودار را شامل می‌شود. |
| chartName | java.lang.String | نام نموداری که باید اضافه شود. |
| embedWorkbook | boolean | اگر true باشد، کتاب‌کار در نمودار جاسازی می‌شود؛ اگر false باشد، نمودار به کتاب‌کار خارجی لینک می‌کند. |

**بازگشت:**  
[IChart](../../com.aspose.slides/ichart) - نموداری که به مجموعه شکل‌ها اضافه شده است.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

یک جدول را از کتاب‌کار اکسل مشخص بازیابی می‌کند و آن را در انتهای مجموعه شکل‌های داده شده در مختصات تعیین شده اضافه می‌نماید.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعه شکل‌هایی که جدول به آن اضافه می‌شود. |
| x | float | مختصات X برای موقعیت‌یابی جدول. |
| y | float | مختصات Y برای موقعیت‌یابی جدول. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | کتاب‌کار اکسل. |
| worksheetName | java.lang.String | نام صفحه کاری که جدول را شامل می‌شود. |
| cellRange | java.lang.String | محدوده سلولی که جدول را تعریف می‌کند (مثلاً "A1:D10"). |

**بازگشت:**  
[ITable](../../com.aspose.slides/itable) - جدول‌ای که به مجموعه شکل‌ها اضافه شده است.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

یک جدول را از فایل کتاب‌کار اکسل مشخص بازیابی می‌کند و آن را در انتهای مجموعه شکل‌های داده شده در مختصات تعیین شده اضافه می‌نماید.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعه شکل‌هایی که جدول به آن اضافه می‌شود. |
| x | float | مختصات X برای موقعیت‌یابی جدول. |
| y | float | مختصات Y برای موقعیت‌یابی جدول. |
| workbookPath | java.lang.String | مسیر فایل کتاب‌کار اکسل. |
| worksheetName | java.lang.String | نام صفحه کاری که جدول را شامل می‌شود. |
| cellRange | java.lang.String | محدوده سلولی که جدول را تعریف می‌کند (مثلاً "A1:D10"). |

**بازگشت:**  
[ITable](../../com.aspose.slides/itable) - جدول‌ای که به مجموعه شکل‌ها اضافه شده است.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

یک جدول را از فایل کتاب‌کار اکسل مشخص بازیابی می‌کند و آن را در انتهای مجموعه شکل‌های داده شده در مختصات تعیین شده اضافه می‌نماید.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعه شکل‌هایی که جدول به آن اضافه می‌شود. |
| x | float | مختصات X برای موقعیت‌یابی جدول. |
| y | float | مختصات Y برای موقعیت‌یابی جدول. |
| workbookStream | java.io.InputStream | جریانی که شامل داده‌های کتاب‌کار است. |
| worksheetName | java.lang.String | نام صفحه کاری که جدول را شامل می‌شود. |
| cellRange | java.lang.String | محدوده سلولی که جدول را تعریف می‌کند (مثلاً "A1:D10"). |

**بازگشت:**  
[ITable](../../com.aspose.slides/itable) - جدول‌ای که به مجموعه شکل‌ها اضافه شده است.