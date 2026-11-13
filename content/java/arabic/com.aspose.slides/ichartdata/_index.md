---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: تمثل البيانات المستخدمة في رسم المخططات.
type: docs
url: /ar/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

تمثل البيانات المستخدمة في رسم المخططات.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | يسترجع مصنع الخلايا لإنشاء الخلايا المستخدمة لسلاسل المخطط أو الفئات. |
| [getSeries()](#getSeries--) | يسترجع السلاسل. |
| [getSeriesGroups()](#getSeriesGroups--) | يسترجع مجموعات السلاسل. |
| [getCategories()](#getCategories--) | يسترجع الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا كانت خاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) = false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | إذا كانت false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) تُرجع null ويتم استخدام البيانات في خاصية (\#getCategories.getCategories) لكل من السلاسل الأساسية والثانوية. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | إذا كانت false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) تُرجع null ويتم استخدام البيانات في خاصية (\#getCategories.getCategories) لكل من السلاسل الأساسية والثانوية. |
| [getSecondaryCategories()](#getSecondaryCategories--) | يسترجع الفئات الثانوية إذا كانت خاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) = true. |
| [readWorkbookStream()](#readWorkbookStream--) | يكتب مصنف Excel الداخلي إلى تدفق في الذاكرة. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | يهيئ مصنف Excel الداخلي بالقيمة المحددة من قبل المستخدم. |
| [setRange(String formula)](#setRange-java.lang.String-) | تعيين نطاق بيانات المخطط. |
| [getRange()](#getRange--) | يسترجع نطاق بيانات المخطط. |
| [getDataSourceType()](#getDataSourceType--) | يمثل مصدر بيانات المخطط. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | يمثل مسار المصنف الخارجي إذا كان مصدر البيانات خارجيًا، وإلا تكون القيمة null. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | يسترجع نوع المصنف المدمج. |
| [switchRowColumn()](#switchRowColumn--) | تبديل البيانات عبر المحور. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | يضبط المصنف الخارجي كمصدر بيانات للمخطط. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | يضبط المصنف الخارجي كمصدر بيانات للمخطط. |
| [refreshData()](#refreshData--) | يقوم بتحديث بيانات المخطط عن طريق إعادة تحميلها من المصنف المصدر. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

يسترجع مصنع الخلايا لإنشاء الخلايا المستخدمة لسلاسل المخطط أو الفئات. للقراءة فقط [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**القيمة المرجعة:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

يسترجع السلاسل. للقراءة فقط [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**القيمة المرجعة:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

يسترجع مجموعات السلاسل. للقراءة فقط [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) كل مجموعة من السلاسل تحتوي على سلاسل من أنواع يمكن دمجها. تم تعريف مجموعات الأنواع القابلة للدمج ووصفها باستخدام تعداد CombinableSeriesTypesGroup. كذلك كل مجموعة من السلاسل تحتوي على سلاسل تُرسم إما على المحاور الأساسية أو على المحاور الثانوية (ليس كليهما في مجموعة واحدة). لذلك، مبدأ تجميع السلاسل هو التجميع حسب مجموعات الأنواع المذكورة أعلاه حسب نوع الرسم الأساسي/الثانوي. 2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة المشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلسلة"). "خصائص مجموعة السلسلة" في فئة ChartSeriesGroup قابلة للقراءة والكتابة. كل من "خصائص مجموعة السلسلة" يمكن أن يكون له تمثيل للقراءة فقط في فئة ChartSeries.

**القيمة المرجعة:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

يسترجع الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا كانت خاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) = false). للقراءة فقط [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

إذا كانت خاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) = false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) تُرجع null ويتم استخدام البيانات في خاصية (\#getCategories.getCategories) لكل من السلاسل الأساسية والثانوية. إذا كانت الخاصية = true فإن البيانات في خاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية والبيانات في خاصية (\#getCategories.getCategories) تُستخدم للسلاسل الأساسية.

**القيمة المرجعة:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

إذا كانت false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) تُرجع null ويتم استخدام البيانات في خاصية (\#getCategories.getCategories) لكل من السلاسل الأساسية والثانوية. إذا كانت true فإن البيانات في خاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية والبيانات في خاصية (\#getCategories.getCategories) تُستخدم للسلاسل الأساسية. قابل للقراءة والكتابة من نوع boolean.

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


**القيمة المرجعة:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

إذا كانت false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) تُرجع null ويتم استخدام البيانات في خاصية (\#getCategories.getCategories) لكل من السلاسل الأساسية والثانوية. إذا كانت true فإن البيانات في خاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية والبيانات في خاصية (\#getCategories.getCategories) تُستخدم للسلاسل الأساسية. قابل للقراءة والكتابة من نوع boolean.

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


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

يسترجع الفئات الثانوية إذا كانت خاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) = true. للقراءة فقط [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

إذا كانت خاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) = false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) تُرجع null ويتم استخدام البيانات في خاصية (\#getCategories.getCategories) لكل من السلاسل الأساسية والثانوية. إذا كانت الخاصية = true فإن البيانات في خاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية والبيانات في خاصية (\#getCategories.getCategories) تُستخدم للسلاسل الأساسية.

**القيمة المرجعة:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

يكتب مصنف Excel الداخلي إلى تدفق في الذاكرة.

**القيمة المرجعة:**
byte[] - إرجاع مصفوفة من البايتات تحتوي على نسخة من مصنف Excel الداخلي.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

يهيئ مصنف Excel الداخلي بالقيمة المحددة من قبل المستخدم.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| ms | byte[] | التدفق المزوَّد من المستخدم والذي يحتوي على كامل مصنف Excel. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

تعيين نطاق بيانات المخطط. سيتم تحديث السلاسل والفئات بناءً على نطاق البيانات الجديد. إذا كان عدد السلاسل في نطاق البيانات أكبر من عدد السلاسل في بيانات المخطط، فستُضاف سلاسل إضافية من نفس نوع السلسلة الأخيرة في المجموعة الحالية إلى نهاية المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| formula | java.lang.String | صيغة نطاق بيانات الخلايا. مثال: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

يسترجع نطاق بيانات المخطط.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**القيمة المرجعة:**
java.lang.String - صيغة نطاق بيانات الخلايا. مثال: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

يمثل مصدر بيانات المخطط

**القيمة المرجعة:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

يمثل مسار المصنف الخارجي إذا كان مصدر البيانات خارجيًا، وإلا تكون القيمة null

**القيمة المرجعة:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

يسترجع نوع المصنف المدمج. يُرجع [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) إذا كان DataSourceType (\#getDataSourceType.getDataSourceType) = [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). للقراءة فقط [WorkbookType](../../com.aspose.slides/workbooktype).

**القيمة المرجعة:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

تبديل البيانات عبر المحور. البيانات المرسومة على المحور X ستنتقل إلى المحور Y والعكس بالعكس.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

يضبط المصنف الخارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من المصنف الهدف.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| workbookPath | java.lang.String | مسار المصنف الهدف |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

يضبط المصنف الخارجي كمصدر بيانات للمخطط.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| workbookPath | java.lang.String | مسار المصنف الهدف |
| updateChartData | boolean | إذا كانت القيمة false سيتم تحديث مسار المصنف فقط. لن يتم تحميل بيانات المخطط وتحديثها من المصنف الهدف. يمكن استخدام ذلك عندما لا يكون المصنف الهدف موجودًا أو غير متاح. إذا كانت القيمة true سيتم تحديث بيانات المخطط من المصنف الهدف. |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```

يقوم بتحديث بيانات المخطط عن طريق إعادة تحميلها من المصنف المصدر.

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```