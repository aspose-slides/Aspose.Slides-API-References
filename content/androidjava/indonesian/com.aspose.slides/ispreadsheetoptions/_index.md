---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options which can be used to specify additional spreadsheets behavior.
type: docs
url: /id/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Mewakili opsi yang dapat digunakan untuk menentukan perilaku tambahan spreadsheet.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Mendapatkan atau mengatur informasi budaya yang diinginkan untuk menghitung beberapa fungsi yang ditujukan untuk digunakan dengan bahasa yang menggunakan set karakter dua byte (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Mendapatkan atau mengatur informasi budaya yang diinginkan untuk menghitung beberapa fungsi yang ditujukan untuk digunakan dengan bahasa yang menggunakan set karakter dua byte (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Jika sumber data untuk diagram adalah buku kerja eksternal dan tidak tersedia, maka akan dipulihkan dari cache diagram. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Jika sumber data untuk diagram adalah buku kerja eksternal dan tidak tersedia, maka akan dipulihkan dari cache diagram. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


Mendapatkan atau mengatur informasi budaya yang diinginkan untuk menghitung beberapa fungsi yang ditujukan untuk digunakan dengan bahasa yang menggunakan set karakter dua byte (DBCS).

**Mengembalikan:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


Mendapatkan atau mengatur informasi budaya yang diinginkan untuk menghitung beberapa fungsi yang ditujukan untuk digunakan dengan bahasa yang menggunakan set karakter dua byte (DBCS).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


Jika sumber data untuk diagram adalah buku kerja eksternal dan tidak tersedia, maka akan dipulihkan dari cache diagram.

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


Jika sumber data untuk diagram adalah buku kerja eksternal dan tidak tersedia, maka akan dipulihkan dari cache diagram.

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