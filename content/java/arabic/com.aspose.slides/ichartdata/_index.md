---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: يمثل البيانات المستخدمة لرسم مخطط.
type: docs
url: /ar/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

يمثل البيانات المستخدمة لرسم مخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | يحصل على مصنع الخلايا لإنشاء الخلايا المستخدمة لسلاسل المخطط أو الفئات. |
| [getSeries()](#getSeries--) | يحصل على السلاسل. |
| [getSeriesGroups()](#getSeriesGroups--) | يحصل على مجموعات السلاسل. |
| [getCategories()](#getCategories--) | يحصل على الفئات الأولية (أو كل من الفئات الأولية والثانوية إذا كانت خاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) غير صحيحة). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | إذا كانت القيمة false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) تُعيد null والبيانات في خاصية (\#getCategories.getCategories) تُستخدم لكل من السلاسل الأولية والثانوية. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | إذا كانت القيمة false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) تُعيد null والبيانات في خاصية (\#getCategories.getCategories) تُستخدم لكل من السلاسل الأولية والثانوية. |
| [getSecondaryCategories()](#getSecondaryCategories--) | يحصل على الفئات الثانوية إذا كانت الخاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true. |
| [readWorkbookStream()](#readWorkbookStream--) | يكتب ملف Excel المضمن داخليًا إلى تدفق في الذاكرة. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | يُهيئ ملف Excel المضمن داخليًا بالقيمة التي يحددها المستخدم. |
| [setRange(String formula)](#setRange-java.lang.String-) | يضبط نطاق بيانات المخطط. |
| [getRange()](#getRange--) | يحصل على نطاق بيانات المخطط. |
| [getDataSourceType()](#getDataSourceType--) | يمثل مصدر بيانات المخطط |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | يمثل مسار ملف العمل الخارجي إذا كان مصدر البيانات خارجيًا، وإلا يكون null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | يحصل على نوع ملف العمل المدمج. |
| [switchRowColumn()](#switchRowColumn--) | تبديل البيانات على المحور. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | يضبط ملف العمل الخارجي كمصدر بيانات للمخطط. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | يضبط ملف العمل الخارجي كمصدر بيانات للمخطط. |
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

يحصل على السلاسل. قراءة فقط [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**الإرجاع:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

يحصل على مجموعات السلاسل. قراءة فقط [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) كل مجموعة من السلاسل تحتوي على سلاسل بأنواع يمكن دمجها. يتم تعريف مجموعات أنواع السلاسل القابلة للدمج ووصفها باستخدام تعداد CombinableSeriesTypesGroup. أيضا كل مجموعة من السلاسل تحتوي على سلاسل يتم رسمها إما على المحاور الأولية أو على المحاور الثانوية (ليس كلا الحالتين في مجموعة واحدة). وبالتالي، مبدأ تجميع السلاسل هو التجميع حسب مجموعات الأنواع المذكورة أعلاه وحسب نوع الرسم الأولي/الثانوي. 2) مجموعة السلسلة تحتوي على بعض خصائص السلسلة التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلسلة"). "خصائص مجموعة السلسلة" في الفئة ChartSeriesGroup هي قراءة/كتابة. كل من "خصائص مجموعة السلسلة" يمكن أن يكون له تمثيل قراءة فقط في الفئة ChartSeries.

**الإرجاع:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

يحصل على الفئات الأولية (أو كل من الفئات الأولية والثانوية إذا كانت خاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) غير صحيحة). قراءة فقط [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

إذا كانت القيمة false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) تُعيد null والبيانات في خاصية (\#getCategories.getCategories) تُستخدم لكل من السلاسل الأولية والثانوية. إذا كانت القيمة true فإن البيانات في خاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية والبيانات في خاصية (\#getCategories.getCategories) تُستخدم للسلاسل الأولية.

**الإرجاع:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

إذا كانت القيمة false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) تُعيد null والبيانات في خاصية (\#getCategories.getCategories) تُستخدم لكل من السلاسل الأولية والثانوية. إذا كانت القيمة true فإن البيانات في خاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية والبيانات في خاصية (\#getCategories.getCategories) تُستخدم للسلاسل الأولية. قراءة/كتابة من نوع boolean.

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

إذا كانت القيمة false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) تُعيد null والبيانات في خاصية (\#getCategories.getCategories) تُستخدم لكل من السلاسل الأولية والثانوية. إذا كانت القيمة true فإن البيانات في خاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية والبيانات في خاصية (\#getCategories.getCategories) تُستخدم للسلاسل الأولية. قراءة/كتابة من نوع boolean.

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


**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

يحصل على الفئات الثانوية إذا كانت الخاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true. قراءة فقط [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

إذا كانت الخاصية (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false فإن خاصية (\#getSecondaryCategories.getSecondaryCategories) تُعيد null والبيانات في خاصية (\#getCategories.getCategories) تُستخدم لكل من السلاسل الأولية والثانوية. إذا كانت الخاصية true فإن البيانات في خاصية (\#getSecondaryCategories.getSecondaryCategories) تُستخدم للسلاسل الثانوية والبيانات في خاصية (\#getCategories.getCategories) تُستخدم للسلاسل الأولية.

**الإرجاع:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

يكتب ملف Excel المضمن داخليًا إلى تدفق في الذاكرة.

**الإرجاع:**
byte[] - إرجاع مصفوفة من البايتات تحتوي على نسخة من ملف Excel المدمج داخليًا.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

يُهيئ ملف Excel المضمن داخليًا بالقيمة التي يحددها المستخدم.

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| ms | byte[] | تدفق المستخدم الذي يحتوي على ملف Excel بالكامل. |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

يضبط نطاق بيانات المخطط. سيتم تحديث السلاسل والفئات بناءً على نطاق البيانات الجديد. إذا كان عدد السلاسل في نطاق البيانات أكبر من عدد السلاسل في بيانات المخطط، فسيتم إضافة سلاسل إضافية من نفس نوع السلسلة الأخيرة في المجموعة الحالية إلى نهاية المجموعة.

**المُعاملات:**
| المُعامل | النوع | الوصف |
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

يمثل مصدر بيانات المخطط

**الإرجاع:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

يمثل مسار ملف العمل الخارجي إذا كان مصدر البيانات خارجيًا، وإلا يكون null

**الإرجاع:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

يحصل على نوع ملف العمل المدمج. يُرجع [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) إذا كان DataSourceType (\#getDataSourceType.getDataSourceType) هو [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). قراءة فقط [WorkbookType](../../com.aspose.slides/workbooktype).

**الإرجاع:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

تبديل البيانات على المحور. البيانات التي تُرسم على المحور X ستنتقل إلى المحور Y والعكس بالعكس.
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

يضبط ملف العمل الخارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من ملف العمل الهدف.

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


**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| workbookPath | java.lang.String | المسار إلى ملف العمل الهدف |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

يضبط ملف العمل الخارجي كمصدر بيانات للمخطط.

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


**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| workbookPath | java.lang.String | المسار إلى ملف العمل الهدف |
| updateChartData | boolean | إذا كانت القيمة false سيتم تحديث مسار ملف العمل فقط. لن يتم تحميل بيانات المخطط وتحديثها من ملف العمل الهدف. يمكن استخدام ذلك عندما لا يكون ملف العمل الهدف موجودًا أو غير متاح. إذا كانت القيمة true سيتم تحديث بيانات المخطط من ملف العمل الهدف. |