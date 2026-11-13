---
title: ChartData
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ Java
description: يمثل البيانات المستخدمة لرسم المخطط.
type: docs
url: /ar/com.aspose.slides/chartdata/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

يمثل البيانات المستخدمة لرسم المخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | يحصل على مصنع الخلايا لإنشاء الخلايا المستخدمة لسلسلة المخطط أو الفئات. |
| [getSeries()](#getSeries--) | يحصل على السلاسل. |
| [getSeriesGroups()](#getSeriesGroups--) | يحصل على مجموعات السلاسل. |
| [getCategories()](#getCategories--) | يحصل على الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا كانت الخاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) مساوية لـ false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | إذا كان false فإن الخاصية \#getSecondaryCategories.getSecondaryCategories تُعيد null وتُستخدم البيانات في الخاصية \#getCategories.getCategories لكل من السلاسل الأساسية والثانوية. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | إذا كان false فإن الخاصية \#getSecondaryCategories.getSecondaryCategories تُعيد null وتُستخدم البيانات في الخاصية \#getCategories.getCategories لكل من السلاسل الأساسية والثانوية. |
| [getSecondaryCategories()](#getSecondaryCategories--) | يحصل على الفئات الثانوية إذا كانت الخاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) مساوية لـ true. |
| [readWorkbookStream()](#readWorkbookStream--) | يكتب دفتر العمل Excel الداخلي إلى تدفق في الذاكرة. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | يجهز دفتر العمل Excel الداخلي بقيمة محددة من قبل المستخدم. |
| [getDataSourceType()](#getDataSourceType--) | يمثل مسار دفتر العمل الخارجي إذا كان مصدر البيانات خارجيًا، وإلا null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | يمثل مصدر بيانات المخطط. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | يحصل على نوع دفتر العمل المضمن. |
| [getRange()](#getRange--) | يحصل على نطاق بيانات المخطط. |
| [setRange(String formula)](#setRange-java.lang.String-) | يضبط نطاق بيانات المخطط. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | يعين دفتر العمل الخارجي كمصدر بيانات للمخطط. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | يعين دفتر العمل الخارجي كمصدر بيانات للمخطط. |
| [refreshData()](#refreshData--) | يقوم بتحديث بيانات المخطط بإعادة تحميلها من دفتر العمل المصدر. |
| [switchRowColumn()](#switchRowColumn--) | تبديل البيانات عبر المحور. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

يستعيد مصنع الخلايا لإنشاء الخلايا المستخدمة لسلسلة المخطط أو الفئات. للقراءة فقط [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**القيمة المرجعة:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

يحصل على السلسلة. للقراءة فقط [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**القيمة المرجعة:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

يحصل على مجموعات السلاسل. للقراءة فقط [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) كل مجموعة من السلاسل تحتوي على سلاسل بأنواع قابلة للجمع. تُعرّف مجموعات الأنواع القابلة للجمع وتُوصف باستخدام تعداد CombinableSeriesTypesGroup. كما أن كل مجموعة من السلاسل تحتوي على سلاسل تُرسم إما على المحاور الأساسية أو على المحاور الثانوية (ليس كلا الحالتين في مجموعة واحدة). لذا، مبدأ تجميع السلاسل هو التجميع حسب مجموعات الأنواع المذكورة أعلاه وحسب نوع الرسم الأساسي/الثانوي. 2) مجموعة السلاسل تحتوي على بعض خصائص السلاسل التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلسلة"). "خصائص مجموعة السلسلة" في فئة ChartSeriesGroup هي قابل للقراءة والكتابة. كل واحدة من "خصائص مجموعة السلسلة" يمكن أن يكون لها تمثيل للقراءة فقط في فئة ChartSeries.

**القيمة المرجعة:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

يحصل على الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا كانت الخاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) مساوية لـ false). للقراءة فقط [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> مثال. ما الفئات المرتبطة بالسلسلة - ChartData.getCategories() أو ChartData.getSecondaryCategories()؟
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


إذا كانت الخاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) مساوية لـ false فإن الخاصية (\#getSecondaryCategories.getSecondaryCategories) تُعيد null وتُستخدم البيانات في الخاصية \#getCategories.getCategories لكل من السلاسل الأساسية والثانوية. إذا كانت الخاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) مساوية لـ true فإن البيانات في الخاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية والبيانات في الخاصية \#getCategories.getCategories تُستخدم للسلاسل الأساسية.

**القيمة المرجعة:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

إذا كان false فإن الخاصية \#getSecondaryCategories.getSecondaryCategories تُعيد null وتُستخدم البيانات في الخاصية \#getCategories.getCategories لكل من السلاسل الأساسية والثانوية. إذا كان true فإن البيانات في الخاصية \#getSecondaryCategories.getSecondaryCategories تُستخدم للسلاسل الثانوية والبيانات في الخاصية \#getCategories.getCategories تُستخدم للسلاسل الأساسية. قابل للقراءة والكتابة من نوع boolean.

--------------------

> ```
> مثال. ما الفئات المرتبطة بالسلسلة - ChartData.getCategories() أو ChartData.getSecondaryCategories()?
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
public final void setUseSecondaryCategories(boolean value)
```

إذا كان false فإن الخاصية \#getSecondaryCategories.getSecondaryCategories تُعيد null وتُستخدم البيانات في الخاصية \#getCategories.getCategories لكل من السلاسل الأساسية والثانوية. إذا كان true فإن البيانات في الخاصية \#getSecondaryCategories.getSecondaryCategories تُستخدم للسلاسل الثانوية والبيانات في الخاصية \#getCategories.getCategories تُستخدم للسلاسل الأساسية. قابل للقراءة والكتابة من نوع boolean.

--------------------

> ```
> مثال. ما الفئات المرتبطة بالسلسلة - ChartData.getCategories() أو ChartData.getSecondaryCategories()؟
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

يحصل على الفئات الثانوية إذا كانت الخاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) مساوية لـ true. للقراءة فقط [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> مثال. ما الفئات المرتبطة بالسلسلة - ChartData.getCategories() أو ChartData.getSecondaryCategories()?
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


إذا كانت الخاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) مساوية لـ false فإن الخاصية (\#getSecondaryCategories.getSecondaryCategories) تُعيد null وتُستخدم البيانات في \#getCategories.getCategories لكل من السلاسل الأساسية والثانوية. إذا كانت الخاصية \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) مساوية بـ true فإن البيانات في الخاصية \#getSecondaryCategories.getSecondaryCategories تُستخدم للسلاسل الثانوية والبيانات في \#getCategories.getCategories تُستخدم للسلاسل الأساسية.

**القيمة المرجعة:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

يكتب دفتر العمل Excel الداخلي إلى تدفق في الذاكرة.

**القيمة المرجعة:**
byte[] - يُعيد كائن من مصفوفة بايت يحتوي على نسخة من دفتر العمل Excel الداخلي.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

يمهد دفتر العمل Excel الداخلي بقيمة محددة من قبل المستخدم.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| ms | byte[] | التدفق المقدم من قبل المستخدم والذي يحتوي على دفتر العمل Excel بالكامل. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

يمثل مسار دفتر العمل الخارجي إذا كان مصدر البيانات خارجيًا، وإلا null.

**القيمة المرجعة:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

يمثل مصدر بيانات المخطط.

**القيمة المرجعة:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

يحصل على نوع دفتر العمل المضمن. يُعيد [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) إذا كان DataSourceType (\#getDataSourceType.getDataSourceType) هو [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). للقراءة فقط [WorkbookType](../../com.aspose.slides/workbooktype).

**القيمة المرجعة:**
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

**القيمة المرجعة:**
java.lang.String - صيغة نطاق بيانات الخلايا. مثال: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

يضبط نطاق بيانات المخطط. سيتم تحديث السلاسل والفئات بناءً على النطاق الجديد. إذا كان عدد السلاسل في نطاق البيانات أكبر من عدد السلاسل في بيانات المخطط، فسيتم إضافة سلاسل إضافية من نفس نوع السلسلة الأخيرة في المجموعة الحالية إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| formula | java.lang.String | صيغة نطاق بيانات الخلايا. مثال: "Sheet1!$A$1:$C$4" ، "SomeSheetName!A1:B100" ، "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

يعين دفتر العمل الخارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من دفتر العمل الهدف.

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| workbookPath | java.lang.String | مسار دفتر العمل الهدف |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

يعين دفتر العمل الخارجي كمصدر بيانات للمخطط.

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| workbookPath | java.lang.String | مسار دفتر العمل الهدف |
| updateChartData | boolean | إذا كانت القيمة false سيتم تحديث مسار دفتر العمل فقط. لن يتم تحميل بيانات المخطط ولا تحديثها من دفتر العمل الهدف. يمكن استخدام ذلك عندما لا يكون دفتر العمل الهدف موجودًا أو غير متاح. إذا كانت القيمة true سيتم تحديث بيانات المخطط من دفتر العمل الهدف. |

### refreshData() {#refreshData--}
```
public final void refreshData()
```

يقوم بتحديث بيانات المخطط بإعادة تحميلها من دفتر العمل المصدر.

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      presentation.dispose();
>  }
> ```

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

تبديل البيانات عبر المحور. البيانات المرسومة على المحور X ستنتقل إلى المحور Y والعكس بالعكس.