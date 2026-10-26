---
title: ExcelWorkbookImporter
second_title: Referencia de la API de Aspose.Slides para Android mediante Java
description: Proporciona funcionalidad para importar contenido desde un libro de Excel a una presentación.
type: docs
url: /es/com.aspose.slides/excelworkbookimporter/
---
**Herencia:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Proporciona funcionalidad para importar contenido desde un libro de Excel a una presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Recupera un gráfico del libro de Excel especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Recupera un gráfico del libro de Excel especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Recupera un gráfico del libro de Excel especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Recupera un gráfico del libro de Excel especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Recupera una tabla del libro de Excel especificado y la agrega al final de la colección de formas proporcionada en las coordenadas especificadas. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Recupera una tabla del archivo de libro de Excel especificado y la agrega al final de la colección de formas proporcionada en las coordenadas especificadas. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Recupera una tabla del archivo de libro de Excel especificado y la agrega al final de la colección de formas proporcionada en las coordenadas especificadas. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

Recupera un gráfico del libro de Excel especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La colección de formas a la que se agregará el gráfico. |
| x | float | La coordenada X para posicionar el gráfico. |
| y | float | La coordenada Y para posicionar el gráfico. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | El libro de Excel. |
| worksheetName | java.lang.String | El nombre de la hoja de cálculo que contiene el gráfico. |
| chartIndex | int | El índice basado en cero de la forma del gráfico a insertar. Este índice puede obtenerse mediante el método [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-). |
| embedAllWorkbook | boolean | Si es verdadero, todo el libro de Excel se incrustará en el gráfico; si es falso, solo se incrustarán los datos del gráfico. |

**Devuelve:**
[IChart](../../com.aspose.slides/ichart) - El gráfico que se agregó a la colección de formas.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Recupera un gráfico del libro de Excel especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La colección de formas a la que se agregará el gráfico. |
| x | float | La coordenada X para posicionar el gráfico. |
| y | float | La coordenada Y para posicionar el gráfico. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | El libro de Excel. |
| worksheetName | java.lang.String | El nombre de la hoja de cálculo que contiene el gráfico. |
| chartName | java.lang.String | El nombre del gráfico a agregar. |
| embedAllWorkbook | boolean | Si es verdadero, todo el libro de Excel se incrustará en el gráfico; si es falso, solo se incrustarán los datos del gráfico. |

**Devuelve:**
[IChart](../../com.aspose.slides/ichart) - El gráfico que se agregó a la colección de formas.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Recupera un gráfico del libro de Excel especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La colección de formas a la que se agregará el gráfico. |
| x | float | La coordenada X para posicionar el gráfico. |
| y | float | La coordenada Y para posicionar el gráfico. |
| workbookStream | java.io.InputStream | Un flujo que contiene los datos del libro. |
| worksheetName | java.lang.String | El nombre de la hoja de cálculo que contiene el gráfico. |
| chartName | java.lang.String | El nombre del gráfico a agregar. |
| embedAllWorkbook | boolean | Si es verdadero, todo el libro de Excel se incrustará en el gráfico; si es falso, solo se incrustarán los datos del gráfico. |

**Devuelve:**
[IChart](../../com.aspose.slides/ichart) - El gráfico que se agregó a la colección de formas.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

Recupera un gráfico del libro de Excel especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La colección de formas a la que se agregará el gráfico. |
| x | float | La coordenada X para posicionar el gráfico. |
| y | float | La coordenada Y para posicionar el gráfico. |
| workbookPath | java.lang.String | La ruta del archivo del libro que contiene el gráfico. |
| worksheetName | java.lang.String | El nombre de la hoja de cálculo que contiene el gráfico. |
| chartName | java.lang.String | El nombre del gráfico a agregar. |
| embedWorkbook | boolean | Si es verdadero, el libro de Excel se incrustará en el gráfico; si es falso, el gráfico enlazará al libro externo. |

**Devuelve:**
[IChart](../../com.aspose.slides/ichart) - El gráfico que se agregó a la colección de formas.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

Recupera una tabla del libro de Excel especificado y la agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La colección de formas a la que se agregará la tabla. |
| x | float | La coordenada X para posicionar la tabla. |
| y | float | La coordenada Y para posicionar la tabla. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | El libro de Excel. |
| worksheetName | java.lang.String | El nombre de la hoja de cálculo que contiene la tabla. |
| cellRange | java.lang.String | El rango de celdas que define la tabla (por ejemplo, "A1:D10"). |

**Devuelve:**
[ITable](../../com.aspose.slides/itable) - La tabla que se agregó a la colección de formas.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

Recupera una tabla del archivo de libro de Excel especificado y la agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La colección de formas a la que se agregará la tabla. |
| x | float | La coordenada X para posicionar la tabla. |
| y | float | La coordenada Y para posicionar la tabla. |
| workbookPath | java.lang.String | La ruta al archivo del libro de Excel. |
| worksheetName | java.lang.String | El nombre de la hoja de cálculo que contiene la tabla. |
| cellRange | java.lang.String | El rango de celdas que define la tabla (por ejemplo, "A1:D10"). |

**Devuelve:**
[ITable](../../com.aspose.slides/itable) - La tabla que se agregó a la colección de formas.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

Recupera una tabla del archivo de libro de Excel especificado y la agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La colección de formas a la que se agregará la tabla. |
| x | float | La coordenada X para posicionar la tabla. |
| y | float | La coordenada Y para posicionar la tabla. |
| workbookStream | java.io.InputStream | Un flujo que contiene los datos del libro. |
| worksheetName | java.lang.String | El nombre de la hoja de cálculo que contiene la tabla. |
| cellRange | java.lang.String | El rango de celdas que define la tabla (por ejemplo, "A1:D10"). |

**Devuelve:**
[ITable](../../com.aspose.slides/itable) - La tabla que se agregó a la colección de formas.