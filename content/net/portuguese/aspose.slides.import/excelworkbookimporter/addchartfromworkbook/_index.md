---
title: AddChartFromWorkbook
second_title: Aspose.Sildes para .NET Referência da API
description: Recupera um gráfico do workbook do Excel especificado e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.
type: docs
weight: 10
url: /pt/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

Recupera um gráfico do workbook do Excel especificado e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | IShapeCollection | A coleção de formas à qual o gráfico será adicionado. |
| x | Single | A coordenada X para posicionamento do gráfico. |
| y | Single | A coordenada Y para posicionamento do gráfico. |
| workbook | IExcelDataWorkbook | O workbook do Excel. |
| worksheetName | String | O nome da planilha que contém o gráfico. |
| chartIndex | Int32 | O índice baseado em zero da forma de gráfico a ser inserida. Esse índice pode ser obtido usando o método [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet). |
| embedAllWorkbook | Boolean | Se `true`, o workbook inteiro será incorporado ao gráfico; se `false`, somente os dados do gráfico serão incorporados. |

### Valor de Retorno

O gráfico que foi adicionado à coleção de formas.

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentException | Lançada quando qualquer parâmetro obrigatório for nulo, vazio ou se o gráfico não puder ser encontrado no workbook. |

### Exemplos

Exemplo:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Ver também

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* classe [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

Recupera um gráfico do workbook do Excel especificado e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | IShapeCollection | A coleção de formas à qual o gráfico será adicionado. |
| x | Single | A coordenada X para posicionamento do gráfico. |
| y | Single | A coordenada Y para posicionamento do gráfico. |
| workbook | IExcelDataWorkbook | O workbook do Excel. |
| worksheetName | String | O nome da planilha que contém o gráfico. |
| chartName | String | O nome do gráfico a ser adicionado. |
| embedAllWorkbook | Boolean | Se `true`, o workbook inteiro será incorporado ao gráfico; se `false`, somente os dados do gráfico serão incorporados. |

### Valor de Retorno

O gráfico que foi adicionado à coleção de formas.

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentException | Lançada quando qualquer parâmetro obrigatório for nulo, vazio ou se o gráfico não puder ser encontrado no workbook. |

### Exemplos

Exemplo:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    string worksheetName = "worksheet name";
    var worksheetCharts = wb.GetChartsFromWorksheet(worksheetName);
    foreach (var chart in worksheetCharts)
    {
        ISlide slide = pres.Slides.AddEmptySlide(pres.LayoutSlides[0]);
        ExcelWorkbookImporter.AddChartFromWorkbook(slide.Shapes, 10, 10, wb, worksheetName, chart.Key, false);
    }
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Ver também

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* classe [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

Recupera um gráfico do workbook do Excel especificado e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | IShapeCollection | A coleção de formas à qual o gráfico será adicionado. |
| x | Single | A coordenada X para posicionamento do gráfico. |
| y | Single | A coordenada Y para posicionamento do gráfico. |
| workbookStream | Stream | Um fluxo contendo os dados do workbook. |
| worksheetName | String | O nome da planilha que contém o gráfico. |
| chartName | String | O nome do gráfico a ser adicionado. |
| embedAllWorkbook | Boolean | Se `true`, o workbook inteiro será incorporado ao gráfico; se `false`, somente os dados do gráfico serão incorporados. |

### Valor de Retorno

O gráfico que foi adicionado à coleção de formas.

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentException | Lançada quando qualquer parâmetro obrigatório for nulo, vazio ou se o gráfico não puder ser encontrado no workbook. |
| InvalidOperationException | Lançada quando os dados de entrada estão em um formato não suportado. |

### Exemplos

Exemplo:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Ver também

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* classe [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

Recupera um gráfico do workbook do Excel especificado e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | IShapeCollection | A coleção de formas à qual o gráfico será adicionado. |
| x | Single | A coordenada X para posicionamento do gráfico. |
| y | Single | A coordenada Y para posicionamento do gráfico. |
| workbookPath | String | O caminho do arquivo para o workbook que contém o gráfico. |
| worksheetName | String | O nome da planilha que contém o gráfico. |
| chartName | String | O nome do gráfico a ser adicionado. |
| embedWorkbook | Boolean | Se `true`, o workbook será incorporado ao gráfico; se `false`, o gráfico será ligado ao workbook externo. |

### Valor de Retorno

O gráfico que foi adicionado à coleção de formas.

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentException | Lançada quando qualquer parâmetro obrigatório for nulo, vazio ou se o gráfico não puder ser encontrado no workbook. |
| IOException | Lançada quando ocorre um erro de E/S ao acessar o arquivo. |
| InvalidOperationException | Lançada quando os dados de entrada estão em um formato não suportado. |

### Exemplos

Exemplo:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Ver também

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* classe [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->