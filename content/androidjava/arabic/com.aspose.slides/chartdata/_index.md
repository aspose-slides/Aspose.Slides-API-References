---
title: ChartData
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل البيانات المستخدمة في رسم المخططات.
type: docs
url: /ar/com.aspose.slides/chartdata/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

يمثل البيانات المستخدمة في رسم مخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | يحصل على مصنع الخلايا لإنشاء الخلايا المستخدمة في سلسلة المخطط أو الفئات. |
| [getSeries()](#getSeries--) | يحصل على السلاسل. |
| [getSeriesGroups()](#getSeriesGroups--) | يحصل على مجموعات السلاسل. |
| [getCategories()](#getCategories--) | يحصل على الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا كانت خاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) هي false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | إذا كانت false فإن خاصية \#getSecondaryCategories.getSecondaryCategories تُعيد null وتُستخدم البيانات في خاصية \#getCategories.getCategories لكل من السلاسل الأساسية والثانوية. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | إذا كانت false فإن خاصية \#getSecondaryCategories.getSecondaryCategories تُعيد null وتُستخدم البيانات في خاصية \#getCategories.getCategories لكل من السلاسل الأساسية والثانوية. |
| [getSecondaryCategories()](#getSecondaryCategories--) | يحصل على الفئات الثانوية إذا كانت خاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) هي true. |
| [readWorkbookStream()](#readWorkbookStream--) | يكتب المصنف الداخلي لـ Excel إلى تدفق في الذاكرة. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | يقوم بتهيئة المصنف الداخلي لـ Excel بالقيمة المحددة من قبل المستخدم. |
| [getDataSourceType()](#getDataSourceType--) | يمثل مسار المصنف الخارجي إذا كان مصدر البيانات خارجيًا، وإلا null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | يمثل مصدر بيانات المخطط. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | يحصل على نوع المصنف المضمّن. |
| [getRange()](#getRange--) | يحصل على نطاق بيانات المخطط. |
| [setRange(String formula)](#setRange-java.lang.String-) | تعيين نطاق بيانات المخطط. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | يعين المصنف الخارجي كمصدر بيانات للمخطط. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | يعين المصنف الخارجي كمصدر بيانات للمخطط. |
| [switchRowColumn()](#switchRowColumn--) | تبديل البيانات عبر المحور. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

يحصل على مصنع الخلايا لإنشاء الخلايا المستخدمة في سلسلة المخطط أو الفئات. للقراءة فقط [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**الإرجاع:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

يحصل على السلاسل. للقراءة فقط [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**الإرجاع:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

يحصل على مجموعات السلاسل. للقراءة فقط [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

1) كل مجموعة من السلاسل تحتوي على سلاسل ذات أنواع قابلة للجمع. تُعرف مجموعات الأنواع القابلة للجمع وتُوصف باستخدام تعداد CombinableSeriesTypesGroup. كما أن كل مجموعة من السلاسل تحتوي على سلاسل تُرسم إما على المحاور الأساسية أو على المحاور الثانوية (ليس كلاً من الحالتين في مجموعة واحدة). لذا، مبدأ تجميع السلاسل هو التجميع حسب مجموعات الأنواع المذكورة أعلاه وحسب نوع الرسم الأساسي/الثانوي. 2) مجموعة السلاسل تحتوي على بعض خصائص السلاسل المشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلاسل"). "خصائص مجموعة السلاسل" في فئة ChartSeriesGroup قابلة للقراءة والكتابة. كل من "خصائص مجموعة السلاسل" يمكن أن يكون لها تمثيل للقراءة فقط في فئة ChartSeries.

**الإرجاع:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

يحصل على الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا كانت خاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) هي false). للقراءة فقط [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // الفئات المرتبطة هي series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // الفئات المرتبطة هي series.getChart().getChartData().getCategories()
>  }
> ```


إذا كانت خاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) هي false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) تُعيد null وتُستخدم البيانات في خاصية \#getCategories.getCategories لكل من السلاسل الأساسية والثانوية. إذا كانت خاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) هي true فإن البيانات في خاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية والبيانات في خاصية \#getCategories.getCategories تُستخدم للسلاسل الأساسية.

**الإرجاع:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

إذا كانت false فإن خاصية \#getSecondaryCategories.getSecondaryCategories تُعيد null وتُستخدم البيانات في خاصية \#getCategories.getCategories لكل من السلاسل الأساسية والثانوية. إذا كانت true فإن البيانات في خاصية \#getSecondaryCategories.getSecondaryCategories تُستخدم للسلاسل الثانوية والبيانات في خاصية \#getCategories.getCategories تُستخدم للسلاسل الأساسية. للقراءة والكتابة Boolean.

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // الفئات المرتبطة هي series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // الفئات المرتبطة هي series.getChart().getChartData().getCategories()
>  }
> ```

**الإرجاع:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

إذا كانت false فإن خاصية \#getSecondaryCategories.getSecondaryCategories تُعيد null وتُستخدم البيانات في خاصية \#getCategories.getCategories لكل من السلاسل الأساسية والثانوية. إذا كانت true فإن البيانات في خاصية \#getSecondaryCategories.getSecondaryCategories تُستخدم للسلاسل الثانوية والبيانات في خاصية \#getCategories.getCategories تُستخدم للسلاسل الأساسية. للقراءة والكتابة Boolean.

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // الفئات المرتبطة هي series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // الفئات المرتبطة هي series.getChart().getChartData().getCategories()
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

يحصل على الفئات الثانوية إذا كانت خاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) هي true. للقراءة فقط [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // الفئات المرتبطة هي series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // الفئات المرتبطة هي series.getChart().getChartData().getCategories()
>  }
> ```


إذا كانت خاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) هي false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) تُعيد null وتُستخدم البيانات في خاصية \#getCategories.getCategories لكل من السلاسل الأساسية والثانوية. إذا كانت خاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) هي true فإن البيانات في خاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية والبيانات في خاصية \#getCategories.getCategories تُستخدم للسلاسل الأساسية.

**الإرجاع:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

يكتب المصنف الداخلي لـ Excel إلى تدفق في الذاكرة.

**الإرجاع:**
byte[] - إرجاع نسخة من مصفوفة بايت تحتوي على نسخة من المصنف الداخلي لـ Excel.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

يتهيئ المصنف الداخلي لـ Excel بالقيمة المحددة من قبل المستخدم.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| ms | byte[] | تدفق المستخدم الذي يحتوي على المصنف الكامل لـ Excel. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

يمثل مسار المصنف الخارجي إذا كان مصدر البيانات خارجيًا، وإلا null.

**الإرجاع:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

يمثل مصدر بيانات المخطط.

**الإرجاع:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

يحصل على نوع المصنف المضمّن. إرجاع [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) إذا كان DataSourceType (\#getDataSourceType.getDataSourceType) هو [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). للقراءة فقط [WorkbookType](../../com.aspose.slides/workbooktype).

**الإرجاع:**
int

### getRange() {#getRange--}
```
public final String getRange()
```

يحصل على نطاق بيانات المخطط.

> ```
> Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>       String result = ((ChartData)chart.getChartData()).getRange();
>   finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**الإرجاع:**
java.lang.String - صيغة نطاق بيانات الخلايا. مثال: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

تعيين نطاق بيانات المخطط. سيتم تحديث السلاسل والفئات بناءً على نطاق البيانات الجديد. إذا كان عدد السلاسل في نطاق البيانات أكبر من عدد السلاسل في بيانات المخطط، فستُضاف سلاسل إضافية من نفس نوع السلسلة الأخيرة في المجموعة الحالية إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| formula | java.lang.String | صيغة نطاق بيانات الخلايا. مثال: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

يعين المصنف الخارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من المصنف الهدف.

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>     if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| workbookPath | java.lang.String | مسار المصنف الهدف |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

يعين المصنف الخارجي كمصدر بيانات للمخطط.

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>      IChartData chartData = chart.getChartData();
>      ((ChartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| workbookPath | java.lang.String | مسار المصنف الهدف |
| updateChartData | boolean | إذا كانت القيمة false سيُحدّث مسار المصنف فقط. لن يتم تحميل بيانات المخطط وتحديثها من المصنف الهدف. يمكن استخدام ذلك عندما لا يكون المصنف الهدف موجودًا أو غير متاح. إذا كانت القيمة true سيتم تحديث بيانات المخطط من المصنف الهدف. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

تبديل البيانات عبر المح轴. البيانات المرسومة على المحور X ستنتقل إلى المحور Y والعكس بالعكس.