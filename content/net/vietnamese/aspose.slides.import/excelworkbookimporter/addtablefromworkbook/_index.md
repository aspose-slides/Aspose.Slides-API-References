---
title: AddTableFromWorkbook
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Truy xuất một bảng từ sổ làm việc Excel đã chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại các tọa độ được chỉ định.
type: docs
weight: 20
url: /vi/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

Truy xuất một bảng từ sổ làm việc Excel đã chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại các tọa độ được chỉ định.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapes | IShapeCollection | Bộ sưu tập hình mà bảng sẽ được thêm vào. |
| x | Single | Tọa độ X để định vị bảng. |
| y | Single | Tọa độ Y để định vị bảng. |
| workbook | IExcelDataWorkbook | Sổ làm việc Excel. |
| worksheetName | String | Tên của bảng tính chứa bảng. |
| cellRange | String | Phạm vi ô định nghĩa bảng (ví dụ, "A1:D10"). |

### Giá trị trả về

Bảng đã được thêm vào bộ sưu tập hình.

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| ArgumentException | Bị ném khi bất kỳ tham số bắt buộc nào là null hoặc trống, hoặc khi bảng tính hoặc phạm vi ô được chỉ định không hợp lệ. |
| InvalidOperationException | Bị ném khi dữ liệu đầu vào ở định dạng không được hỗ trợ. |

### Ví dụ

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Xem thêm

* giao diện [ITable](../../../aspose.slides/itable)
* giao diện [IShapeCollection](../../../aspose.slides/ishapecollection)
* giao diện [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* lớp [ExcelWorkbookImporter](../../excelworkbookimporter)
* không gian tên [Aspose.Slides.Import](../../excelworkbookimporter)
* tập hợp [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

Truy xuất một bảng từ tệp sổ làm việc Excel đã chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại các tọa độ được chỉ định.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapes | IShapeCollection | Bộ sưu tập hình mà bảng sẽ được thêm vào. |
| x | Single | Tọa độ X để định vị bảng. |
| y | Single | Tọa độ Y để định vị bảng. |
| workbookPath | String | Đường dẫn tới tệp sổ làm việc Excel. |
| worksheetName | String | Tên của bảng tính chứa bảng. |
| cellRange | String | Phạm vi ô định nghĩa bảng (ví dụ, "A1:D10"). |

### Giá trị trả về

Bảng đã được thêm vào bộ sưu tập hình.

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| ArgumentException | Bị ném khi bất kỳ tham số bắt buộc nào là null hoặc trống, hoặc khi bảng tính hoặc phạm vi ô được chỉ định không hợp lệ. |
| IOException | Bị ném khi xảy ra lỗi I/O trong khi truy cập tệp sổ làm việc. |
| InvalidOperationException | Bị ném khi dữ liệu đầu vào ở định dạng không được hỗ trợ. |

### Ví dụ

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Xem thêm

* giao diện [ITable](../../../aspose.slides/itable)
* giao diện [IShapeCollection](../../../aspose.slides/ishapecollection)
* lớp [ExcelWorkbookImporter](../../excelworkbookimporter)
* không gian tên [Aspose.Slides.Import](../../excelworkbookimporter)
* tập hợp [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

Truy xuất một bảng từ tệp sổ làm việc Excel đã chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại các tọa độ được chỉ định.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapes | IShapeCollection | Bộ sưu tập hình mà bảng sẽ được thêm vào. |
| x | Single | Tọa độ X để định vị bảng. |
| y | Single | Tọa độ Y để định vị bảng. |
| workbookStream | Stream | Luồng chứa dữ liệu sổ làm việc. |
| worksheetName | String | Tên của bảng tính chứa bảng. |
| cellRange | String | Phạm vi ô định nghĩa bảng (ví dụ, "A1:D10"). |

### Giá trị trả về

Bảng đã được thêm vào bộ sưu tập hình.

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| ArgumentException | Bị ném khi bất kỳ tham số bắt buộc nào là null hoặc trống, hoặc khi bảng tính hoặc phạm vi ô được chỉ định không hợp lệ. |
| InvalidOperationException | Bị ném khi dữ liệu đầu vào ở định dạng không được hỗ trợ. |

### Ví dụ

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Xem thêm

* giao diện [ITable](../../../aspose.slides/itable)
* giao diện [IShapeCollection](../../../aspose.slides/ishapecollection)
* lớp [ExcelWorkbookImporter](../../excelworkbookimporter)
* không gian tên [Aspose.Slides.Import](../../excelworkbookimporter)
* tập hợp [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->