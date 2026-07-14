---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Represents data used for a chart plotting.
type: docs
url: /ar/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

يمثل البيانات المستخدمة في رسم مخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | يحصل على مصنع الخلايا لإنشاء الخلايا المستخدمة لسلاسل المخطط أو الفئات. |
| [getSeries()](#getSeries--) | يحصل على السلسلة. |
| [getSeriesGroups()](#getSeriesGroups--) | يحصل على مجموعات السلسلة. |
| [getCategories()](#getCategories--) | يحصل على الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا كانت الخاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) هي false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | إذا كانت false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) ترجع null والبيانات في خاصية (\#getCategories.getCategories) تُستخدم لكل من السلاسل الأساسية والثانوية. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | إذا كانت false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) ترجع null والبيانات في خاصية (\#getCategories.getCategories) تُستخدم لكل من السلاسل الأساسية والثانوية. |
| [getSecondaryCategories()](#getSecondaryCategories--) | يحصل على الفئات الثانوية إذا كانت الخاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) هي true. |
| [readWorkbookStream()](#readWorkbookStream--) | يكتب ملف Excel المضمن داخليًا إلى دفق في الذاكرة. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | يُهيئ ملف Excel المضمن داخليًا بالقيمة المحددة من قبل المستخدم. |
| [setRange(String formula)](#setRange-java.lang.String-) | يضبط نطاق بيانات المخطط. |
| [getRange()](#getRange--) | يحصل على نطاق بيانات المخطط. |
| [getDataSourceType()](#getDataSourceType--) | يمثل مصدر البيانات للمخطط |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | يمثل مسار المصنف الخارجي إذا كان مصدر البيانات خارجيًا، وإلا null. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | يحصل على نوع المصنف المضمن. |
| [switchRowColumn()](#switchRowColumn--) | تبديل البيانات عبر المحور. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | يضبط المصنف الخارجي كمصدر بيانات للمخطط. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | يضبط المصنف الخارجي كمصدر بيانات للمخطط. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

يحصل على مصنع الخلايا لإنشاء الخلايا المستخدمة لسلاسل المخطط أو الفئات. قراءة فقط [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**الإرجاع:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

يحصل على السلسلة. قراءة فقط [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**الإرجاع:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

يحصل على مجموعات السلسلة. قراءة فقط [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) كل مجموعة من السلاسل تحتوي على سلاسل بأنواع يمكن دمجها. مجموعات أنواع السلاسل القابلة للدمج معرفة ومُوضَّحة باستخدام تعداد CombinableSeriesTypesGroup. كما أن كل مجموعة من السلاسل تحتوي على سلاسل تُرسم إما على المحور الأساسي أو على المحور الثانوي (ليس كلا الحالتين في مجموعة واحدة). لذا، مبدأ تجميع السلاسل هو التجميع حسب مجموعات الأنواع المذكورة أعلاه وحسب نوع الرسم على الأساسي/الثانوي. 2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة المشتركة لكل سلسلة في المجموعة ("series group properties"). "Series group properties" في الفئة ChartSeriesGroup قابلة للقراءة والكتابة. كل من "series group properties" يمكن أن يكون له عرض للقراءة فقط في الفئة ChartSeries.

**الإرجاع:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

يحصل على الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا كانت الخاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) هي false). قراءة فقط [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

إذا كانت الخاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) هي false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) ترجع null وتُستخدم البيانات في خاصية (\#getCategories.getCategories) لكل من السلاسل الأساسية والثانوية. إذا كانت الخاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) هي true فإن البيانات في خاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية وتُستخدم البيانات في خاصية (\#getCategories.getCategories) للسلاسل الأساسية.

**الإرجاع:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

إذا كانت false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) ترجع null وتُستخدم البيانات في خاصية (\#getCategories.getCategories) لكل من السلاسل الأساسية والثانوية. إذا كانت true فإن البيانات في خاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية وتُستخدم البيانات في خاصية (\#getCategories.getCategories) للسلاسل الأساسية. قابل للقراءة والكتابة Boolean.

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
public abstract void setUseSecondaryCategories(boolean value)
```

إذا كانت false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) ترجع null وتُستخدم البيانات في خاصية (\#getCategories.getCategories) لكل من السلاسل الأساسية والثانوية. إذا كانت true فإن البيانات في خاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية وتُستخدم البيانات في خاصية (\#getCategories.getCategories) للسلاسل الأساسية. قابل للقراءة والكتابة Boolean.

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
public abstract IChartCategoryCollection getSecondaryCategories()
```

يحصل على الفئات الثانوية إذا كانت الخاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) هي true. قراءة فقط [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

إذا كانت الخاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) هي false فإن هذه الخاصية (\#getSecondaryCategories.getSecondaryCategories) ترجع null وتُستخدم البيانات في خاصية (\#getCategories.getCategories) لكل من السلاسل الأساسية والثانوية. إذا كانت الخاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) هي true فإن البيانات في هذه الخاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية وتُستخدم البيانات في خاصية (\#getCategories.getCategories) للسلاسل الأساسية.

**الإرجاع:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

يكتب ملف Excel المضمن داخليًا إلى دفق في الذاكرة.

**الإرجاع:**
byte[] - إرجاع مصفوفة من البايتات تحتوي على نسخة من ملف Excel المضمن داخليًا.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

يُهيئ ملف Excel المضمن داخليًا بالقيمة المحددة من قبل المستخدم.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| ms | byte[] |  |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

يضبط نطاق بيانات المخطط. سيتم تحديث السلاسل والفئات بناءً على النطاق الجديد للبيانات. إذا كان عدد السلاسل في نطاق البيانات أكبر من عدد السلاسل في بيانات المخطط، فسيتم إضافة سلاسل إضافية من نفس نوع السلسلة الأخيرة في المجموعة الحالية إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| formula | java.lang.String | صيغة نطاق بيانات الخلايا. مثال: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
### getRange() {#getRange--}
```
public abstract String getRange()
```

يحصل على نطاق بيانات المخطط.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```


**الإرجاع:**
java.lang.String - صيغة نطاق بيانات الخلايا. مثال: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

يمثل مصدر البيانات للمخطط

**الإرجاع:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

يمثل مسار المصنف الخارجي إذا كان مصدر البيانات خارجيًا، وإلا null

**الإرجاع:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

يحصل على نوع المصنف المضمن. إرجاع [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) إذا كان DataSourceType (\#getDataSourceType.getDataSourceType) هو [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). قراءة فقط [WorkbookType](../../com.aspose.slides/workbooktype).

**الإرجاع:**
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

**المعاملات:**
| المعامل | النوع | الوصف |
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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| workbookPath | java.lang.String | مسار المصنف الهدف |
| updateChartData | boolean | إذا كان القيمة false فسيتم تحديث مسار المصنف فقط. لن يتم تحميل بيانات المخطط وتحديثها من المصنف الهدف. يمكن استخدام ذلك عندما لا يكون المصنف الهدف موجودًا أو غير متاح. إذا كانت القيمة true فسيتم تحديث بيانات المخطط من المصنف الهدف. |