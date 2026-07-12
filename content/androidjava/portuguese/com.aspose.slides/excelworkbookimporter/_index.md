---
title: ExcelWorkbookImporter
second_title: Aspose.Slides para Android via Referência da API Java
description: Fornece funcionalidade para importar conteúdo de uma pasta de trabalho Excel para uma apresentação.
type: docs
url: /pt/com.aspose.slides/excelworkbookimporter/
---
**Herança:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Fornece funcionalidade para importar conteúdo de uma pasta de trabalho do Excel para uma apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Recupera um gráfico da pasta de trabalho Excel especificada e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Recupera um gráfico da pasta de trabalho Excel especificada e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Recupera um gráfico da pasta de trabalho Excel especificada e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Recupera um gráfico da pasta de trabalho Excel especificada e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Recupera uma tabela da pasta de trabalho Excel especificada e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Recupera uma tabela do arquivo da pasta de trabalho Excel especificado e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Recupera uma tabela do arquivo da pasta de trabalho Excel especificado e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```


Recupera um gráfico da pasta de trabalho Excel especificada e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | A coleção de formas à qual o gráfico será adicionado. |
| x | float | A coordenada X para posicionar o gráfico. |
| y | float | A coordenada Y para posicionar o gráfico. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | A pasta de trabalho Excel. |
| worksheetName | java.lang.String | O nome da planilha que contém o gráfico. |
| chartIndex | int | O índice baseado em zero da forma de gráfico a ser inserida. Esse índice pode ser obtido usando o método [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-). |
| embedAllWorkbook | boolean | Se true, toda a pasta de trabalho será incorporada ao gráfico; se false, apenas os dados do gráfico serão incorporados. |

**Retorna:**
[IChart](../../com.aspose.slides/ichart) - O gráfico que foi adicionado à coleção de formas.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```


Recupera um gráfico da pasta de trabalho Excel especificada e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | A coleção de formas à qual o gráfico será adicionado. |
| x | float | A coordenada X para posicionar o gráfico. |
| y | float | A coordenada Y para posicionar o gráfico. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | A pasta de trabalho Excel. |
| worksheetName | java.lang.String | O nome da planilha que contém o gráfico. |
| chartName | java.lang.String | O nome do gráfico a ser adicionado. |
| embedAllWorkbook | boolean | Se true, toda a pasta de trabalho será incorporada ao gráfico; se false, apenas os dados do gráfico serão incorporados. |

**Retorna:**
[IChart](../../com.aspose.slides/ichart) - O gráfico que foi adicionado à coleção de formas.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```


Recupera um gráfico da pasta de trabalho Excel especificada e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | A coleção de formas à qual o gráfico será adicionado. |
| x | float | A coordenada X para posicionar o gráfico. |
| y | float | A coordenada Y para posicionar o gráfico. |
| workbookStream | java.io.InputStream | Um fluxo contendo os dados da pasta de trabalho. |
| worksheetName | java.lang.String | O nome da planilha que contém o gráfico. |
| chartName | java.lang.String | O nome do gráfico a ser adicionado. |
| embedAllWorkbook | boolean | Se true, toda a pasta de trabalho será incorporada ao gráfico; se false, apenas os dados do gráfico serão incorporados. |

**Retorna:**
[IChart](../../com.aspose.slides/ichart) - O gráfico que foi adicionado à coleção de formas.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```


Recupera um gráfico da pasta de trabalho Excel especificada e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | A coleção de formas à qual o gráfico será adicionado. |
| x | float | A coordenada X para posicionar o gráfico. |
| y | float | A coordenada Y para posicionar o gráfico. |
| workbookPath | java.lang.String | O caminho do arquivo para a pasta de trabalho que contém o gráfico. |
| worksheetName | java.lang.String | O nome da planilha que contém o gráfico. |
| chartName | java.lang.String | O nome do gráfico a ser adicionado. |
| embedWorkbook | boolean | Se true, a pasta de trabalho será incorporada ao gráfico; se false, o gráfico fará link para a pasta de trabalho externa. |

**Retorna:**
[IChart](../../com.aspose.slides/ichart) - O gráfico que foi adicionado à coleção de formas.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```


Recupera uma tabela da pasta de trabalho Excel especificada e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | A coleção de formas à qual a tabela será adicionada. |
| x | float | A coordenada X para posicionar a tabela. |
| y | float | A coordenada Y para posicionar a tabela. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | A pasta de trabalho Excel. |
| worksheetName | java.lang.String | O nome da planilha que contém a tabela. |
| cellRange | java.lang.String | O intervalo de células que define a tabela (por exemplo, "A1:D10"). |

**Retorna:**
[ITable](../../com.aspose.slides/itable) - A tabela que foi adicionada à coleção de formas.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```


Recupera uma tabela do arquivo da pasta de trabalho Excel especificado e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | A coleção de formas à qual a tabela será adicionada. |
| x | float | A coordenada X para posicionar a tabela. |
| y | float | A coordenada Y para posicionar a tabela. |
| workbookPath | java.lang.String | O caminho para o arquivo da pasta de trabalho Excel. |
| worksheetName | java.lang.String | O nome da planilha que contém a tabela. |
| cellRange | java.lang.String | O intervalo de células que define a tabela (por exemplo, "A1:D10"). |

**Retorna:**
[ITable](../../com.aspose.slides/itable) - A tabela que foi adicionada à coleção de formas.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```


Recupera uma tabela do arquivo da pasta de trabalho Excel especificado e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | A coleção de formas à qual a tabela será adicionada. |
| x | float | A coordenada X para posicionar a tabela. |
| y | float | A coordenada Y para posicionar a tabela. |
| workbookStream | java.io.InputStream | Um fluxo contendo os dados da pasta de trabalho. |
| worksheetName | java.lang.String | O nome da planilha que contém a tabela. |
| cellRange | java.lang.String | O intervalo de células que define a tabela (por exemplo, "A1:D10"). |

**Retorna:**
[ITable](../../com.aspose.slides/itable) - A tabela que foi adicionada à coleção de formas.