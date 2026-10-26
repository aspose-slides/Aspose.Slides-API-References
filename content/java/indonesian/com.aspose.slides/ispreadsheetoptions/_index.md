---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Java API Reference
description: Mewakili opsi yang dapat digunakan untuk menentukan perilaku spreadsheet tambahan.
type: docs
url: /id/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Mewakili opsi yang dapat digunakan untuk menentukan perilaku spreadsheet tambahan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Mendapatkan atau mengatur informasi budaya yang diutamakan untuk menghitung beberapa fungsi yang dimaksudkan untuk digunakan dengan bahasa yang menggunakan set karakter dua byte (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Mendapatkan atau mengatur informasi budaya yang diutamakan untuk menghitung beberapa fungsi yang dimaksudkan untuk digunakan dengan bahasa yang menggunakan set karakter dua byte (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Jika sumber data untuk bagan adalah workbook eksternal dan tidak tersedia, akan dipulihkan dari cache bagan. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Jika sumber data untuk bagan adalah workbook eksternal dan tidak tersedia, akan dipulihkan dari cache bagan. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```

Mendapatkan atau mengatur informasi budaya yang diutamakan untuk menghitung beberapa fungsi yang dimaksudkan untuk digunakan dengan bahasa yang menggunakan set karakter dua byte (DBCS).

**Mengembalikan:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```

Mendapatkan atau mengatur informasi budaya yang diutamakan untuk menghitung beberapa fungsi yang dimaksudkan untuk digunakan dengan bahasa yang menggunakan set karakter dua byte (DBCS).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```

Jika sumber data untuk bagan adalah workbook eksternal dan tidak tersedia, akan dipulihkan dari cache bagan.

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

**Mengembalikan:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```

Jika sumber data untuk bagan adalah workbook eksternal dan tidak tersedia, akan dipulihkan dari cache bagan.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |