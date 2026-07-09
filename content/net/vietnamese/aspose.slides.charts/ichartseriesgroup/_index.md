---
title: IChartSeriesGroup
second_title: Aspose.Sildes cho .NET Tham chiếu API
description: Đại diện cho nhóm các chuỗi.
type: docs
weight: 1950
url: /vi/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup giao diện

Represents group of series.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Cho phép lấy giao diện IChartComponent cơ bản. Chỉ đọc [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Đọc/ghi [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể nằm trong khoảng từ 0 đến 300 phần trăm của kích thước mặc định). Đọc/ghi Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Xác định kích thước lỗ trong biểu đồ bánh rỗng (có thể nằm trong khoảng từ 10 đến 90 phần trăm của kích thước khu vực vẽ). Đọc/ghi Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Lấy hoặc đặt góc của phần bánh đầu tiên trong biểu đồ bánh hoặc bánh rỗng, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Đọc/ghi UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Lấy hoặc đặt khoảng cách, tính bằng phần trăm độ rộng đánh dấu, giữa các chuỗi dữ liệu trong biểu đồ 3D. Đọc/ghi UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Xác định khoảng cách giữa các cụm cột hoặc thanh, tính bằng phần trăm độ rộng của cột hoặc thanh. Đọc/ghi UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Đúng nếu biểu đồ có các đường chuỗi. Áp dụng cho biểu đồ cột xếp chồng và OfPie. Đọc/ghi Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Xác định định dạng HiLowLines. HiLowLines được áp dụng với các loại biểu đồ HiLowClose, OpenHiLowClose, VolumeHiLowClose và VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Xác định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. Đọc/ghi Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Lấy phần tử tại chỉ mục được chỉ định. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% đến 100%). - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). - 0%: Các thanh được đặt cạnh nhau mà không chồng lấn hoặc cách. - 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là Đọc/ghi SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Xác định cách xác định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đọc/ghi [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Thông tin chia tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có chia tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie. Chỉ đọc [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Xác định một giá trị sẽ được sử dụng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đọc/ghi Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Cho biết liệu các chuỗi của nhóm này có được vẽ trên trục phụ hay không. Chỉ đọc Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính theo phần trăm kích thước của bánh đầu tiên (có thể nằm trong khoảng từ 5 đến 200 phần trăm). Đọc/ghi UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Trả về một bộ sưu tập chỉ đọc của các chuỗi biểu đồ. Chỉ đọc [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Trả về kiểu của nhóm chuỗi này. Chỉ đọc [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Cung cấp truy cập tới các thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu. Chỉ đọc [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Ghi chú

1) Xem phần tóm tắt và ghi chú cho lớp ChartSeriesGroupCollection và enum CombinableSeriesTypesGroup. 2) Nhóm chuỗi chứa một số thuộc tính chuỗi mà là chung cho mỗi chuỗi trong nhóm ("series group properties"). "Series group properties" trong lớp ChartSeriesGroup là Đọc/ghi. Mỗi "series group properties" có thể có một chiếu hướng chỉ đọc trong lớp ChartSeries.

### Xem thêm

* giao diện [IChartComponent](../ichartcomponent)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->