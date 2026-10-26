---
title: ExcelDataWorkbook
second_title: Aspose.Slides for Android Java API Referansı
description: Genel kullanım için Excel verilerine erişim sağlayan bir çalışma kitabını temsil eder.
type: docs
url: /tr/com.aspose.slides/exceldataworkbook/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Genel kullanım için Excel verilerine erişim sağlayan bir çalışma kitabını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Belirtilen dosya yolunu kullanarak yeni bir örnek oluşturur. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Sağlanan akışı kullanarak sınıfın yeni bir örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Belirtilen formülle eşleşen hücrelerin bir koleksiyonunu çalışma kitabından alır. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Belirtilen çalışma sayfasından indeks ve hücre koordinatlarını kullanarak bir hücre alır. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Belirtilen çalışma sayfasından adı ve hücre koordinatlarını kullanarak bir hücre alır. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Belirtilen çalışma sayfasından indeks ve Excel tarzı hücre adı (örn., "B2") kullanarak bir hücre alır. |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Belirtilen çalışma sayfasından Excel tarzı hücre adı (örn., "B2") kullanarak bir hücre alır. |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Belirtilen Excel çalışma kitabındaki bir çalışma sayfasındaki tüm grafiklerin indeks ve adlarını içeren bir sözlük alır. |
| [getWorksheetNames()](#getWorksheetNames--) | Excel çalışma kitabında bulunan tüm çalışma sayfalarının adlarını alır. |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

Belirtilen dosya yolunu kullanarak yeni bir örnek oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Excel çalışma kitabı dosyasının tam yolu. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

Sağlanan akışı kullanarak sınıfın yeni bir örneğini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Excel çalışma kitabı verilerini içeren bir akış. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
``` 
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Belirtilen formülle eşleşen hücrelerin bir koleksiyonunu çalışma kitabından alır.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Çıktı: 5
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formula | java.lang.String | Hedef hücreleri belirlemek için kullanılan bir formül veya aralık ifadesi (örn., "Sheet1!A1:B3"). |
| skipHiddenCells | boolean | Doğru ise, gizli hücreler (örneğin, gizli satır veya sütunlardaki) sonuçtan dışlanır. |

**Döndürür:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Belirtilen formülle eşleşen hücrelerin yalnızca okunabilir listesi.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Belirtilen çalışma sayfasından indeks ve hücre koordinatlarını kullanarak bir hücre alır.

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
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

Belirtilen çalışma sayfasından adı ve hücre koordinatlarını kullanarak bir hücre alır.

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
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Belirtilen çalışma sayfasından indeks ve Excel tarzı hücre adı (örn., "B2") kullanarak bir hücre alır.

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
| cellName | java.lang.String | Excel tarzı hücre referansı (örn., "A1", "C5"). |

**Döndürür:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Belirtilen konumdaki hücre.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

Belirtilen çalışma sayfasından Excel tarzı hücre adı (örn., "B2") kullanarak bir hücre alır.

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
| cellName | java.lang.String | Excel tarzı hücre referansı (örn., "A1", "C5"). |

**Döndürür:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Belirtilen konumdaki hücre.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Belirtilen Excel çalışma kitabındaki bir çalışma sayfasındaki tüm grafiklerin indeks ve adlarını içeren bir sözlük alır.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Anahtarının grafik indeksi, değerinin grafik adı olduğu bir sözlük.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
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
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Çalışma sayfası adlarının listesi