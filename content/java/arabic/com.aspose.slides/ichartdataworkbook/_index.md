---
title: IChartDataWorkbook
second_title: Aspose.Slides for Java مرجع API
description: يوفر إمكانية الوصول إلى دفتر عمل Excel المضمّن
type: docs
url: /ar/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

يوفر إمكانية الوصول إلى دفتر عمل Excel المضمّن
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | يحسب جميع الصيغ في دفتر العمل ويحدث القيم المقابلة للخلايا. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | يحصل على مجموعة الخلايا. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | يحصل على الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | يحصل على الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | يحصل على الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | يحصل على الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | يحصل على الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات |
| [clear(int sheetIndex)](#clear-int-) | مسح جميع قيم الخلايا في الورقة |
| [getWorksheets()](#getWorksheets--) | يحصل على مجموعة من أوراق العمل. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```

يحسب جميع الصيغ في دفتر العمل ويحدث القيم المقابلة للخلايا.

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

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public abstract IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

يحصل على مجموعة الخلايا.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| formula | java.lang.String | صيغة Excel مثل "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | إذا كان true فترجع الطريقة مجموعة دون الخلايا المخفية. |

**الإرجاع:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - مجموعة من الخلايا [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```

يحصل على الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetName | java.lang.String | اسم ورقة العمل. |
| row | int | الصف. |
| column | int | العمود. |

**الإرجاع:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - كائن Cell
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```

يحصل على الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | int | فهرس ورقة العمل. |
| row | int | الصف. |
| column | int | العمود. |

**الإرجاع:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - كائن Cell
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```

يحصل على الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | int | فهرس ورقة العمل. |
| cellName | java.lang.String | اسم الخلية. |

**الإرجاع:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - كائن Cell
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

يحصل على الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | int | فهرس ورقة العمل. |
| cellName | java.lang.String | اسم الخلية. |
| value | java.lang.Object | القيمة. |

**الإرجاع:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - كائن Cell
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

يحصل على الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | int | فهرس ورقة العمل. |
| row | int | الصف. |
| column | int | العمود. |
| value | java.lang.Object | القيمة. |

**الإرجاع:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - كائن Cell
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```

مسح جميع قيم الخلايا في الورقة

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sheetIndex | int | فهرس الورقة |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
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

**الإرجاع:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)