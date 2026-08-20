---
title: SpreadsheetOptions
second_title: Aspose.Slides لواجهة برمجة تطبيقات Java
description: يمثل الخيارات التي يمكن استخدامها لتحديد سلوك إضافي لملفات جداول البيانات.
type: docs
url: /ar/com.aspose.slides/spreadsheetoptions/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

يمثل الخيارات التي يمكن استخدامها لتحديد سلوك إضافي لجداول البيانات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | تهيئ مثيلًا جديدًا من الفئة [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | يحصل أو يعيّن معلومات الثقافة المفضلة لحساب بعض الدوال المخصصة للغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | يحصل أو يعيّن معلومات الثقافة المفضلة لحساب بعض الدوال المخصصة للغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | إذا كان مصدر البيانات للمخطط عبارة عن دفتر عمل خارجي ولم يكن متاحًا، فسيتم استعادته من ذاكرة التخزين المؤقت للمخطط. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | إذا كان مصدر البيانات للمخطط عبارة عن دفتر عمل خارجي ولم يكون متاحًا، فسيتم استعادته من ذاكرة التخزين المؤقت للمخطط. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

تهيئ مثيلًا جديدًا من الفئة [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions).

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

يحصل أو يعيّن معلومات الثقافة المفضلة لحساب بعض الدوال المخصصة للغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS).

**الإرجاع:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

يحصل أو يعيّن معلومات الثقافة المفضلة لحساب بعض الدوال المخصصة للغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

إذا كان مصدر البيانات للمخطط عبارة عن دفتر عمل خارجي ولم يكن متاحًا، فسيتم استعادته من ذاكرة التخزين المؤقت للمخطط.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**الإرجاع:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public final void setRecoverWorkbookFromChartCache(boolean value)
```

إذا كان مصدر البيانات للمخطط عبارة عن دفتر عمل خارجي ولم يكن متاحًا، فسيتم استعادته من ذاكرة التخزين المؤقت للمخطط.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |