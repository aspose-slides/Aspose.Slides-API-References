---
title: ExcelWorkbookImporter
second_title: Référence de l'API Aspose.Slides pour Java
description: Fournit des fonctionnalités d'importation de contenu depuis un classeur Excel vers une présentation.
type: docs
url: /fr/com.aspose.slides/excelworkbookimporter/
---
**Héritage:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Fournit des fonctionnalités pour importer du contenu depuis un classeur Excel dans une présentation.

## Méthodes

| Méthode | Description |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Retrieves a table from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Retrieves a table from the specified Excel workbook file and adds it to the end of the given shape collection at the specified coordinates. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Retrieves a table from the specified Excel workbook file and adds it to the end of the given shape collection at the specified coordinates. |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

Récupère un graphique depuis le classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.

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


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La collection de formes à laquelle le graphique sera ajouté. |
| x | float | La coordonnée X pour positionner le graphique. |
| y | float | La coordonnée Y pour positionner le graphique. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Le classeur Excel. |
| worksheetName | java.lang.String | Le nom de la feuille de calcul contenant le graphique. |
| chartIndex | int | L’index zéro-based du graphique à insérer. Cet index peut être obtenu à l’aide de la méthode [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-). |
| embedAllWorkbook | boolean | Si vrai, le classeur entier sera intégré dans le graphique ; si faux, seules les données du graphique seront intégrées. |

**Renvoie:**
[IChart](../../com.aspose.slides/ichart) - Le graphique qui a été ajouté à la collection de formes.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Récupère un graphique depuis le classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.

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


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La collection de formes à laquelle le graphique sera ajouté. |
| x | float | La coordonnée X pour positionner le graphique. |
| y | float | La coordonnée Y pour positionner le graphique. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Le classeur Excel. |
| worksheetName | java.lang.String | Le nom de la feuille de calcul contenant le graphique. |
| chartName | java.lang.String | Le nom du graphique à ajouter. |
| embedAllWorkbook | boolean | Si vrai, le classeur entier sera intégré dans le graphique ; si faux, seules les données du graphique seront intégrées. |

**Renvoie:**
[IChart](../../com.aspose.slides/ichart) - Le graphique qui a été ajouté à la collection de formes.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Récupère un graphique depuis le classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La collection de formes à laquelle le graphique sera ajouté. |
| x | float | La coordonnée X pour positionner le graphique. |
| y | float | La coordonnée Y pour positionner le graphique. |
| workbookStream | java.io.InputStream | Un flux contenant les données du classeur. |
| worksheetName | java.lang.String | Le nom de la feuille de calcul contenant le graphique. |
| chartName | java.lang.String | Le nom du graphique à ajouter. |
| embedAllWorkbook | boolean | Si vrai, le classeur entier sera intégré dans le graphique ; si faux, seules les données du graphique seront intégrées. |

**Renvoie:**
[IChart](../../com.aspose.slides/ichart) - Le graphique qui a été ajouté à la collection de formes.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

Récupère un graphique depuis le classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La collection de formes à laquelle le graphique sera ajouté. |
| x | float | La coordonnée X pour positionner le graphique. |
| y | float | La coordonnée Y pour positionner le graphique. |
| workbookPath | java.lang.String | Le chemin du fichier du classeur contenant le graphique. |
| worksheetName | java.lang.String | Le nom de la feuille de calcul contenant le graphique. |
| chartName | java.lang.String | Le nom du graphique à ajouter. |
| embedWorkbook | boolean | Si vrai, le classeur sera intégré dans le graphique ; si faux, le graphique fera un lien vers le classeur externe. |

**Renvoie:**
[IChart](../../com.aspose.slides/ichart) - Le graphique qui a été ajouté à la collection de formes.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

Récupère un tableau depuis le classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La collection de formes à laquelle le tableau sera ajouté. |
| x | float | La coordonnée X pour positionner le tableau. |
| y | float | La coordonnée Y pour positionner le tableau. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Le classeur Excel. |
| worksheetName | java.lang.String | Le nom de la feuille de calcul contenant le tableau. |
| cellRange | java.lang.String | La plage de cellules qui définit le tableau (par exemple, "A1:D10"). |

**Renvoie:**
[ITable](../../com.aspose.slides/itable) - Le tableau qui a été ajouté à la collection de formes.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

Récupère un tableau depuis le classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La collection de formes à laquelle le tableau sera ajouté. |
| x | float | La coordonnée X pour positionner le tableau. |
| y | float | La coordonnée Y pour positionner le tableau. |
| workbookPath | java.lang.String | Le chemin du fichier du classeur Excel. |
| worksheetName | java.lang.String | Le nom de la feuille de calcul contenant le tableau. |
| cellRange | java.lang.String | La plage de cellules qui définit le tableau (par exemple, "A1:D10"). |

**Renvoie:**
[ITable](../../com.aspose.slides/itable) - Le tableau qui a été ajouté à la collection de formes.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

Récupère un tableau depuis le classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La collection de formes à laquelle le tableau sera ajouté. |
| x | float | La coordonnée X pour positionner le tableau. |
| y | float | La coordonnée Y pour positionner le tableau. |
| workbookStream | java.io.InputStream | Un flux contenant les données du classeur. |
| worksheetName | java.lang.String | Le nom de la feuille de calcul contenant le tableau. |
| cellRange | java.lang.String | La plage de cellules qui définit le tableau (par exemple, "A1:D10"). |

**Renvoie:**
[ITable](../../com.aspose.slides/itable) - Le tableau qui a été ajouté à la collection de formes.