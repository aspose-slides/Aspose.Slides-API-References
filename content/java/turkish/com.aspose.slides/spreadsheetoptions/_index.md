---
title: SpreadsheetOptions
second_title: Aspose.Slides for Java API Referansı
description: Ek tablo davranışlarını belirtmek için kullanılabilecek seçenekleri temsil eder.
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
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Yeni bir [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) sınıfı örneği oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Çift bayt karakter kümesi (DBCS) kullanan diller için tasarlanmış bazı fonksiyonları hesaplamak amacıyla tercih edilen kültür bilgisini alır veya ayarlar. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Çift bayt karakter kümesi (DBCS) kullanan diller için tasarlanmış bazı fonksiyonları hesaplamak amacıyla tercih edilen kültür bilgisini alır veya ayarlar. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Grafik için veri kaynağı dış bir çalışma kitabıysa ve mevcut değilse, grafik önbelleğinden geri alınacaktır. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Grafik için veri kaynağı dış bir çalışma kitabıysa ve mevcut değilse, grafik önbelleğinden geri alınacaktır. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

Yeni bir [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) sınıfı örneği oluşturur.

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

Çift bayt karakter kümesi (DBCS) kullanan diller için tasarlanmış bazı fonksiyonları hesaplamak amacıyla tercih edilen kültür bilgisini alır veya ayarlar.

**Döndürür:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

Çift bayt karakter kümesi (DBCS) kullanan diller için tasarlanmış bazı fonksiyonları hesaplamak amacıyla tercih edilen kültür bilgisini alır veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

Grafik için veri kaynağı dış bir çalışma kitabıysa ve mevcut değilse, grafik önbelleğinden geri alınacaktır.

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

**Döndürür:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public final void setRecoverWorkbookFromChartCache(boolean value)
```

Grafik için veri kaynağı dış bir çalışma kitabıysa ve mevcut değilse, grafik önbelleğinden geri alınacaktır.

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