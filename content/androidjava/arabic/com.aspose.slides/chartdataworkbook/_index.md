---
title: ChartDataWorkbook
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يوفر إمكانية الوصول إلى مصنف Excel المضمن
type: docs
url: /ar/com.aspose.slides/chartdataworkbook/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)  
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

يوفر إمكانية الوصول إلى مصنف Excel المضمن
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | يحصل على مجموعة من أوراق العمل. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | يحصل على مجموعة الخلايا. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | يحصل على الخلية التي يمكن استخدامها لسلسلة المخطط أو الفئات |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | يحصل على الخلية التي يمكن استخدامها لسلسلة المخطط أو الفئات |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | يحصل على الخلية التي يمكن استخدامها لسلسلة المخطط أو الفئات |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | يحصل على الخلية التي يمكن استخدامها لسلسلة المخطط أو الفئات |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | يحصل على الخلية التي يمكن استخدامها لسلسلة المخطط أو الفئات |
| [clear(int sheetIndex)](#clear-int-) | يمسح جميع قيم الخلايا في الورقة |
| [calculateFormulas()](#calculateFormulas--) | يحسب جميع الصيغ في المصنف ويحدّث قيم الخلايا المقابلة. |

### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```

يحصل على مجموعة من أوراق العمل.

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

**القيمة المرجعة:**  
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

يحصل على مجموعة الخلايا.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| formula | java.lang.String | صيغة Excel مثل "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | إذا كان true فستُرجع الطريقة مجموعة بدون الخلايا المخفية. |

**القيمة المرجعة:**  
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

يحصل على الخلية التي يمكن استخدامها لسلسلة المخطط أو الفئات

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| worksheetName | java.lang.String | اسم ورقة العمل. |
| row | int | الصف. |
| column | int | العمود. |

**القيمة المرجعة:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

يحصل على الخلية التي يمكن استخدامها لسلسلة المخطط أو الفئات

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | int | فهرس ورقة العمل. |
| row | int | الصف. |
| column | int | العمود. |

**القيمة المرجعة:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

يحصل على الخلية التي يمكن استخدامها لسلسلة المخطط أو الفئات

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | int | فهرس ورقة العمل. |
| cellName | java.lang.String | اسم الخلية. |

**القيمة المرجعة:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

يحصل على الخلية التي يمكن استخدامها لسلسلة المخطط أو الفئات

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | int | فهرس ورقة العمل. |
| cellName | java.lang.String | اسم الخلية. |
| value | java.lang.Object | القيمة. |

**القيمة المرجعة:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

يحصل على الخلية التي يمكن استخدامها لسلسلة المخطط أو الفئات

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | int | فهرس ورقة العمل. |
| row | int | الصف. |
| column | int | العمود. |
| value | java.lang.Object | القيمة. |

**القيمة المرجعة:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

يمسح جميع قيم الخلايا في الورقة

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| sheetIndex | int | فهرس الورقة |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```

يحسب جميع الصيغ في المصنف ويحدّث قيم الخلايا المقابلة.

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