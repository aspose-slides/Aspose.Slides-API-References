---
title: AddTableFromWorkbook
second_title: Aspose.Sildes for .NET API Reference
description: Retrieves a table from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.
type: docs
weight: 20
url: /aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---

## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

Retrieves a table from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | The shape collection to which the table will be added. |
| x | Single | The X coordinate for positioning the table. |
| y | Single | The Y coordinate for positioning the table. |
| workbook | IExcelDataWorkbook | The Excel workbook. |
| worksheetName | String | The name of the worksheet that contains the table. |
| cellRange | String | The cell range that defines the table (for example, "A1:D10"). |

### Return Value

The table that was added to the shape collection.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when any required parameter is null or empty, or when the specified worksheet or cell range is invalid. |
| InvalidOperationException | Thrown when the input data is in an unsupported format. |

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

* interface [ITable](../../../aspose.slides/itable)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

Retrieves a table from the specified Excel workbook file and adds it to the end of the given shape collection at the specified coordinates.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | The shape collection to which the table will be added. |
| x | Single | The X coordinate for positioning the table. |
| y | Single | The Y coordinate for positioning the table. |
| workbookPath | String | The path to the Excel workbook file. |
| worksheetName | String | The name of the worksheet that contains the table. |
| cellRange | String | The cell range that defines the table (for example, "A1:D10"). |

### Return Value

The table that was added to the shape collection.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when any required parameter is null or empty, or when the specified worksheet or cell range is invalid. |
| IOException | Thrown when an I/O error occurs while accessing the workbook file. |
| InvalidOperationException | Thrown when the input data is in an unsupported format. |

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

* interface [ITable](../../../aspose.slides/itable)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

Retrieves a table from the specified Excel workbook file and adds it to the end of the given shape collection at the specified coordinates.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | The shape collection to which the table will be added. |
| x | Single | The X coordinate for positioning the table. |
| y | Single | The Y coordinate for positioning the table. |
| workbookStream | Stream | A stream containing the workbook data. |
| worksheetName | String | The name of the worksheet that contains the table. |
| cellRange | String | The cell range that defines the table (for example, "A1:D10"). |

### Return Value

The table that was added to the shape collection.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when any required parameter is null or empty, or when the specified worksheet or cell range is invalid. |
| InvalidOperationException | Thrown when the input data is in an unsupported format. |

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

* interface [ITable](../../../aspose.slides/itable)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
