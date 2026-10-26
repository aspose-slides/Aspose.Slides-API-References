---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: Genel kullanım için Excel verilerine erişim sağlayan bir çalışma kitabını temsil eder.
type: docs
url: /tr/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Genel kullanım için Excel verilerine erişim sağlayan bir çalışma kitabını temsil eder.
## Yöntemler

| Method | Açıklama |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Belirtilen formülle eşleşen hücrelerin bir koleksiyonunu çalışma kitabından alır. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Belirtilen çalışma sayfasından indeksini ve hücre koordinatlarını kullanarak bir hücre alır. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Belirtilen çalışma sayfasından adını ve hücre koordinatlarını kullanarak bir hücre alır. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Belirtilen çalışma sayfasından indeksini ve Excel-biçimindeki hücre adını (ör. "B2") kullanarak bir hücre alır. |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Belirtilen çalışma sayfasından Excel-biçimindeki hücre adını (ör. "B2") kullanarak bir hücre alır. |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Bir Excel çalışma kitabındaki belirtilen çalışma sayfasındaki tüm grafiklerin indekslerini ve adlarını içeren bir sözlük alır. |
| [getWorksheetNames()](#getWorksheetNames--) | Excel çalışma kitabında bulunan tüm çalışma sayfalarının adlarını alır. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Belirtilen formülle eşleşen hücrelerin bir koleksiyonunu çalışma kitabından alır.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Çıktı: 5
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formula | java.lang.String | Hedef hücreleri tanımlamak için kullanılan bir formül veya aralık ifadesi (ör. "Sheet1!A1:B3"). |
| skipHiddenCells | boolean | Doğru ise, gizli hücreler (ör. gizli satırlarda veya sütunlarda) sonuçtan çıkarılacaktır. |

**Döndürür:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Belirtilen formülle eşleşen hücrelerden oluşan bir salt-okunur liste.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Belirtilen çalışma sayfasından indeksini ve hücre koordinatlarını kullanarak bir hücre alır.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | int | Çalışma sayfasının sıfır tabanlı indeksi. |
| row | int | Hücrenin sıfır tabanlı satır indeksi. |
| column | int | Hücrenin sıfır tabanlı sütun indeksi. |

**Döndürür:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Belirtilen konumdaki hücre.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

Belirtilen çalışma sayfasından adını ve hücre koordinatlarını kullanarak bir hücre alır.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetName | java.lang.String | Çalışma sayfasının adı. |
| row | int | Hücrenin sıfır tabanlı satır indeksi. |
| column | int | Hücrenin sıfır tabanlı sütun indeksi. |

**Döndürür:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Belirtilen konumdaki hücre.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Belirtilen çalışma sayfasından indeksini ve Excel-biçimindeki hücre adını (ör. "B2") kullanarak bir hücre alır.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | int | Çalışma sayfasının sıfır tabanlı indeksi. |
| cellName | java.lang.String | Excel-biçimindeki hücre referansı (ör. "A1", "C5"). |

**Döndürür:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Belirtilen konumdaki hücre.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

Belirtilen çalışma sayfasından Excel-biçimindeki hücre adını (ör. "B2") kullanarak bir hücre alır.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetName | java.lang.String | Çalışma sayfasının adı. |
| cellName | java.lang.String | Excel-biçimindeki hücre referansı (ör. "A1", "C5"). |

**Döndürür:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Belirtilen konumdaki hücre.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Bir Excel çalışma kitabındaki belirtilen çalışma sayfasındaki tüm grafiklerin indekslerini ve adlarını içeren bir sözlük alır.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Dictionary.Enumerator<Integer, String> sheetCharts = wb.getChartsFromWorksheet("worksheetName").iterator();
>  while (sheetCharts.hasNext())
>  {
>      KeyValuePair<Integer, String> chart = sheetCharts.next();
>      System.out.println(chart.getKey() + " : " + chart.getValue());
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetName | java.lang.String | Grafiklerin aranacağı çalışma sayfasının adı. |

**Döndürür:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Anahtar grafik indeksi ve değer grafik adı olan bir sözlük.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

Excel çalışma kitabında bulunan tüm çalışma sayfalarının adlarını alır.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Döndürür:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Çalışma sayfası adlarının bir listesi.