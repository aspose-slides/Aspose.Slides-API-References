---
title: ChartSeriesGroup
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Đại diện cho nhóm các chuỗi.
type: docs
weight: 1460
url: /vi/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup lớp

Đại diện cho nhóm các chuỗi.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Đọc/ghi [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 đến 300 phần trăm kích thước mặc định). Đọc/ghi Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Trả về biểu đồ cha. Chỉ đọc [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Xác định kích thước lỗ trong biểu đồ vòng bánh (có thể từ 0 đến 90 phần trăm kích thước vùng vẽ). Đọc/ghi Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Lấy hoặc đặt góc của phần đầu tiên của biểu đồ tròn hoặc vòng bánh, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Đọc/ghi UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Trả về hoặc đặt khoảng cách, tính bằng phần trăm chiều rộng đánh dấu, giữa các chuỗi dữ liệu trong biểu đồ 3D. Đọc/ghi UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Xác định khoảng cách giữa các cụm cột hoặc thanh, tính bằng phần trăm chiều rộng của cột hoặc thanh. Đọc/ghi UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True nếu biểu đồ có đường chuỗi. Áp dụng cho biểu đồ thanh chồng và OfPie. Đọc/ghi Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Xác định định dạng HiLowLines. HiLowLines được áp dụng với các loại biểu đồ HiLowClose, OpenHiLowClose, VolumeHiLowClose và VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Xác định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. Đọc/ghi Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Lấy phần tử tại chỉ mục được chỉ định. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Xác định mức độ chồng chập của các thanh và cột trên biểu đồ 2D, tính bằng phần trăm (từ -100% đến 100%). - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). - 0%: Các thanh được đặt cạnh nhau mà không chồng chập hay khoảng cách. - 100%: Chồng chập tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là Đọc/ghi SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Xác định cách xác định các điểm dữ liệu nào nằm trong phần tròn hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đọc/ghi [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Thông tin chia tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có chia tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong phần tròn hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie. Chỉ đọc [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Xác định một giá trị sẽ được sử dụng để xác định các điểm dữ liệu nằm trong phần tròn hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đọc/ghi Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Chỉ ra nếu chuỗi của nhóm này được vẽ trên trục phụ. Chỉ đọc Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Xác định kích thước của phần tròn hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của phần tròn đầu tiên (có thể từ 5 đến 200 phần trăm). Đọc/ghi UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Trả về một bộ sưu tập các chuỗi. Chỉ đọc [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Trả về kiểu của nhóm chuỗi này. Chỉ đọc [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Cung cấp quyền truy cập vào các thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu. Chỉ đọc [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Ghi chú

1) Xem tóm tắt và ghi chú cho lớp ChartSeriesGroupCollection và enum CombinableSeriesTypesGroup. 2) Nhóm chuỗi chứa một số thuộc tính chuỗi mà chung cho mỗi chuỗi trong nhóm ("thuộc tính nhóm chuỗi"). "Thuộc tính nhóm chuỗi" trong lớp ChartSeriesGroup là Đọc/ghi. Mỗi "thuộc tính nhóm chuỗi" có thể có một phiên bản chỉ đọc trong lớp ChartSeries.

### Xem thêm

* giao diện [IChartSeriesGroup](../ichartseriesgroup)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->