---
title: AddChartFromWorkbook
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Lấy một biểu đồ từ sổ làm việc Excel đã chỉ định và thêm nó vào cuối bộ sưu tập hình dạng đã cho tại các tọa độ được chỉ định.
type: docs
weight: 10
url: /vi/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

Lấy biểu đồ từ sổ làm việc Excel đã chỉ định và thêm nó vào cuối bộ sưu tập hình dạng đã cho tại các tọa độ được chỉ định.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapes | IShapeCollection | Bộ sưu tập hình dạng mà biểu đồ sẽ được thêm vào. |
| x | Single | Tọa độ X để định vị biểu đồ. |
| y | Single | Tọa độ Y để định vị biểu đồ. |
| workbook | IExcelDataWorkbook | Sổ làm việc Excel. |
| worksheetName | String | Tên của bảng tính chứa biểu đồ. |
| chartIndex | Int32 | Chỉ mục dựa trên số 0 của hình dạng biểu đồ cần chèn. Chỉ mục này có thể được lấy bằng phương thức [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet). |
| embedAllWorkbook | Boolean | Nếu `true`, toàn bộ sổ làm việc sẽ được nhúng vào biểu đồ; nếu `false`, chỉ dữ liệu biểu đồ sẽ được nhúng. |

### Giá trị trả về

Biểu đồ đã được thêm vào bộ sưu tập hình dạng.

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| ArgumentException | Được ném khi bất kỳ tham số bắt buộc nào là null, rỗng, hoặc nếu không thể tìm thấy biểu đồ trong sổ làm việc. |

### Ví dụ

Ví dụ:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Xem thêm

* giao diện [IChart](../../../aspose.slides.charts/ichart)
* giao diện [IShapeCollection](../../../aspose.slides/ishapecollection)
* giao diện [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* lớp [ExcelWorkbookImporter](../../excelworkbookimporter)
* không gian tên [Aspose.Slides.Import](../../excelworkbookimporter)
* tập hợp [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

Lấy biểu đồ từ sổ làm việc Excel đã chỉ định và thêm nó vào cuối bộ sưu tập hình dạng đã cho tại các tọa độ được chỉ định.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapes | IShapeCollection | Bộ sưu tập hình dạng mà biểu đồ sẽ được thêm vào. |
| x | Single | Tọa độ X để định vị biểu đồ. |
| y | Single | Tọa độ Y để định vị biểu đồ. |
| workbook | IExcelDataWorkbook | Sổ làm việc Excel. |
| worksheetName | String | Tên của bảng tính chứa biểu đồ. |
| chartName | String | Tên của biểu đồ sẽ được thêm. |
| embedAllWorkbook | Boolean | Nếu `true`, toàn bộ sổ làm việc sẽ được nhúng vào biểu đồ; nếu `false`, chỉ dữ liệu biểu đồ sẽ được nhúng. |

### Giá trị trả về

Biểu đồ đã được thêm vào bộ sưu tập hình dạng.

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| ArgumentException | Được ném khi bất kỳ tham số bắt buộc nào là null, rỗng, hoặc nếu không thể tìm thấy biểu đồ trong sổ làm việc. |

### Ví dụ

Ví dụ:

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

### Xem thêm

* giao diện [IChart](../../../aspose.slides.charts/ichart)
* giao diện [IShapeCollection](../../../aspose.slides/ishapecollection)
* giao diện [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* lớp [ExcelWorkbookImporter](../../excelworkbookimporter)
* không gian tên [Aspose.Slides.Import](../../excelworkbookimporter)
* tập hợp [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

Lấy biểu đồ từ sổ làm việc Excel đã chỉ định và thêm nó vào cuối bộ sưu tập hình dạng đã cho tại các tọa độ được chỉ định.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapes | IShapeCollection | Bộ sưu tập hình dạng mà biểu đồ sẽ được thêm vào. |
| x | Single | Tọa độ X để định vị biểu đồ. |
| y | Single | Tọa độ Y để định vị biểu đồ. |
| workbookStream | Stream | Luồng chứa dữ liệu sổ làm việc. |
| worksheetName | String | Tên của bảng tính chứa biểu đồ. |
| chartName | String | Tên của biểu đồ sẽ được thêm. |
| embedAllWorkbook | Boolean | Nếu `true`, toàn bộ sổ làm việc sẽ được nhúng vào biểu đồ; nếu `false`, chỉ dữ liệu biểu đồ sẽ được nhúng. |

### Giá trị trả về

Biểu đồ đã được thêm vào bộ sưu tập hình dạng.

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| ArgumentException | Được ném khi bất kỳ tham số bắt buộc nào là null, rỗng, hoặc nếu không thể tìm thấy biểu đồ trong sổ làm việc. |
| InvalidOperationException | Được ném khi dữ liệu đầu vào ở định dạng không được hỗ trợ. |

### Ví dụ

Ví dụ:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Xem thêm

* giao diện [IChart](../../../aspose.slides.charts/ichart)
* giao diện [IShapeCollection](../../../aspose.slides/ishapecollection)
* lớp [ExcelWorkbookImporter](../../excelworkbookimporter)
* không gian tên [Aspose.Slides.Import](../../excelworkbookimporter)
* tập hợp [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

Lấy biểu đồ từ sổ làm việc Excel đã chỉ định và thêm nó vào cuối bộ sưu tập hình dạng đã cho tại các tọa độ được chỉ định.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapes | IShapeCollection | Bộ sưu tập hình dạng mà biểu đồ sẽ được thêm vào. |
| x | Single | Tọa độ X để định vị biểu đồ. |
| y | Single | Tọa độ Y để định vị biểu đồ. |
| workbookPath | String | Đường dẫn tệp tới sổ làm việc chứa biểu đồ. |
| worksheetName | String | Tên của bảng tính chứa biểu đồ. |
| chartName | String | Tên của biểu đồ sẽ được thêm. |
| embedWorkbook | Boolean | Nếu `true`, sổ làm việc sẽ được nhúng vào biểu đồ; nếu `false`, biểu đồ sẽ liên kết tới sổ làm việc bên ngoài. |

### Giá trị trả về

Biểu đồ đã được thêm vào bộ sưu tập hình dạng.

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| ArgumentException | Được ném khi bất kỳ tham số bắt buộc nào là null, rỗng, hoặc nếu không thể tìm thấy biểu đồ trong sổ làm việc. |
| IOException | Được ném khi xảy ra lỗi I/O trong quá trình truy cập tệp. |
| InvalidOperationException | Được ném khi dữ liệu đầu vào ở định dạng không được hỗ trợ. |

### Ví dụ

Ví dụ:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Xem thêm

* giao diện [IChart](../../../aspose.slides.charts/ichart)
* giao diện [IShapeCollection](../../../aspose.slides/ishapecollection)
* lớp [ExcelWorkbookImporter](../../excelworkbookimporter)
* không gian tên [Aspose.Slides.Import](../../excelworkbookimporter)
* tập hợp [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->