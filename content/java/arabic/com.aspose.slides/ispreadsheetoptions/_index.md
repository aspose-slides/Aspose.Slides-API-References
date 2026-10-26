---
title: ISpreadsheetOptions
second_title: Aspose.Slides لـ Java مرجع API
description: يمثل الخيارات التي يمكن استخدامها لتحديد سلوك إضافي للجداول الإلكترونية.
type: docs
url: /ar/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

يمثل الخيارات التي يمكن استخدامها لتحديد سلوك إضافي للجداول الإلكترونية.
## الطرق

| Method | Description |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | يحصل أو يضبط معلومات الثقافة المفضلة لحساب بعض الدوال المخصصة للغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | يحصل أو يضبط معلومات الثقافة المفضلة لحساب بعض الدوال المخصصة للغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | إذا كان مصدر بيانات المخطط من مصنف خارجي وغير متوفر، سيتم استرداده من مخزن المؤقت للمخطط. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | إذا كان مصدر بيانات المخطط من مصنف خارجي وغير متوفر، سيتم استرداده من مخزن المؤقت للمخطط. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


يحصل أو يضبط معلومات الثقافة المفضلة لحساب بعض الدوال المخصصة للغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS).

**القيمة المرجعة:**  
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


يحصل أو يضبط معلومات الثقافة المفضلة لحساب بعض الدوال المخصصة للغات التي تستخدم مجموعة الأحرف ذات البايتين (DBCS).

**الوسائط:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |
### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


إذا كان مصدر بيانات المخطط من مصنف خارجي وغير متوفر، سيتم استرداده من مخزن المؤقت للمخطط.

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


**القيمة المرجعة:**  
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


إذا كان مصدر بيانات المخطط من مصنف خارجي وغير متوفر، سيتم استرداده من مخزن المؤقت للمخطط.

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


**الوسائط:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |