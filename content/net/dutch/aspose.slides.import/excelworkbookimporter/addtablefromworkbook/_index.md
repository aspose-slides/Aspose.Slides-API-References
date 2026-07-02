---
title: AddTableFromWorkbook
second_title: Aspose.Sildes voor .NET API-referentie
description: Haalt een tabel op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven shape-collectie op de opgegeven coördinaten.
type: docs
weight: 20
url: /nl/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

Haalt een tabel op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven shape-verzameling op de opgegeven coördinaten.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | De shape-verzameling waaraan de tabel zal worden toegevoegd. |
| x | Single | De X-coördinaat voor het positioneren van de tabel. |
| y | Single | De Y-coördinaat voor het positioneren van de tabel. |
| workbook | IExcelDataWorkbook | De Excel-werkmap. |
| worksheetName | String | De naam van het werkblad dat de tabel bevat. |
| cellRange | String | Het celbereik dat de tabel definieert (bijvoorbeeld "A1:D10"). |

### Return Value

De tabel die aan de shape-verzameling is toegevoegd.

### Exceptions

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer een vereist parameter null of leeg is, of wanneer het opgegeven werkblad of celbereik ongeldig is. |
| InvalidOperationException | Wordt gegooid wanneer de invoergegevens in een niet-ondersteund formaat zijn. |

### Examples

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [ITable](../../../aspose.slides/itable)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* klasse [ExcelWorkbookImporter](../../excelworkbookimporter)
* naamruimte [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

Haalt een tabel op uit het opgegeven Excel-werkmapbestand en voegt deze toe aan het einde van de opgegeven shape-verzameling op de opgegeven coördinaten.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | De shape-verzameling waaraan de tabel zal worden toegevoegd. |
| x | Single | De X-coördinaat voor het positioneren van de tabel. |
| y | Single | De Y-coördinaat voor het positioneren van de tabel. |
| workbookPath | String | Het pad naar het Excel-werkmapbestand. |
| worksheetName | String | De naam van het werkblad dat de tabel bevat. |
| cellRange | String | Het celbereik dat de tabel definieert (bijvoorbeeld "A1:D10"). |

### Return Value

De tabel die aan de shape-verzameling is toegevoegd.

### Exceptions

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer een vereist parameter null of leeg is, of wanneer het opgegeven werkblad of celbereik ongeldig is. |
| IOException | Wordt gegooid wanneer er een I/O-fout optreedt bij het openen van het werkmapbestand. |
| InvalidOperationException | Wordt gegooid wanneer de invoergegevens in een niet-ondersteund formaat zijn. |

### Examples

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [ITable](../../../aspose.slides/itable)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* klasse [ExcelWorkbookImporter](../../excelworkbookimporter)
* naamruimte [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

Haalt een tabel op uit het opgegeven Excel-werkmapbestand en voegt deze toe aan het einde van de opgegeven shape-verzameling op de opgegeven coördinaten.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | De shape-verzameling waaraan de tabel zal worden toegevoegd. |
| x | Single | De X-coördinaat voor het positioneren van de tabel. |
| y | Single | De Y-coördinaat voor het positioneren van de tabel. |
| workbookStream | Stream | Een stroom die de werkmapgegevens bevat. |
| worksheetName | String | De naam van het werkblad dat de tabel bevat. |
| cellRange | String | Het celbereik dat de tabel definieert (bijvoorbeeld "A1:D10"). |

### Return Value

De tabel die aan de shape-verzameling is toegevoegd.

### Exceptions

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer een vereist parameter null of leeg is, of wanneer het opgegeven werkblad of celbereik ongeldig is. |
| InvalidOperationException | Wordt gegooid wanneer de invoergegevens in een niet-ondersteund formaat zijn. |

### Examples

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [ITable](../../../aspose.slides/itable)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* klasse [ExcelWorkbookImporter](../../excelworkbookimporter)
* naamruimte [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->