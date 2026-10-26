---
title: IExcelDataWorkbook
second_title: Aspose.Slides Android için Java API Referansı
description: Genel kullanım için Excel verilerine erişim sağlayan bir çalışma kitabını temsil eder.
type: docs
url: /tr/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Genel kullanım için Excel verilerine erişim sağlayan bir çalışma kitabını temsil eder.
## Methods

| Method | Description |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Belirtilen formülle eşleşen çalışma kitabındaki hücre koleksiyonunu getirir. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Belirtilen çalışma sayfasından indeks ve hücre koordinatlarıyla bir hücre getirir. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Belirtilen çalışma sayfasından adı ve hücre koordinatlarıyla bir hücre getirir. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Belirtilen çalışma sayfasından indeks ve Excel biçiminde hücre adı (ör. "B2") ile bir hücre getirir. |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Belirtilen çalışma sayfasından Excel biçimindeki hücre adı (ör. "B2") ile bir hücre getirir. |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Bir Excel çalışma kitabının belirtilen çalışma sayfasındaki tüm grafiklerin indeks ve adlarını içeren bir sözlük getirir. |
| [getWorksheetNames()](#getWorksheetNames--) | Excel çalışma kitabında bulunan tüm çalışma sayfalarının adlarını getirir. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


Belirtilen formülle eşleşen çalışma kitabındaki hücre koleksiyonunu getirir.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Çıktı: 5
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | Hedef hücreleri tanımlamak için kullanılan formül veya aralık ifadesi (ör. "Sheet1!A1:B3"). |
| skipHiddenCells | boolean | true ise, gizli hücreler (gizli satır veya sütunlardaki) sonuçtan dışlanır. |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Belirtilen formülle eşleşen hücrelerin salt okunur listesi.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


Belirtilen çalışma sayfasından indeks ve hücre koordinatlarıyla bir hücre getirir.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Çalışma sayfasının sıfır tabanlı indeksi. |
| row | int | Hücrenin sıfır tabanlı satır indeksi. |
| column | int | Hücrenin sıfır tabanlı sütun indeksi. |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Belirtilen konumdaki hücre.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```


Belirtilen çalışma sayfasından adı ve hücre koordinatlarıyla bir hücre getirir.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | Çalışma sayfasının adı. |
| row | int | Hücrenin sıfır tabanlı satır indeksi. |
| column | int | Hücrenin sıfır tabanlı sütun indeksi. |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Belirtilen konumdaki hücre.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Belirtilen çalışma sayfasından indeks ve Excel biçimindeki hücre adı (ör. "B2") ile bir hücre getirir.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Çalışma sayfasının sıfır tabanlı indeksi. |
| cellName | java.lang.String | Excel biçimindeki hücre referansı (ör. "A1", "C5"). |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Belirtilen konumdaki hücre.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```


Belirtilen çalışma sayfasından Excel biçimindeki hücre adı (ör. "B2") ile bir hücre getirir.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | Çalışma sayfasının adı. |
| cellName | java.lang.String | Excel biçimindeki hücre referansı (ör. "A1", "C5"). |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Belirtilen konumdaki hücre.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Belirtilen Excel çalışma kitabının çalışma sayfasındaki tüm grafiklerin indeks ve adlarını içeren bir sözlük getirir.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | Grafiklerin aranacağı çalışma sayfasının adı. |

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Anahtarın grafik indeksi, değerin grafik adı olduğu bir sözlük.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```


Excel çalışma kitabında bulunan tüm çalışma sayfalarının adlarını getirir.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Çalışma sayfası adlarının listesi