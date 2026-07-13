---
title: ExcelWorkbookImporter
second_title: Aspose.Slides dla Androida za pośrednictwem Java API Reference
description: Udostępnia funkcjonalność importowania treści z skoroszytu Excel do prezentacji.
type: docs
url: /pl/com.aspose.slides/excelworkbookimporter/
---
**Dziedziczenie:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Zapewnia funkcjonalność importowania treści z skoroszytu Excel do prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Pobiera wykres z określonego skoroszytu Excel i dodaje go na końcu podanej kolekcji kształtów w określonych współrzędnych. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Pobiera wykres z określonego skoroszytu Excel i dodaje go na końcu podanej kolekcji kształtów w określonych współrzędnych. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Pobiera wykres z określonego skoroszytu Excel i dodaje go na końcu podanej kolekcji kształtów w określonych współrzędnych. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Pobiera wykres z określonego skoroszytu Excel i dodaje go na końcu podanej kolekcji kształtów w określonych współrzędnych. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Pobiera tabelę z określonego skoroszytu Excel i dodaje ją na końcu podanej kolekcji kształtów w określonych współrzędnych. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Pobiera tabelę z określonego pliku skoroszytu Excel i dodaje ją na końcu podanej kolekcji kształtów w określonych współrzędnych. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Pobiera tabelę z określonego pliku skoroszytu Excel i dodaje ją na końcu podanej kolekcji kształtów w określonych współrzędnych. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```


Pobiera wykres z określonego skoroszytu Excel i dodaje go na końcu podanej kolekcji kształtów w określonych współrzędnych.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, wb, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Kolekcja kształtów, do której zostanie dodany wykres. |
| x | float | Współrzędna X określająca pozycję wykresu. |
| y | float | Współrzędna Y określająca pozycję wykresu. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Skoroszyt Excel. |
| worksheetName | java.lang.String | Nazwa arkusza zawierającego wykres. |
| chartIndex | int | Zero-indeksowany indeks kształtu wykresu do wstawienia. Ten indeks można uzyskać przy pomocy metody [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-). |
| embedAllWorkbook | boolean | Jeśli true, cały skoroszyt zostanie osadzony w wykresie; jeśli false, zostaną osadzone tylko dane wykresu. |

**Zwraca:**
[IChart](../../com.aspose.slides/ichart) – Wykres, który został dodany do kolekcji kształtów.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```


Pobiera wykres z określonego skoroszytu Excel i dodaje go na końcu podanej kolekcji kształtów w określonych współrzędnych.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      String worksheetName = "worksheet name";
>      Dictionary.Enumerator<Integer, String> worksheetCharts = wb.getChartsFromWorksheet(worksheetName).iterator();
>      while (worksheetCharts.hasNext())
>      {
>          KeyValuePair<Integer, String> chart = worksheetCharts.next();
>          ISlide slide = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>          ExcelWorkbookImporter.addChartFromWorkbook(slide.getShapes(), 10, 10, wb, worksheetName, chart.getKey(), false);
>      }
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Kolekcja kształtów, do której zostanie dodany wykres. |
| x | float | Współrzędna X określająca pozycję wykresu. |
| y | float | Współrzędna Y określająca pozycję wykresu. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Skoroszyt Excel. |
| worksheetName | java.lang.String | Nazwa arkusza zawierającego wykres. |
| chartName | java.lang.String | Nazwa wykresu do dodania. |
| embedAllWorkbook | boolean | Jeśli true, cały skoroszyt zostanie osadzony w wykresie; jeśli false, zostaną osadzone tylko dane wykresu. |

**Zwraca:**
[IChart](../../com.aspose.slides/ichart) – Wykres, który został dodany do kolekcji kształtów.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```


Pobiera wykres z określonego skoroszytu Excel i dodaje go na końcu podanej kolekcji kształtów w określonych współrzędnych.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fStream = new FileInputStream(workbookPath);
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getLayoutSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, chartName, true);
>      fStream.close();
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Kolekcja kształtów, do której zostanie dodany wykres. |
| x | float | Współrzędna X określająca pozycję wykresu. |
| y | float | Współrzędna Y określająca pozycję wykresu. |
| workbookStream | java.io.InputStream | Strumień zawierający dane skoroszytu. |
| worksheetName | java.lang.String | Nazwa arkusza zawierającego wykres. |
| chartName | java.lang.String | Nazwa wykresu do dodania. |
| embedAllWorkbook | boolean | Jeśli true, cały skoroszyt zostanie osadzony w wykresie; jeśli false, zostaną osadzone tylko dane wykresu. |

**Zwraca:**
[IChart](../../com.aspose.slides/ichart) – Wykres, który został dodany do kolekcji kształtów.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```


Pobiera wykres z określonego skoroszytu Excel i dodaje go na końcu podanej kolekcji kształtów w określonych współrzędnych.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Kolekcja kształtów, do której zostanie dodany wykres. |
| x | float | Współrzędna X określająca pozycję wykresu. |
| y | float | Współrzędna Y określająca pozycję wykresu. |
| workbookPath | java.lang.String | Ścieżka do pliku skoroszytu zawierającego wykres. |
| worksheetName | java.lang.String | Nazwa arkusza zawierającego wykres. |
| chartName | java.lang.String | Nazwa wykresu do dodania. |
| embedWorkbook | boolean | Jeśli true, skoroszyt zostanie osadzony w wykresie; jeśli false, wykres będzie odwoływał się do zewnętrznego skoroszytu. |

**Zwraca:**
[IChart](../../com.aspose.slides/ichart) – Wykres, który został dodany do kolekcji kształtów.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```


Pobiera tabelę z określonego skoroszytu Excel i dodaje ją na końcu podanej kolekcji kształtów w określonych współrzędnych.

--------------------

> ```
> IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbook, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Kolekcja kształtów, do której zostanie dodana tabela. |
| x | float | Współrzędna X określająca pozycję tabeli. |
| y | float | Współrzędna Y określająca pozycję tabeli. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Skoroszyt Excel. |
| worksheetName | java.lang.String | Nazwa arkusza zawierającego tabelę. |
| cellRange | java.lang.String | Zakres komórek definiujący tabelę (np. „A1:D10”). |

**Zwraca:**
[ITable](../../com.aspose.slides/itable) – Tabela, która została dodana do kolekcji kształtów.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```


Pobiera tabelę z określonego pliku skoroszytu Excel i dodaje ją na końcu podanej kolekcji kształtów w określonych współrzędnych.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Kolekcja kształtów, do której zostanie dodana tabela. |
| x | float | Współrzędna X określająca pozycję tabeli. |
| y | float | Współrzędna Y określająca pozycję tabeli. |
| workbookPath | java.lang.String | Ścieżka do pliku skoroszytu Excel. |
| worksheetName | java.lang.String | Nazwa arkusza zawierającego tabelę. |
| cellRange | java.lang.String | Zakres komórek definiujący tabelę (np. „A1:D10”). |

**Zwraca:**
[ITable](../../com.aspose.slides/itable) – Tabela, która została dodana do kolekcji kształtów.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```


Pobiera tabelę z określonego pliku skoroszytu Excel i dodaje ją na końcu podanej kolekcji kształtów w określonych współrzędnych.

--------------------

> ```
> FileInputStream fStream = new FileInputStream(workbookPath);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Kolekcja kształtów, do której zostanie dodana tabela. |
| x | float | Współrzędna X określająca pozycję tabeli. |
| y | float | Współrzędna Y określająca pozycję tabeli. |
| workbookStream | java.io.InputStream | Strumień zawierający dane skoroszytu. |
| worksheetName | java.lang.String | Nazwa arkusza zawierającego tabelę. |
| cellRange | java.lang.String | Zakres komórek definiujący tabelę (np. „A1:D10”). |

**Zwraca:**
[ITable](../../com.aspose.slides/itable) – Tabela, która została dodana do kolekcji kształtów.