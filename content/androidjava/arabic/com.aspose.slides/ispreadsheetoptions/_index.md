---
title: ISpreadsheetOptions
second_title: Aspose.Slides لنظام Android عبر مرجع API للـ Java
description: يمثل الخيارات التي يمكن استخدامها لتحديد سلوك إضافي لجداول البيانات.
type: docs
url: /ar/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

يمثل الخيارات التي يمكن استخدامها لتحديد سلوك إضافي لجداول البيانات.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | يحصل أو يحدد معلومات الثقافة المفضلة لحساب بعض الدوال المصممة للاستخدام مع اللغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | يحصل أو يحدد معلومات الثقافة المفضلة لحساب بعض الدوال المصممة للاستخدام مع اللغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | إذا كان مصدر البيانات للمخطط هو مصنف خارجي ولم يكن متاحًا، فسيتم استعادته من ذاكرة التخزين المؤقت للمخطط. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | إذا كان مصدر البيانات للمخطط هو مصنف خارجي ولم يكن متاحًا، فسيتم استعادته من ذاكرة التخزين المؤقت للمخطط. |

### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```

يحصل أو يحدد معلومات الثقافة المفضلة لحساب بعض الدوال المصممة للاستخدام مع اللغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS).

**الإرجاع:**  
java.util.Locale

### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```

يحصل أو يحدد معلومات الثقافة المفضلة لحساب بعض الدوال المصممة للاستخدام مع اللغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```

إذا كان مصدر البيانات للمخطط هو مصنف خارجي ولم يكن متاحًا، فسيتم استعادته من ذاكرة التخزين المؤقت للمخطط.

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
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```

إذا كان مصدر البيانات للمخطط هو مصنف خارجي ولم يكن متاحًا، فسيتم استعادته من ذاكرة التخزين المؤقت للمخطط.

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