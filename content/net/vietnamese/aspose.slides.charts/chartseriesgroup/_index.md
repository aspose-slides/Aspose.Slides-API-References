---
title: ChartSeriesGroup
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Đại diện cho nhóm các chuỗi.
type: docs
weight: 1470
url: /vi/aspose.slides.charts/chartseriesgroup/
---
## lớp ChartSeriesGroup

Đại diện cho nhóm các chuỗi.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Xác định cách các giá trị kích thước bong bóng được biểu thị trên biểu đồ bong bóng. Đọc/ghi [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể nằm trong khoảng từ 0 đến 300 phần trăm kích thước mặc định). Đọc/ghi Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Trả về biểu đồ cha. Chỉ đọc [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Xác định kích thước lỗ trong biểu đồ bánh rán (có thể nằm trong khoảng từ 0 đến 90 phần trăm kích thước vùng vẽ). Đọc/ghi Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Lấy hoặc đặt góc của lát bánh tròn hoặc bánh rán đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Đọc/ghi UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Lấy hoặc đặt khoảng cách giữa các chuỗi dữ liệu trong biểu đồ 3D, tính bằng phần trăm chiều rộng dấu hiệu. Giá trị phải nằm trong khoảng từ 0 đến 500. Đọc/ghi UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Lấy hoặc đặt khoảng cách giữa các cụm cột hoặc thanh, tính bằng phần trăm chiều rộng cột hoặc thanh. Giá trị phải nằm trong khoảng từ 0 đến 500. Đọc/ghi UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Đúng nếu biểu đồ có các đường chuỗi. Áp dụng cho biểu đồ cột chồng và OfPie. Đọc/ghi Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Xác định định dạng HiLowLines. HiLowLines được áp dụng với các loại biểu đồ HiLowClose, OpenHiLowClose, VolumeHiLowClose và VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Xác định mỗi dấu dữ liệu trong chuỗi có màu khác nhau. Đọc/ghi Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Lấy phần tử tại chỉ mục được chỉ định. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2D, tính bằng phần trăm (từ -100% đến 100%). - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). - 0%: Các thanh được đặt cạnh nhau mà không chồng lấn hay khoảng cách. - 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là Đọc/ghi SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Xác định cách xác định các điểm dữ liệu nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đọc/ghi [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Thông tin chia tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có chia tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie. Chỉ đọc [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Xác định một giá trị sẽ được sử dụng để xác định các điểm dữ liệu nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đọc/ghi Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Cho biết liệu chuỗi của nhóm này có được vẽ trên trục phụ hay không. Chỉ đọc Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của bánh thứ nhất (có thể nằm trong khoảng từ 5 đến 200 phần trăm). Đọc/ghi UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Trả về một tập hợp các chuỗi. Chỉ đọc [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Trả về kiểu của nhóm chuỗi này. Chỉ đọc [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Cung cấp quyền truy cập vào thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu. Chỉ đọc [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Ghi chú

1) Xem tóm tắt và ghi chú cho lớp ChartSeriesGroupCollection và enum CombinableSeriesTypesGroup. 2) Nhóm các chuỗi chứa một số thuộc tính chuỗi mà chung cho mỗi chuỗi trong nhóm ("thuộc tính nhóm chuỗi"). "Thuộc tính nhóm chuỗi" trong lớp ChartSeriesGroup là Đọc/ghi. Mỗi "thuộc tính nhóm chuỗi" có thể có một phiên bản chỉ đọc trong lớp ChartSeries.

### Xem thêm

* giao diện [IChartSeriesGroup](../ichartseriesgroup)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->