---
title: ExcelWorkbookImporter
second_title: Aspose.Slides for Java API referencia
description: Funkciókat biztosít egy Excel munkafüzet tartalmának egy prezentációba történő importálásához.
type: docs
url: /hu/com.aspose.slides/excelworkbookimporter/
---
**Öröklés:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Funkciókat biztosít egy Excel-munkafüzet tartalmának importálásához egy prezentációba.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Lekéri a diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Lekéri a diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Lekéri a diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Lekéri a diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Lekéri a táblázatot a megadott Excel-munkafüzetből, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Lekéri a táblázatot a megadott Excel-munkafüzet-fájlból, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Lekéri a táblázatot a megadott Excel-munkafüzet-fájlból, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

Lekéri a diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Az alakzatgyűjtemény, amelyhez a diagram hozzáadódik. |
| x | float | Az X koordináta a diagram elhelyezéséhez. |
| y | float | Az Y koordináta a diagram elhelyezéséhez. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Az Excel-munkafüzet. |
| worksheetName | java.lang.String | A munkalap neve, amely a diagramot tartalmazza. |
| chartIndex | int | A nullaalapú index a beszúrandó diagram alakzathoz. Ez az index a [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) metódussal szerezhető meg. |
| embedAllWorkbook | boolean | Ha igaz, a teljes munkafüzet be lesz ágyazva a diagramba; ha hamis, csak a diagram adatai lesznek beágyazva. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) - A diagram, amely hozzá lett adva az alakzatgyűjteményhez.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Lekéri a diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Az alakzatgyűjtemény, amelyhez a diagram hozzáadódik. |
| x | float | Az X koordináta a diagram elhelyezéséhez. |
| y | float | Az Y koordináta a diagram elhelyezéséhez. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Az Excel-munkafüzet. |
| worksheetName | java.lang.String | A munkalap neve, amely a diagramot tartalmazza. |
| chartName | java.lang.String | A hozzáadandó diagram neve. |
| embedAllWorkbook | boolean | Ha igaz, a teljes munkafüzet be lesz ágyazva a diagramba; ha hamis, csak a diagram adatai lesznek beágyazva. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) - A diagram, amely hozzá lett adva az alakzatgyűjteményhez.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Lekéri a diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Az alakzatgyűjtemény, amelyhez a diagram hozzáadódik. |
| x | float | Az X koordináta a diagram elhelyezéséhez. |
| y | float | Az Y koordináta a diagram elhelyezéséhez. |
| workbookStream | java.io.InputStream | Az adatfolyam, amely a munkafüzet adatait tartalmazza. |
| worksheetName | java.lang.String | A munkalap neve, amely a diagramot tartalmazza. |
| chartName | java.lang.String | A hozzáadandó diagram neve. |
| embedAllWorkbook | boolean | Ha igaz, a teljes munkafüzet be lesz ágyazva a diagramba; ha hamis, csak a diagram adatai lesznek beágyazva. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) - A diagram, amely hozzá lett adva az alakzatgyűjteményhez.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

Lekéri a diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Az alakzatgyűjtemény, amelyhez a diagram hozzáadódik. |
| x | float | Az X koordináta a diagram elhelyezéséhez. |
| y | float | Az Y koordináta a diagram elhelyezéséhez. |
| workbookPath | java.lang.String | A fájlútvonal a diagramot tartalmazó munkafüzethez. |
| worksheetName | java.lang.String | A munkalap neve, amely a diagramot tartalmazza. |
| chartName | java.lang.String | A hozzáadandó diagram neve. |
| embedWorkbook | boolean | Ha igaz, a munkafüzet be lesz ágyazva a diagramba; ha hamis, a diagram egy külső munkafüzetre hivatkozik. |

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart) - A diagram, amely hozzá lett adva az alakzatgyűjteményhez.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

Lekéri a táblázatot a megadott Excel-munkafüzetből, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Az alakzatgyűjtemény, amelyhez a táblázat hozzáadódik. |
| x | float | Az X koordináta a táblázat elhelyezéséhez. |
| y | float | Az Y koordináta a táblázat elhelyezéséhez. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Az Excel-munkafüzet. |
| worksheetName | java.lang.String | A munkalap neve, amely a táblázatot tartalmazza. |
| cellRange | java.lang.String | A cellatartomány, amely meghatározza a táblázatot (például "A1:D10"). |

**Visszatérési érték:**
[ITable](../../com.aspose.slides/itable) - A táblázat, amely hozzá lett adva az alakzatgyűjteményhez.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

Lekéri a táblázatot a megadott Excel-munkafüzet-fájlból, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Az alakzatgyűjtemény, amelyhez a táblázat hozzáadódik. |
| x | float | Az X koordináta a táblázat elhelyezéséhez. |
| y | float | Az Y koordináta a táblázat elhelyezéséhez. |
| workbookPath | java.lang.String | Az Excel-munkafüzet fájlának elérési útja. |
| worksheetName | java.lang.String | A munkalap neve, amely a táblázatot tartalmazza. |
| cellRange | java.lang.String | A cellatartomány, amely meghatározza a táblázatot (például "A1:D10"). |

**Visszatérési érték:**
[ITable](../../com.aspose.slides/itable) - A táblázat, amely hozzá lett adva az alakzatgyűjteményhez.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

Lekéri a táblázatot a megadott Excel-munkafüzet-fájlból, és a megadott koordinátákon a megadott alakzatgyűjtemény végéhez adja hozzá.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Az alakzatgyűjtemény, amelyhez a táblázat hozzáadódik. |
| x | float | Az X koordináta a táblázat elhelyezéséhez. |
| y | float | Az Y koordináta a táblázat elhelyezéséhez. |
| workbookStream | java.io.InputStream | Az adatfolyam, amely a munkafüzet adatait tartalmazza. |
| worksheetName | java.lang.String | A munkalap neve, amely a táblázatot tartalmazza. |
| cellRange | java.lang.String | A cellatartomány, amely meghatározza a táblázatot (például "A1:D10"). |

**Visszatérési érték:**
[ITable](../../com.aspose.slides/itable) - A táblázat, amely hozzá lett adva az alakzatgyűjteményhez.