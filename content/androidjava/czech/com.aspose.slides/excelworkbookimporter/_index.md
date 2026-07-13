---
title: ExcelWorkbookImporter
second_title: Aspose.Slides pro Android přes Java API Reference
description: Poskytuje funkčnost pro import obsahu z Excel sešitu do prezentace.
type: docs
url: /cs/com.aspose.slides/excelworkbookimporter/
---
**Dědičnost:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Poskytuje funkčnost pro import obsahu z Excel sešitu do prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Načte graf ze zadaného Excel sešitu a přidá jej na konec dané kolekce tvarů na určených souřadnicích. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Načte graf ze zadaného Excel sešitu a přidá jej na konec dané kolekce tvarů na určených souřadnicích. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Načte graf ze zadaného Excel sešitu a přidá jej na konec dané kolekce tvarů na určených souřadnicích. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Načte graf ze zadaného Excel sešitu a přidá jej na konec dané kolekce tvarů na určených souřadnicích. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Načte tabulku ze zadaného Excel sešitu a přidá ji na konec dané kolekce tvarů na určených souřadnicích. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Načte tabulku ze zadaného souboru Excel sešitu a přidá ji na konec dané kolekce tvarů na určených souřadnicích. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Načte tabulku ze zadaného souboru Excel sešitu a přidá ji na konec dané kolekce tvarů na určených souřadnicích. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```


Načte graf ze zadaného Excel sešitu a přidá jej na konec dané kolekce tvarů na určených souřadnicích.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Kolekce tvarů, do které bude graf přidán. |
| x | float | Souřadnice X pro umístění grafu. |
| y | float | Souřadnice Y pro umístění grafu. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel sešit. |
| worksheetName | java.lang.String | Název listu, který obsahuje graf. |
| chartIndex | int | Nulový index grafického tvaru k vložení. Tento index lze získat pomocí metody [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-). |
| embedAllWorkbook | boolean | Pokud je true, celý sešit bude vložen do grafu; pokud je false, budou vložena pouze data grafu. |

**Návratová hodnota:**
[IChart](../../com.aspose.slides/ichart) - Graf, který byl přidán do kolekce tvarů.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```


Načte graf ze zadaného Excel sešitu a přidá jej na konec dané kolekce tvarů na určených souřadnicích.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Kolekce tvarů, do které bude graf přidán. |
| x | float | Souřadnice X pro umístění grafu. |
| y | float | Souřadnice Y pro umístění grafu. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel sešit. |
| worksheetName | java.lang.String | Název listu, který obsahuje graf. |
| chartName | java.lang.String | Název grafu, který má být přidán. |
| embedAllWorkbook | boolean | Pokud je true, celý sešit bude vložen do grafu; pokud je false, budou vložena pouze data grafu. |

**Návratová hodnota:**
[IChart](../../com.aspose.slides/ichart) - Graf, který byl přidán do kolekce tvarů.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```


Načte graf ze zadaného Excel sešitu a přidá jej na konec dané kolekce tvarů na určených souřadnicích.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Kolekce tvarů, do které bude graf přidán. |
| x | float | Souřadnice X pro umístění grafu. |
| y | float | Souřadnice Y pro umístění grafu. |
| workbookStream | java.io.InputStream | Datový stream obsahující data sešitu. |
| worksheetName | java.lang.String | Název listu, který obsahuje graf. |
| chartName | java.lang.String | Název grafu, který má být přidán. |
| embedAllWorkbook | boolean | Pokud je true, celý sešit bude vložen do grafu; pokud je false, budou vložena pouze data grafu. |

**Návratová hodnota:**
[IChart](../../com.aspose.slides/ichart) - Graf, který byl přidán do kolekce tvarů.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```


Načte graf ze zadaného souboru Excel sešitu a přidá jej na konec dané kolekce tvarů na určených souřadnicích.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Kolekce tvarů, do které bude graf přidán. |
| x | float | Souřadnice X pro umístění grafu. |
| y | float | Souřadnice Y pro umístění grafu. |
| workbookPath | java.lang.String | Cesta k souboru sešitu, který obsahuje graf. |
| worksheetName | java.lang.String | Název listu, který obsahuje graf. |
| chartName | java.lang.String | Název grafu, který má být přidán. |
| embedWorkbook | boolean | Pokud je true, sešit bude vložen do grafu; pokud je false, graf bude odkazovat na externí sešit. |

**Návratová hodnota:**
[IChart](../../com.aspose.slides/ichart) - Graf, který byl přidán do kolekce tvarů.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```


Načte tabulku ze zadaného Excel sešitu a přidá ji na konec dané kolekce tvarů na určených souřadnicích.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Kolekce tvarů, do které bude tabulka přidána. |
| x | float | Souřadnice X pro umístění tabulky. |
| y | float | Souřadnice Y pro umístění tabulky. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel sešit. |
| worksheetName | java.lang.String | Název listu, který obsahuje tabulku. |
| cellRange | java.lang.String | Rozsah buněk, který definuje tabulku (například "A1:D10"). |

**Návratová hodnota:**
[ITable](../../com.aspose.slides/itable) - Tabulka, která byla přidána do kolekce tvarů.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```


Načte tabulku ze zadaného souboru Excel sešitu a přidá ji na konec dané kolekce tvarů na určených souřadnicích.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Kolekce tvarů, do které bude tabulka přidána. |
| x | float | Souřadnice X pro umístění tabulky. |
| y | float | Souřadnice Y pro umístění tabulky. |
| workbookPath | java.lang.String | Cesta k souboru Excel sešitu. |
| worksheetName | java.lang.String | Název listu, který obsahuje tabulku. |
| cellRange | java.lang.String | Rozsah buněk, který definuje tabulku (například "A1:D10"). |

**Návratová hodnota:**
[ITable](../../com.aspose.slides/itable) - Tabulka, která byla přidána do kolekce tvarů.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```


Načte tabulku ze zadaného souboru Excel sešitu a přidá ji na konec dané kolekce tvarů na určených souřadnicích.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Kolekce tvarů, do které bude tabulka přidána. |
| x | float | Souřadnice X pro umístění tabulky. |
| y | float | Souřadnice Y pro umístění tabulky. |
| workbookStream | java.io.InputStream | Datový stream obsahující data sešitu. |
| worksheetName | java.lang.String | Název listu, který obsahuje tabulku. |
| cellRange | java.lang.String | Rozsah buněk, který definuje tabulku (například "A1:D10"). |

**Návratová hodnota:**
[ITable](../../com.aspose.slides/itable) - Tabulka, která byla přidána do kolekce tvarů.