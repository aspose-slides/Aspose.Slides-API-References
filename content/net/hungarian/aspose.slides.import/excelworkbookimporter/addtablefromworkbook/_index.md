---
title: AddTableFromWorkbook
second_title: Aspose.Sildes .NET API referenciája
description: Lekéri a táblázatot a megadott Excel munkafüzetből, és a megadott koordinátákon a megadott alakzatgyűjtemény végére adja hozzá.
type: docs
weight: 20
url: /hu/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

Egy táblázatot kér le a megadott Excel munkafüzetből, és a megadott koordinátákon a megadott alakzatgyűjtemény végére adja hozzá.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | IShapeCollection | Az alakzatgyűjtemény, amelyhez a táblázat hozzá lesz adva. |
| x | Single | Az X koordináta a táblázat elhelyezéséhez. |
| y | Single | Az Y koordináta a táblázat elhelyezéséhez. |
| workbook | IExcelDataWorkbook | Az Excel munkafüzet. |
| worksheetName | String | A munkalap neve, amely a táblázatot tartalmazza. |
| cellRange | String | A cellatartomány, amely meghatározza a táblázatot (például "A1:D10"). |

### Visszatérési érték

A táblázat, amelyet hozzáadtak az alakzatgyűjteményhez.

### Kivételek

| kivétel | feltétel |
| --- | --- |
| ArgumentException | Akkor dobódik, ha bármely kötelező paraméter null vagy üres, vagy ha a megadott munkalap vagy cellatartomány érvénytelen. |
| InvalidOperationException | Akkor dobódik, ha a bemeneti adat nem támogatott formátumú. |

### Példák

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* interfész [ITable](../../../aspose.slides/itable)
* interfész [IShapeCollection](../../../aspose.slides/ishapecollection)
* interfész [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* osztály [ExcelWorkbookImporter](../../excelworkbookimporter)
* névtér [Aspose.Slides.Import](../../excelworkbookimporter)
* összeállítás [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

Egy táblázatot kér le a megadott Excel munkafájlból, és a megadott koordinátákon a megadott alakzatgyűjtemény végére adja hozzá.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | IShapeCollection | Az alakzatgyűjtemény, amelyhez a táblázat hozzá lesz adva. |
| x | Single | Az X koordináta a táblázat elhelyezéséhez. |
| y | Single | Az Y koordináta a táblázat elhelyezéséhez. |
| workbookPath | String | Az Excel munkafájl elérési útja. |
| worksheetName | String | A munkalap neve, amely a táblázatot tartalmazza. |
| cellRange | String | A cellatartomány, amely meghatározza a táblázatot (például "A1:D10"). |

### Visszatérési érték

A táblázat, amelyet hozzáadtak az alakzatgyűjteményhez.

### Kivételek

| kivétel | feltétel |
| --- | --- |
| ArgumentException | Akkor dobódik, ha bármely kötelező paraméter null vagy üres, vagy ha a megadott munkalap vagy cellatartomány érvénytelen. |
| IOException | Akkor dobódik, ha I/O hiba lép fel a munkafüzet fájl elérése közben. |
| InvalidOperationException | Akkor dobódik, ha a bemeneti adat nem támogatott formátumú. |

### Példák

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* interfész [ITable](../../../aspose.slides/itable)
* interfész [IShapeCollection](../../../aspose.slides/ishapecollection)
* osztály [ExcelWorkbookImporter](../../excelworkbookimporter)
* névtér [Aspose.Slides.Import](../../excelworkbookimporter)
* összeállítás [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

Egy táblázatot kér le a megadott Excel munkafájlból, és a megadott koordinátákon a megadott alakzatgyűjtemény végére adja hozzá.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | IShapeCollection | Az alakzatgyűjtemény, amelyhez a táblázat hozzá lesz adva. |
| x | Single | Az X koordináta a táblázat elhelyezéséhez. |
| y | Single | Az Y koordináta a táblázat elhelyezéséhez. |
| workbookStream | Stream | Egy adatfolyam, amely a munkafüzet adatát tartalmazza. |
| worksheetName | String | A munkalap neve, amely a táblázatot tartalmazza. |
| cellRange | String | A cellatartomány, amely meghatározza a táblázatot (például "A1:D10"). |

### Visszatérési érték

A táblázat, amelyet hozzáadtak az alakzatgyűjteményhez.

### Kivételek

| kivétel | feltétel |
| --- | --- |
| ArgumentException | Akkor dobódik, ha bármely kötelező paraméter null vagy üres, vagy ha a megadott munkalap vagy cellatartomány érvénytelen. |
| InvalidOperationException | Akkor dobódik, ha a bemeneti adat nem támogatott formátumú. |

### Példák

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* interfész [ITable](../../../aspose.slides/itable)
* interfész [IShapeCollection](../../../aspose.slides/ishapecollection)
* osztály [ExcelWorkbookImporter](../../excelworkbookimporter)
* névtér [Aspose.Slides.Import](../../excelworkbookimporter)
* összeállítás [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->