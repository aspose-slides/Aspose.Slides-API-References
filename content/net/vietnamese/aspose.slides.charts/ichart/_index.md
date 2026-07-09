---
title: IChart
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn một biểu đồ đồ họa trên một slide.
type: docs
weight: 1740
url: /vi/aspose.slides.charts/ichart/
---
## IChart giao diện

Biểu diễn một biểu đồ đồ họa trên một slide.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Cho phép lấy giao diện cơ sở IFormattedTextContainer. Chỉ đọc [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Cho phép lấy giao diện cơ sở IGraphicalObject. Chỉ đọc [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Trả về giao diện IOverrideThemeable. Chỉ đọc [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Cung cấp truy cập đến các trục biểu đồ. Chỉ đọc [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Trả về một đối tượng cho phép thay đổi định dạng của tường phía sau của biểu đồ 3D. Chỉ đọc [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Trả về thông tin về dữ liệu được liên kết hoặc nhúng liên quan đến biểu đồ. Chỉ đọc [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Trả về bảng dữ liệu của một biểu đồ. Chỉ đọc [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Trả về hoặc đặt tiêu đề biểu đồ. Chỉ đọc [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Trả về hoặc đặt cách vẽ các ô trống trên biểu đồ. Đọc/ghi [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Trả về một đối tượng cho phép thay đổi định dạng của sàn của biểu đồ 3D. Chỉ đọc [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Xác định liệu biểu đồ có bảng dữ liệu hay không. Đọc/ghi Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Xác định liệu biểu đồ có chú thích hay không. Đọc/ghi Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Xác định khu vực biểu đồ sẽ có các góc tròn. Đọc/ghi Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Xác định liệu biểu đồ có tiêu đề hiển thị hay không. Đọc/ghi Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Trả về hoặc đặt chú thích cho một biểu đồ. Chỉ đọc [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Biểu diễn khu vực vẽ của một biểu đồ. Chỉ đọc [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Xác định liệu chỉ các ô hiển thị được vẽ. Đặt false để vẽ cả ô hiển thị và ẩn. Đọc/ghi Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Trả về quay 3D của một biểu đồ. Chỉ đọc [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Xác định nhãn dữ liệu trên giá trị tối đa của biểu đồ sẽ được hiển thị. Đọc/ghi Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Trả về một đối tượng cho phép thay đổi định dạng của tường bên của biểu đồ 3D. Chỉ đọc [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Trả về hoặc đặt kiểu biểu đồ. Đọc/ghi [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Trả về hoặc đặt loại biểu đồ. Đọc/ghi [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Xác định các hình dạng được vẽ trên biểu đồ. Chỉ đọc [`IGroupShape`](../../aspose.slides/igroupshape). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Tính toán các giá trị thực tế của các phần tử biểu đồ. Các giá trị thực bao gồm vị trí của các phần tử thực thi giao diện IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) và các giá trị trục thực tế (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Xem thêm

* giao diện [IFormattedTextContainer](../iformattedtextcontainer)
* giao diện [IGraphicalObject](../../aspose.slides/igraphicalobject)
* giao diện [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->