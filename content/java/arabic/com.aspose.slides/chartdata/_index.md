---
title: ChartData
second_title: مرجع API ل Aspose.Slides للغة Java
description: يمثل البيانات المستخدمة في رسم المخطط.
type: docs
url: /ar/com.aspose.slides/chartdata/
---
**التورّث:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

يمثل البيانات المستخدمة لرسم مخطط.
## الطرق

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | يحصل على مصنع الخلايا لإنشاء خلايا تُستخدم في سلاسل المخطط أو الفئات. |
| [getSeries()](#getSeries--) | يحصل على السلاسل. |
| [getSeriesGroups()](#getSeriesGroups--) | يحصل على مجموعات السلاسل. |
| [getCategories()](#getCategories--) | يحصل على الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا كانت خاصية #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) قيمتها false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | إذا كانت false فإن خاصية #getSecondaryCategories.getSecondaryCategories تُرجع null وتُستخدم البيانات في خاصية #getCategories.getCategories لكلا السلسلتين الأساسية والثانوية. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | إذا كانت false فإن خاصية #getSecondaryCategories.getSecondaryCategories تُرجع null وتُستخدم البيانات في خاصية #getCategories.getCategories لكلا السلسلتين الأساسية والثانوية. |
| [getSecondaryCategories()](#getSecondaryCategories--) | يحصل على الفئات الثانوية إذا كانت خاصية #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) قيمتها true. |
| [readWorkbookStream()](#readWorkbookStream--) | يكتب دفتر عمل Excel المتضمن داخليًا إلى تدفق في الذاكرة. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | يُهيئ دفتر عمل Excel المتضمن داخليًا بالقيمة المحددة من قبل المستخدم. |
| [getDataSourceType()](#getDataSourceType--) | يمثل مسار دفتر العمل الخارجي إذا كان مصدر البيانات خارجيًا، وإلا null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | يمثل مصدر بيانات المخطط. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | يحصل على نوع دفتر العمل المضمن. |
| [getRange()](#getRange--) | يحصل على نطاق بيانات المخطط. |
| [setRange(String formula)](#setRange-java.lang.String-) | يضبط نطاق بيانات المخطط. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | يضبط دفتر العمل الخارجي كمصدر بيانات للمخطط. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | يضبط دفتر العمل الخارجي كمصدر بيانات للمخطط. |
| [switchRowColumn()](#switchRowColumn--) | يبدّل البيانات على المحور. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

يحصل على مصنع الخلايا لإنشاء خلايا تُستخدم في سلاسل المخطط أو الفئات. قراءة فقط [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**الإرجاع:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

يحصل على السلاسل. قراءة فقط [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**الإرجاع:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

يحصل على مجموعات السلاسل. قراءة فقط [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) كل مجموعة من السلاسل تحتوي على سلاسل بأنواع يمكن دمجها. تم تعريف مجموعات أنواع السلاسل القابلة للدمج وتوضيحها باستخدام تعداد CombinableSeriesTypesGroup. أيضًا كل مجموعة من السلاسل تحتوي على سلاسل تُرسم إما على المحاور الأساسية أو على المحاور الثانوية (ليس كلا الحالتين في مجموعة واحدة). وبالتالي مبدأ تجميع السلاسل هو التجميع حسب مجموعات الأنواع المذكورة أعلاه وحسب نوع الرسم الأساسي/الثانوي. 2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة التي تُشترك بينها جميع السلاسل في المجموعة ("خصائص مجموعة السلسلة"). "خصائص مجموعة السلسلة" في الفئة ChartSeriesGroup هي قراءة/كتابة. كل من "خصائص مجموعة السلسلة" يمكن أن يكون لها نسخة قراءة فقط في الفئة ChartSeries.

**الإرجاع:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

يحصل على الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا كانت خاصية #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) قيمتها false). قراءة فقط [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

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

--------------------

إذا كانت خاصية #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) قيمتها false، فإن خاصية (#getSecondaryCategories.getSecondaryCategories) تُرجع null وتُستخدم البيانات في خاصية #getCategories.getCategories لكلٍ من السلاسل الأساسية والثانوية. إذا كانت الخاصية قيمتها true، فإن البيانات في خاصية (#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية والبيانات في خاصية #getCategories.getCategories تُستخدم للسلاسل الأساسية.

**الإرجاع:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

إذا كانت false فإن خاصية #getSecondaryCategories.getSecondaryCategories تُرجع null وتُستخدم البيانات في خاصية #getCategories.getCategories لكلٍ من السلاسل الأساسية والثانوية. إذا كانت true فإن البيانات في خاصية #getSecondaryCategories.getSecondaryCategories تُستخدم للسلاسل الثانوية والبيانات في خاصية #getCategories.getCategories تُستخدم للسلاسل الأساسية. قراءة/كتابة boolean.

--------------------

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

إذا كانت false فإن خاصية #getSecondaryCategories.getSecondaryCategories تُرجع null وتُستخدم البيانات في خاصية #getCategories.getCategories لكلٍ من السلاسل الأساسية والثانوية. إذا كانت true فإن البيانات في خاصية #getSecondaryCategories.getSecondaryCategories تُستخدم للسلاسل الثانوية والبيانات في خاصية #getCategories.getCategories تُستخدم للسلاسل الأساسية. قراءة/كتابة boolean.

--------------------

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

يحصل على الفئات الثانوية إذا كانت خاصية #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) قيمتها true. قراءة فقط [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

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

--------------------

إذا كانت خاصية #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) قيمتها false، فإن خاصية (#getSecondaryCategories.getSecondaryCategories) تُرجع null وتُستخدم البيانات في خاصية #getCategories.getCategories لكلٍ من السلاسل الأساسية والثانوية. إذا كانت الخاصية قيمتها true، فإن البيانات في خاصية #getSecondaryCategories.getSecondaryCategories تُستخدم للسلاسل الثانوية والبيانات في خاصية #getCategories.getCategories تُستخدم للسلاسل الأساسية.

**الإرجاع:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

يكتب دفتر عمل Excel المتضمن داخليًا إلى تدفق في الذاكرة.

**الإرجاع:**
byte[] - إرجاع مثيل من مصفوفة بايت تحتوي على نسخة من دفتر عمل Excel المتضمن داخليًا.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

يُهيئ دفتر عمل Excel المتضمن داخليًا بالقيمة المحددة من قبل المستخدم.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| ms | byte[] | تيار المستخدم الذي يحتوي على دفتر عمل Excel بالكامل. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

يمثل مسار دفتر العمل الخارجي إذا كان مصدر البيانات خارجيًا، وإلا null.

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

يحصل على نوع دفتر العمل المضمن. إرجاع [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) إذا كان DataSourceType (#getDataSourceType.getDataSourceType) هو [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). قراءة فقط [WorkbookType](../../com.aspose.slides/workbooktype).

**الإرجاع:**
int

### getRange() {#getRange--}
```
public final String getRange()
```

يحصل على نطاق بيانات المخطط.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>       String result = ((ChartData)chart.getChartData()).getRange();
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**الإرجاع:**
java.lang.String - صيغة نطاق بيانات الخلايا. مثال: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

يضبط نطاق بيانات المخطط. سيتم تحديث السلاسل والفئات بناءً على نطاق البيانات الجديد. إذا كان عدد السلاسل في نطاق البيانات أكبر من عدد السلاسل في بيانات المخطط، فستضاف سلاسل إضافية من نفس نوع السلسلة الأخيرة في المجموعة الحالية إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| formula | java.lang.String | صيغة نطاق بيانات الخلايا. مثال: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

يضبط دفتر العمل الخارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من دفتر العمل الهدف.

--------------------

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| workbookPath | java.lang.String | مسار دفتر العمل الهدف |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

يضبط دفتر العمل الخارجي كمصدر بيانات للمخطط.

--------------------

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| workbookPath | java.lang.String | مسار دفتر العمل الهدف |
| updateChartData | boolean | إذا كانت القيمة false سيتم تحديث مسار دفتر العمل فقط. لن يتم تحميل وتحديث بيانات المخطط من دفتر العمل الهدف. يمكن استخدام ذلك عندما لا يوجد دفتر العمل الهدف أو غير متاح. إذا كانت القيمة true سيتم تحديث بيانات المخطط من دفتر العمل الهدف. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

بدل البيانات على المحور. البيانات التي تُرسم على المحور X ستنتقل إلى المحور Y والعكس بالعكس.