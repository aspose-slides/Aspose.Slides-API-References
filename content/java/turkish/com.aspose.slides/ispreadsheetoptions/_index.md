---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Java API Reference
description: Ek tablo davranışlarını belirtmek için kullanılabilecek seçenekleri temsil eder.
type: docs
url: /tr/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Ek tablo davranışlarını belirtmek için kullanılabilecek seçenekleri temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Çift bayt karakter kümesi (DBCS) kullanan diller için tasarlanmış bazı işlevlerin hesaplanması amacıyla tercih edilen kültür bilgisini alır veya ayarlar. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Çift bayt karakter kümesi (DBCS) kullanan diller için tasarlanmış bazı işlevlerin hesaplanması amacıyla tercih edilen kültür bilgisini alır veya ayarlar. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Grafik için veri kaynağı dış bir çalışma kitabı ise ve mevcut değilse, grafik önbelleğinden geri alınacaktır. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Grafik için veri kaynağı dış bir çalışma kitabı ise ve mevcut değilse, grafik önbelleğinden geri alınacaktır. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


Çift bayt karakter kümesi (DBCS) kullanan diller için tasarlanmış bazı işlevlerin hesaplanması amacıyla tercih edilen kültür bilgisini alır veya ayarlar.

**Dönüş:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


Çift bayt karakter kümesi (DBCS) kullanan diller için tasarlanmış bazı işlevlerin hesaplanması amacıyla tercih edilen kültür bilgisini alır veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


Grafik için veri kaynağı dış bir çalışma kitabı ise ve mevcut değilse, grafik önbelleğinden geri alınacaktır.

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

**Dönüş:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


Grafik için veri kaynağı dış bir çalışma kitabı ise ve mevcut değilse, grafik önbelleğinden geri alınacaktır.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |