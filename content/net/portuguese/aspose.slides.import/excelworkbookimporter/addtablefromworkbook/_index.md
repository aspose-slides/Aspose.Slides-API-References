---
title: AddTableFromWorkbook
second_title: Aspose.Sildes para .NET Referência da API
description: Recupera uma tabela da pasta de trabalho do Excel especificada e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.
type: docs
weight: 20
url: /pt/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

Recupera uma tabela da pasta de trabalho do Excel especificada e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | IShapeCollection | A coleção de formas à qual a tabela será adicionada. |
| x | Single | A coordenada X para posicionar a tabela. |
| y | Single | A coordenada Y para posicionar a tabela. |
| workbook | IExcelDataWorkbook | A pasta de trabalho do Excel. |
| worksheetName | String | O nome da planilha que contém a tabela. |
| cellRange | String | O intervalo de células que define a tabela (por exemplo, "A1:D10"). |

### Valor de Retorno

A tabela que foi adicionada à coleção de formas.

### Exceções

| Exceção | Condição |
| --- | --- |
| ArgumentException | Lançada quando qualquer parâmetro obrigatório é nulo ou vazio, ou quando a planilha ou o intervalo de células especificado é inválido. |
| InvalidOperationException | Lançada quando os dados de entrada estão em um formato não suportado. |

### Exemplos

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Veja Também

* interface [ITable](../../../aspose.slides/itable)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* classe [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

Recupera uma tabela do arquivo de pasta de trabalho do Excel especificado e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | IShapeCollection | A coleção de formas à qual a tabela será adicionada. |
| x | Single | A coordenada X para posicionar a tabela. |
| y | Single | A coordenada Y para posicionar a tabela. |
| workbookPath | String | O caminho para o arquivo de pasta de trabalho do Excel. |
| worksheetName | String | O nome da planilha que contém a tabela. |
| cellRange | String | O intervalo de células que define a tabela (por exemplo, "A1:D10"). |

### Valor de Retorno

A tabela que foi adicionada à coleção de formas.

### Exceções

| Exceção | Condição |
| --- | --- |
| ArgumentException | Lançada quando qualquer parâmetro obrigatório é nulo ou vazio, ou quando a planilha ou o intervalo de células especificado é inválido. |
| IOException | Lançada quando ocorre um erro de I/O ao acessar o arquivo da pasta de trabalho. |
| InvalidOperationException | Lançada quando os dados de entrada estão em um formato não suportado. |

### Exemplos

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Veja Também

* interface [ITable](../../../aspose.slides/itable)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* classe [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

Recupera uma tabela do arquivo de pasta de trabalho do Excel especificado e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapes | IShapeCollection | A coleção de formas à qual a tabela será adicionada. |
| x | Single | A coordenada X para posicionar a tabela. |
| y | Single | A coordenada Y para posicionar a tabela. |
| workbookStream | Stream | Um fluxo contendo os dados da pasta de trabalho. |
| worksheetName | String | O nome da planilha que contém a tabela. |
| cellRange | String | O intervalo de células que define a tabela (por exemplo, "A1:D10"). |

### Valor de Retorno

A tabela que foi adicionada à coleção de formas.

### Exceções

| Exceção | Condição |
| --- | --- |
| ArgumentException | Lançada quando qualquer parâmetro obrigatório é nulo ou vazio, ou quando a planilha ou o intervalo de células especificado é inválido. |
| InvalidOperationException | Lançada quando os dados de entrada estão em um formato não suportado. |

### Exemplos

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Veja Também

* interface [ITable](../../../aspose.slides/itable)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* classe [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->