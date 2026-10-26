---
title: AddTableFromWorkbook
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Pobiera tabelę z określonego skoroszytu Excela i dodaje ją na koniec podanej kolekcji kształtów w podanych współrzędnych.
type: docs
weight: 20
url: /pl/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

Pobiera tabelę z określonego skoroszytu Excela i dodaje ją na koniec podanej kolekcji kształtów w podanych współrzędnych.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | IShapeCollection | Kolekcja kształtów, do której tabela zostanie dodana. |
| x | Single | Współrzędna X określająca położenie tabeli. |
| y | Single | Współrzędna Y określająca położenie tabeli. |
| workbook | IExcelDataWorkbook | Skoroszyt Excela. |
| worksheetName | String | Nazwa arkusza zawierającego tabelę. |
| cellRange | String | Zakres komórek definiujący tabelę (na przykład "A1:D10"). |

### Wartość zwracana

Tabela, która została dodana do kolekcji kształtów.

### Wyjątki

| Wyjątek | Warunek |
| --- | --- |
| ArgumentException | Rzucany, gdy którykolwiek wymagany parametr jest null lub pusty, lub gdy określony arkusz lub zakres komórek jest nieprawidłowy. |
| InvalidOperationException | Rzucany, gdy dane wejściowe są w nieobsługiwanym formacie. |

### Przykłady

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Zobacz także

* interfejs [ITable](../../../aspose.slides/itable)
* interfejs [IShapeCollection](../../../aspose.slides/ishapecollection)
* interfejs [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* klasa [ExcelWorkbookImporter](../../excelworkbookimporter)
* przestrzeń nazw [Aspose.Slides.Import](../../excelworkbookimporter)
* zestaw [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

Pobiera tabelę z określonego pliku skoroszytu Excela i dodaje ją na koniec podanej kolekcji kształtów w podanych współrzędnych.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | IShapeCollection | Kolekcja kształtów, do której tabela zostanie dodana. |
| x | Single | Współrzędna X określająca położenie tabeli. |
| y | Single | Współrzędna Y określająca położenie tabeli. |
| workbookPath | String | Ścieżka do pliku skoroszytu Excela. |
| worksheetName | String | Nazwa arkusza zawierającego tabelę. |
| cellRange | String | Zakres komórek definiujący tabelę (na przykład "A1:D10"). |

### Wartość zwracana

Tabela, która została dodana do kolekcji kształtów.

### Wyjątki

| Wyjątek | Warunek |
| --- | --- |
| ArgumentException | Rzucany, gdy którykolwiek wymagany parametr jest null lub pusty, lub gdy określony arkusz lub zakres komórek jest nieprawidłowy. |
| IOException | Rzucany, gdy wystąpi błąd I/O podczas dostępu do pliku skoroszytu. |
| InvalidOperationException | Rzucany, gdy dane wejściowe są w nieobsługiwanym formacie. |

### Przykłady

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Zobacz także

* interfejs [ITable](../../../aspose.slides/itable)
* interfejs [IShapeCollection](../../../aspose.slides/ishapecollection)
* klasa [ExcelWorkbookImporter](../../excelworkbookimporter)
* przestrzeń nazw [Aspose.Slides.Import](../../excelworkbookimporter)
* zestaw [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

Pobiera tabelę z określonego pliku skoroszytu Excela i dodaje ją na koniec podanej kolekcji kształtów w podanych współrzędnych.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | IShapeCollection | Kolekcja kształtów, do której tabela zostanie dodana. |
| x | Single | Współrzędna X określająca położenie tabeli. |
| y | Single | Współrzędna Y określająca położenie tabeli. |
| workbookStream | Stream | Strumień zawierający dane skoroszytu. |
| worksheetName | String | Nazwa arkusza zawierającego tabelę. |
| cellRange | String | Zakres komórek definiujący tabelę (na przykład "A1:D10"). |

### Wartość zwracana

Tabela, która została dodana do kolekcji kształtów.

### Wyjątki

| Wyjątek | Warunek |
| --- | --- |
| ArgumentException | Rzucany, gdy którykolwiek wymagany parametr jest null lub pusty, lub gdy określony arkusz lub zakres komórek jest nieprawidłowy. |
| InvalidOperationException | Rzucany, gdy dane wejściowe są w nieobsługiwanym formacie. |

### Przykłady

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Zobacz także

* interfejs [ITable](../../../aspose.slides/itable)
* interfejs [IShapeCollection](../../../aspose.slides/ishapecollection)
* klasa [ExcelWorkbookImporter](../../excelworkbookimporter)
* przestrzeń nazw [Aspose.Slides.Import](../../excelworkbookimporter)
* zestaw [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->