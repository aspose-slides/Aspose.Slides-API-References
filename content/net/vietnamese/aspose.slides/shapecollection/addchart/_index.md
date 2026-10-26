---
title: AddChart
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và thêm nó vào cuối bộ sưu tập shape.
type: docs
weight: 100
url: /vi/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và thêm nó vào cuối bộ sưu tập shape.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | ChartType | Loại biểu đồ cần thêm. |
| x | Single | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | Single | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | Single | Chiều rộng của biểu đồ, tính bằng điểm. |
| height | Single | Chiều cao của biểu đồ, tính bằng điểm. |

### Giá trị trả về

[`IChart`](../../../aspose.slides.charts/ichart) mới được tạo.

### Ví dụ

Ví dụ dưới đây cho thấy cách tạo Chart trong PowerPoint Presentation.

```csharp
[C#]
// Khởi tạo lớp Presentation đại diện cho tệp PPTX
using(Presentation pres = new Presentation()) {
  // Truy cập slide đầu tiên
  ISlide sld = pres.Slides[0];
  // Thêm một biểu đồ với dữ liệu mặc định
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Thiết lập tiêu đề biểu đồ
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // Thiết lập series đầu tiên hiển thị giá trị
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Thiết lập chỉ mục cho trang tính dữ liệu biểu đồ
  int defaultWorksheetIndex = 0;
  // Lấy worksheet dữ liệu biểu đồ
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Xóa các series và danh mục được tạo mặc định
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Thêm series mới
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // Thêm danh mục mới
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // Lấy series biểu đồ đầu tiên
  IChartSeries series = chart.ChartData.Series[0];
  // Đổ dữ liệu vào series
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Thiết lập màu nền cho series
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // Lấy series biểu đồ thứ hai
  series = chart.ChartData.Series[1];
  // Đổ dữ liệu vào series
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Thiết lập màu nền cho series
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // Thiết lập nhãn đầu tiên hiển thị tên Danh mục
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // Thiết lập series hiển thị giá trị cho nhãn thứ ba
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // Lưu tệp PPTX xuống đĩa
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### Xem thêm

* giao diện [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* lớp [ShapeCollection](../../shapecollection)
* không gian tên [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và thêm nó vào cuối bộ sưu tập shape.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | ChartType | Loại biểu đồ cần thêm. |
| x | Single | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | Single | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | Single | Chiều rộng của biểu đồ, tính bằng điểm. |
| height | Single | Chiều cao của biểu đồ, tính bằng điểm. |
| initWithSample | Boolean | True để khởi tạo biểu đồ mới với dữ liệu và cài đặt mẫu; false để tạo biểu đồ không có series và chỉ có các cài đặt tối thiểu, giúp việc tạo nhanh hơn. |

### Giá trị trả về

[`IChart`](../../../aspose.slides.charts/ichart) mới được tạo.

### Xem thêm

* giao diện [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* lớp [ShapeCollection](../../shapecollection)
* không gian tên [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->