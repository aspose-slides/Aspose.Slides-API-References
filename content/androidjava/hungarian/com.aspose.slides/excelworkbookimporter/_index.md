---
title: ExcelWorkbookImporter
second_title: Aspose.Slides Androidhoz a Java API hivatkozás alapján
description: Funkciókat biztosít az Excel-munkafüzetből származó tartalom importálásához egy bemutatóba.
type: docs
url: /hu/com.aspose.slides/excelworkbookimporter/
---
**Öröklődés:**  
java.lang.Object  
```
public class ExcelWorkbookImporter
```

Funkciókat biztosít az Excel-munkafüzetből származó tartalom importálásához egy bemutatóba.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Lekéri egy diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a shape-gyűjtemény végére helyezi. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Lekéri egy diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a shape-gyűjtemény végére helyezi. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Lekéri egy diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a shape-gyűjtemény végére helyezi. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Lekéri egy diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a shape-gyűjtemény végére helyezi. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Lekéri egy táblázatot a megadott Excel-munkafüzetből, és a megadott koordinátákon a shape-gyűjtemény végére helyezi. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Lekéri egy táblázatot a megadott Excel-munkafüzet fájlból, és a megadott koordinátákon a shape-gyűjtemény végére helyezi. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Lekéri egy táblázatot a megadott Excel-munkafüzet fájlból, és a megadott koordinátákon a shape-gyűjtemény végére helyezi. |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

Lekéri egy diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a shape-gyűjtemény végére helyezi.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Az a shape-gyűjtemény, amelyhez a diagramot hozzá kell adni. |
| x | float | A diagram X koordinátája. |
| y | float | A diagram Y koordinátája. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Az Excel-munkafüzet. |
| worksheetName | java.lang.String | A munkalap neve, amely tartalmazza a diagramot. |
| chartIndex | int | A diagram shape nullától induló indexe a beszúráshoz. Ez az index a [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) módszerrel szerezhető meg. |
| embedAllWorkbook | boolean | Ha igaz, a teljes munkafüzet beágyazásra kerül a diagramba; ha hamis, csak a diagram adatai lesznek beágyazva. |

**Visszatérési érték:**  
[IChart](../../com.aspose.slides/ichart) – A shape-gyűjteményhez hozzáadott diagram.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Lekéri egy diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a shape-gyűjtemény végére helyezi.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Az a shape-gyűjtemény, amelyhez a diagramot hozzá kell adni. |
| x | float | A diagram X koordinátája. |
| y | float | A diagram Y koordinátája. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Az Excel-munkafüzet. |
| worksheetName | java.lang.String | A munkalap neve, amely tartalmazza a diagramot. |
| chartName | java.lang.String | A hozzáadandó diagram neve. |
| embedAllWorkbook | boolean | Ha igaz, a teljes munkafüzet beágyazásra kerül a diagramba; ha hamis, csak a diagram adatai lesznek beágyazva. |

**Visszatérési érték:**  
[IChart](../../com.aspose.slides/ichart) – A shape-gyűjteményhez hozzáadott diagram.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Lekéri egy diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a shape-gyűjtemény végére helyezi.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Az a shape-gyűjtemény, amelyhez a diagramot hozzá kell adni. |
| x | float | A diagram X koordinátája. |
| y | float | A diagram Y koordinátája. |
| workbookStream | java.io.InputStream | A munkafüzet adatát tartalmazó adatfolyam. |
| worksheetName | java.lang.String | A munkalap neve, amely tartalmazza a diagramot. |
| chartName | java.lang.String | A hozzáadandó diagram neve. |
| embedAllWorkbook | boolean | Ha igaz, a teljes munkafüzet beágyazásra kerül a diagramba; ha hamis, csak a diagram adatai lesznek beágyazva. |

**Visszatérési érték:**  
[IChart](../../com.aspose.slides/ichart) – A shape-gyűjteményhez hozzáadott diagram.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

Lekéri egy diagramot a megadott Excel-munkafüzetből, és a megadott koordinátákon a shape-gyűjtemény végére helyezi.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Az a shape-gyűjtemény, amelyhez a diagramot hozzá kell adni. |
| x | float | A diagram X koordinátája. |
| y | float | A diagram Y koordinátája. |
| workbookPath | java.lang.String | A diagramot tartalmazó munkafüzet fájlútvonala. |
| worksheetName | java.lang.String | A munkalap neve, amely tartalmazza a diagramot. |
| chartName | java.lang.String | A hozzáadandó diagram neve. |
| embedWorkbook | boolean | Ha igaz, a munkafüzet beágyazásra kerül a diagramba; ha hamis, a diagram külső munkafüzethez fog kapcsolódni. |

**Visszatérési érték:**  
[IChart](../../com.aspose.slides/ichart) – A shape-gyűjteményhez hozzáadott diagram.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

Lekéri egy táblázatot a megadott Excel-munkafüzetből, és a megadott koordinátákon a shape-gyűjtemény végére helyezi.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Az a shape-gyűjtemény, amelyhez a táblázatot hozzá kell adni. |
| x | float | A táblázat X koordinátája. |
| y | float | A táblázat Y koordinátája. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Az Excel-munkafüzet. |
| worksheetName | java.lang.String | A munkalap neve, amely tartalmazza a táblázatot. |
| cellRange | java.lang.String | A táblázatot definiáló cellatartomány (például „A1:D10”). |

**Visszatérési érték:**  
[ITable](../../com.aspose.slides/itable) – A shape-gyűjteményhez hozzáadott táblázat.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

Lekéri egy táblázatot a megadott Excel-munkafüzet fájlból, és a megadott koordinátákon a shape-gyűjtemény végére helyezi.

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

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Az a shape-gyűjtemény, amelyhez a táblázatot hozzá kell adni. |
| x | float | A táblázat X koordinátája. |
| y | float | A táblázat Y koordinátája. |
| workbookPath | java.lang.String | Az Excel-munkafüzet fájlútvonala. |
| worksheetName | java.lang.String | A munkalap neve, amely tartalmazza a táblázatot. |
| cellRange | java.lang.String | A táblázatot definiáló cellatartomány (például „A1:D10”). |

**Visszatérési érték:**  
[ITable](../../com.aspose.slides/itable) – A shape-gyűjteményhez hozzáadott táblázat.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

Lekéri egy táblázatot a megadott Excel-munkafüzet fájlból, és a megadott koordinátákon a shape-gyűjtemény végére helyezi.

--------------------

> ```
> FileInputStream fStream = new FileInputStream(workbookPath);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Az a shape-gyűjtemény, amelyhez a táblázatot hozzá kell adni. |
| x | float | A táblázat X koordinátája. |
| y | float | A táblázat Y koordinátája. |
| workbookStream | java.io.InputStream | A munkafüzet adatát tartalmazó adatfolyam. |
| worksheetName | java.lang.String | A munkalap neve, amely tartalmazza a táblázatot. |
| cellRange | java.lang.String | A táblázatot definiáló cellatartomány (például „A1:D10”). |

**Visszatérési érték:**  
[ITable](../../com.aspose.slides/itable) – A shape-gyűjteményhez hozzáadott táblázat.