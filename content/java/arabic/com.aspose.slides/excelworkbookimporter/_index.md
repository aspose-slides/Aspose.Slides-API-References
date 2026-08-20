---
title: ExcelWorkbookImporter
second_title: مرجع API لـ Aspose.Slides for Java
description: يوفر وظائف لاستيراد المحتوى من مصنف إكسل إلى عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/excelworkbookimporter/
---
**الوراثة:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

يوفر وظائف لاستيراد المحتوى من مصنف إكسل إلى عرض تقديمي.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | يجلب مخططًا من مصنف إكسل المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة في الإحداثيات المحددة. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | يجلب مخططًا من مصنف إكسل المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة في الإحداثيات المحددة. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | يجلب مخططًا من مصنف إكسل المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة في الإحداثيات المحددة. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | يجلب مخططًا من مصنف إكسل المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة في الإحداثيات المحددة. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | يجلب جدولًا من مصنف إكسل المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة في الإحداثيات المحددة. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | يجلب جدولًا من ملف مصنف إكسل المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة في الإحداثيات المحددة. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | يجلب جدولًا من ملف مصنف إكسل المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة في الإحداثيات المحددة. |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

يجلب مخططًا من مصنف إكسل المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة في الإحداثيات المحددة.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | float | الإحداثي X لتحديد موقع المخطط. |
| y | float | الإحداثي Y لتحديد موقع المخطط. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | مصنف إكسل. |
| worksheetName | java.lang.String | اسم ورقة العمل التي تحتوي على المخطط. |
| chartIndex | int | الفهرس الصفري لشكل المخطط الذي سيتم إدراجه. يمكن الحصول على هذا الفهرس باستخدام طريقة [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-). |
| embedAllWorkbook | boolean | إذا كان true، سيتم تضمين المصنف بالكامل في المخطط؛ إذا كان false، سيتم تضمين بيانات المخطط فقط. |

**الإرجاع:**
[IChart](../../com.aspose.slides/ichart) - المخطط الذي تم إضافته إلى مجموعة الأشكال.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

يجلب مخططًا من مصنف إكسل المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة في الإحداثيات المحددة.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | float | الإحداثي X لتحديد موقع المخطط. |
| y | float | الإحداثي Y لتحديد موقع المخطط. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | مصنف إكسل. |
| worksheetName | java.lang.String | اسم ورقة العمل التي تحتوي على المخطط. |
| chartName | java.lang.String | اسم المخطط الذي سيُضاف. |
| embedAllWorkbook | boolean | إذا كان true، سيتم تضمين المصنف بالكامل في المخطط؛ إذا كان false، سيتم تضمين بيانات المخطط فقط. |

**الإرجاع:**
[IChart](../../com.aspose.slides/ichart) - المخطط الذي تم إضافته إلى مجموعة الأشكال.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

يجلب مخططًا من مصنف إكسل المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة في الإحداثيات المحددة.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | float | الإحداثي X لتحديد موقع المخطط. |
| y | float | الإحداثي Y لتحديد موقع المخطط. |
| workbookStream | java.io.InputStream | تدفق يحتوي على بيانات المصنف. |
| worksheetName | java.lang.String | اسم ورقة العمل التي تحتوي على المخطط. |
| chartName | java.lang.String | اسم المخطط الذي سيُضاف. |
| embedAllWorkbook | boolean | إذا كان true، سيتم تضمين المصنف بالكامل في المخطط؛ إذا كان false، سيتم تضمين بيانات المخطط فقط. |

**الإرجاع:**
[IChart](../../com.aspose.slides/ichart) - المخطط الذي تم إضافته إلى مجموعة الأشكال.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

يجلب مخططًا من مصنف إكسل المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة في الإحداثيات المحددة.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعة الأشكال التي سيُضاف إليها المخطط. |
| x | float | الإحداثي X لتحديد موقع المخطط. |
| y | float | الإحداثي Y لتحديد موقع المخطط. |
| workbookPath | java.lang.String | مسار الملف إلى المصنف الذي يحتوي على المخطط. |
| worksheetName | java.lang.String | اسم ورقة العمل التي تحتوي على المخطط. |
| chartName | java.lang.String | اسم المخطط الذي سيُضاف. |
| embedWorkbook | boolean | إذا كان true، سيتم تضمين المصنف في المخطط؛ إذا كان false، سيتصل المخطط بالمصنف الخارجي. |

**الإرجاع:**
[IChart](../../com.aspose.slides/ichart) - المخطط الذي تم إضافته إلى مجموعة الأشكال.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

يجلب جدولًا من مصنف إكسل المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة في الإحداثيات المحددة.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعة الأشكال التي سيُضاف إليها الجدول. |
| x | float | الإحداثي X لتحديد موقع الجدول. |
| y | float | الإحداثي Y لتحديد موقع الجدول. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | مصنف إكسل. |
| worksheetName | java.lang.String | اسم ورقة العمل التي تحتوي على الجدول. |
| cellRange | java.lang.String | النطاق الخلوي الذي يحدد الجدول (على سبيل المثال، "A1:D10"). |

**الإرجاع:**
[ITable](../../com.aspose.slides/itable) - الجدول الذي تم إضافته إلى مجموعة الأشكال.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

يجلب جدولًا من ملف مصنف إكسل المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة في الإحداثيات المحددة.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعة الأشكال التي سيُضاف إليها الجدول. |
| x | float | الإحداثي X لتحديد موقع الجدول. |
| y | float | الإحداثي Y لتحديد موقع الجدول. |
| workbookPath | java.lang.String | مسار ملف مصنف إكسل. |
| worksheetName | java.lang.String | اسم ورقة العمل التي تحتوي على الجدول. |
| cellRange | java.lang.String | النطاق الخلوي الذي يحدد الجدول (على سبيل المثال، "A1:D10"). |

**الإرجاع:**
[ITable](../../com.aspose.slides/itable) - الجدول الذي تم إضافته إلى مجموعة الأشكال.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

يجلب جدولًا من ملف مصنف إكسل المحدد ويضيفه إلى نهاية مجموعة الأشكال المعطاة في الإحداثيات المحددة.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | مجموعة الأشكال التي سيُضاف إليها الجدول. |
| x | float | الإحداثي X لتحديد موقع الجدول. |
| y | float | الإحداثي Y لتحديد موقع الجدول. |
| workbookStream | java.io.InputStream | تدفق يحتوي على بيانات المصنف. |
| worksheetName | java.lang.String | اسم ورقة العمل التي تحتوي على الجدول. |
| cellRange | java.lang.String | النطاق الخلوي الذي يحدد الجدول (على سبيل المثال، "A1:D10"). |

**الإرجاع:**
[ITable](../../com.aspose.slides/itable) - الجدول الذي تم إضافته إلى مجموعة الأشكال.