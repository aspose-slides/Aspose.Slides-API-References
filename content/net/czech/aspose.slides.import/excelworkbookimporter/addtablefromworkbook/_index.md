---
title: AddTableFromWorkbook
second_title: Aspose.Sildes pro .NET API Reference
description: Načte tabulku ze zadaného Excel sešitu a přidá ji na konec dané kolekce tvarů na zadaných souřadnicích.
type: docs
weight: 20
url: /cs/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

Načte tabulku ze zadaného Excel sešitu a přidá ji na konec dané kolekce tvarů na zadaných souřadnicích.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | IShapeCollection | Kolekce tvarů, do které bude tabulka přidána. |
| x | Single | Souřadnice X pro umístění tabulky. |
| y | Single | Souřadnice Y pro umístění tabulky. |
| workbook | IExcelDataWorkbook | Excel sešit. |
| worksheetName | String | Název listu, který tabulku obsahuje. |
| cellRange | String | Rozsah buněk, který tabulku určuje (například "A1:D10"). |

### Návratová hodnota

Tabulka, která byla přidána do kolekce tvarů.

### Výjimky

| výjimka | podmínka |
| --- | --- |
| ArgumentException | Vyvoláno, když je některý povinný parametr null nebo prázdný, nebo když je určený list nebo rozsah buněk neplatný. |
| InvalidOperationException | Vyvoláno, když jsou vstupní data v nepodporovaném formátu. |

### Příklady

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Viz také

* rozhraní [ITable](../../../aspose.slides/itable)
* rozhraní [IShapeCollection](../../../aspose.slides/ishapecollection)
* rozhraní [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* třída [ExcelWorkbookImporter](../../excelworkbookimporter)
* jmenný prostor [Aspose.Slides.Import](../../excelworkbookimporter)
* sestavení [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

Načte tabulku ze zadaného souboru Excel sešitu a přidá ji na konec dané kolekce tvarů na zadaných souřadnicích.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | IShapeCollection | Kolekce tvarů, do které bude tabulka přidána. |
| x | Single | Souřadnice X pro umístění tabulky. |
| y | Single | Souřadnice Y pro umístění tabulky. |
| workbookPath | String | Cesta k souboru Excel sešitu. |
| worksheetName | String | Název listu, který tabulku obsahuje. |
| cellRange | String | Rozsah buněk, který tabulku určuje (například "A1:D10"). |

### Návratová hodnota

Tabulka, která byla přidána do kolekce tvarů.

### Výjimky

| výjimka | podmínka |
| --- | --- |
| ArgumentException | Vyvoláno, když je některý povinný parametr null nebo prázdný, nebo když je určený list nebo rozsah buněk neplatný. |
| IOException | Vyvoláno, když dojde k chybě V/V při přístupu k souboru sešitu. |
| InvalidOperationException | Vyvoláno, když jsou vstupní data v nepodporovaném formátu. |

### Příklady

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Viz také

* rozhraní [ITable](../../../aspose.slides/itable)
* rozhraní [IShapeCollection](../../../aspose.slides/ishapecollection)
* třída [ExcelWorkbookImporter](../../excelworkbookimporter)
* jmenný prostor [Aspose.Slides.Import](../../excelworkbookimporter)
* sestavení [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

Načte tabulku ze zadaného souboru Excel sešitu a přidá ji na konec dané kolekce tvarů na zadaných souřadnicích.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | IShapeCollection | Kolekce tvarů, do které bude tabulka přidána. |
| x | Single | Souřadnice X pro umístění tabulky. |
| y | Single | Souřadnice Y pro umístění tabulky. |
| workbookStream | Stream | Datový proud obsahující data sešitu. |
| worksheetName | String | Název listu, který tabulku obsahuje. |
| cellRange | String | Rozsah buněk, který tabulku určuje (například "A1:D10"). |

### Návratová hodnota

Tabulka, která byla přidána do kolekce tvarů.

### Výjimky

| výjimka | podmínka |
| --- | --- |
| ArgumentException | Vyvoláno, když je některý povinný parametr null nebo prázdný, nebo když je určený list nebo rozsah buněk neplatný. |
| InvalidOperationException | Vyvoláno, když jsou vstupní data v nepodporovaném formátu. |

### Příklady

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Viz také

* rozhraní [ITable](../../../aspose.slides/itable)
* rozhraní [IShapeCollection](../../../aspose.slides/ishapecollection)
* třída [ExcelWorkbookImporter](../../excelworkbookimporter)
* jmenný prostor [Aspose.Slides.Import](../../excelworkbookimporter)
* sestavení [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->