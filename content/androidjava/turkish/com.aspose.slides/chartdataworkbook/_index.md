---
title: ChartDataWorkbook
second_title: Aspose.Slides for Android için Java API Referansı
description: Gömülü Excel çalışma kitabına erişim sağlar
type: docs
url: /tr/com.aspose.slides/chartdataworkbook/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Gömülü Excel çalışma kitabına erişim sağlar

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Çalışma sayfalarının bir koleksiyonunu alır. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Hücre kümesini alır. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır |
| [clear(int sheetIndex)](#clear-int-) | Sayfadaki tüm hücre değerlerini temizler |
| [calculateFormulas()](#calculateFormulas--) | Çalışma kitabındaki tüm formülleri hesaplar ve ilgili hücre değerlerini günceller. |

### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```

Çalışma sayfalarının bir koleksiyonunu alır.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

Hücre kümesini alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formula | java.lang.String | “Sheet1!$A$2:$A$5” gibi Excel formülü. |
| skipHiddenCells | boolean | true ise yöntem gizli hücreler olmadan koleksiyon döndürür. |

**Döndürür:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetName | java.lang.String | Çalışma sayfasının adı. |
| row | int | Satır. |
| column | int | Sütun. |

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell nesnesi

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | int | Çalışma sayfasının indeksi. |
| row | int | Satır. |
| column | int | Sütun. |

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell nesnesi

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | int | Çalışma sayfasının indeksi. |
| cellName | java.lang.String | Hücrenin adı. |

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell nesnesi

### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | int | Çalışma sayfasının indeksi. |
| cellName | java.lang.String | Hücrenin adı. |
| value | java.lang.Object | Değer. |

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell nesnesi

### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | int | Çalışma sayfasının indeksi. |
| row | int | Satır. |
| column | int | Sütun. |
| value | java.lang.Object | Değer. |

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell nesnesi

### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

Sayfadaki tüm hücre değerlerini temizler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sheetIndex | int | Sayfanın indeksi |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```

Çalışma kitabındaki tüm formülleri hesaplar ve ilgili hücre değerlerini günceller.

--------------------

> ```
> Example shows how to assign a formula to the cell and to calculate a value. The value of the "B4" cell is getting set to 5.
>   
>   Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 100, 100, 300, 400);
>       IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>       wb.getCell(0, "B2", 2);
>       wb.getCell(0, "B3", 3);
>       wb.getCell(0, "B4").setFormula("B2+B3");
>       wb.calculateFormulas();
>       ...
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```