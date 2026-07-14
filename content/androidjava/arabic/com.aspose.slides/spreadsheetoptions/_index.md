---
title: SpreadsheetOptions
second_title: مرجع API لجافا عبر Aspose.Slides لنظام Android
description: يمثل الخيارات التي يمكن استخدامها لتحديد سلوك إضافي للجداول الإلكترونية.
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

يمثل الخيارات التي يمكن استخدامها لتحديد سلوك إضافي للجداول الإلكترونية.

## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | ينشئ مثلاً جديداً من الفئة [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions). |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | يحصل أو يعيّن معلومات الثقافة المفضلة لحساب بعض الدوال الموجهة للاستخدام مع اللغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | يحصل أو يعيّن معلومات الثقافة المفضلة لحساب بعض الدوال الموجهة للاستخدام مع اللغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | إذا كان مصدر البيانات للبيان هو دفتر عمل خارجي وليس متوفرًا، فسيتم استعادته من ذاكرة التخزين المؤقت للبيان. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | إذا كان مصدر البيانات للبيان هو دفتر عمل خارجي وليس متوفرًا، فسيتم استعادته من ذاكرة التخزين المؤقت للبيان. |

### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

ينشئ مثلاً جديداً من الفئة [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions).

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

يحصل أو يعيّن معلومات الثقافة المفضلة لحساب بعض الدوال الموجهة للاستخدام مع اللغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS).

**الإرجاع:**  
java.util.Locale

### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

يحصل أو يعيّن معلومات الثقافة المفضلة لحساب بعض الدوال الموجهة للاستخدام مع اللغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

إذا كان مصدر البيانات للبيان هو دفتر عمل خارجي وليس متوفرًا، فسيتم استعادته من ذاكرة التخزين المؤقت للبيان.

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

إذا كان مصدر البيانات للبيان هو دفتر عمل خارجي وليس متوفرًا، فسيتم استعادته من ذاكرة التخزين المؤقت للبيان.

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |