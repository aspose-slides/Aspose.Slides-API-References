---
title: SpreadsheetOptions
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Ek tablo davranışlarını belirlemek için kullanılabilecek seçenekleri temsil eder.
type: docs
url: /tr/com.aspose.slides/spreadsheetoptions/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Ek tablo davranışlarını belirtmek için kullanılabilecek seçenekleri temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Çift bayt karakter seti (DBCS) kullanan diller için tasarlanmış bazı işlevlerin hesaplanması için tercih edilen kültür bilgisini alır veya ayarlar. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Çift bayt karakter seti (DBCS) kullanan diller için tasarlanmış bazı işlevlerin hesaplanması için tercih edilen kültür bilgisini alır veya ayarlar. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Grafik için veri kaynağı harici bir çalışma kitabı ise ve mevcut değilse, grafik önbelleğinden kurtarılacaktır. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Grafik için veri kaynağı harici bir çalışma kitabı ise ve mevcut değilse, grafik önbelleğinden kurtarılacaktır. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```


[SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) sınıfının yeni bir örneğini başlatır.

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```


Çift bayt karakter seti (DBCS) kullanan diller için tasarlanmış bazı işlevlerin hesaplanması için tercih edilen kültür bilgisini alır veya ayarlar.

**Dönüş Değeri:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```


Çift bayt karakter seti (DBCS) kullanan diller için tasarlanmış bazı işlevlerin hesaplanması için tercih edilen kültür bilgisini alır veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```


Grafik için veri kaynağı harici bir çalışma kitabı ise ve mevcut değilse, grafik önbelleğinden kurtarılacaktır.

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

**Dönüş Değeri:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public final void setRecoverWorkbookFromChartCache(boolean value)
```


Grafik için veri kaynağı harici bir çalışma kitabı ise ve mevcut değilse, grafik önbelleğinden kurtarılacaktır.

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