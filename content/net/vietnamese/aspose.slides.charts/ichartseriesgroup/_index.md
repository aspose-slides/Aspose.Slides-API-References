---
title: IChartSeriesGroup
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn nhóm các chuỗi.
type: docs
weight: 1950
url: /vi/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup giao diện

Biểu diễn nhóm các chuỗi.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Cho phép lấy giao diện IChartComponent cơ bản. Chỉ đọc [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Xác định cách các giá trị kích thước bong bóng được biểu thị trên biểu đồ bong bóng. Đọc/ghi [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể nằm trong khoảng từ 0 đến 300% kích thước mặc định). Đọc/ghi Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Xác định kích thước của lỗ trong biểu đồ bánh ròng (có thể nằm trong khoảng từ 10 đến 90% kích thước vùng vẽ). Đọc/ghi Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Lấy hoặc đặt góc của lát bánh hoặc bánh ròng đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ vị trí trên, từ 0 đến 360 độ). Đọc/ghi UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Trả về hoặc đặt khoảng cách, tính bằng phần trăm độ rộng đánh dấu, giữa các chuỗi dữ liệu trong biểu đồ 3D. Đọc/ghi UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Xác định khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm độ rộng thanh hoặc cột. Đọc/ghi UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Đúng nếu biểu đồ có các đường chuỗi. Áp dụng cho biểu đồ thanh xếp chồng và OfPie. Đọc/ghi Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Xác định định dạng HiLowLines. HiLowLines được áp dụng với các loại biểu đồ HiLowClose, OpenHiLowClose, VolumeHiLowClose và VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Xác định rằng mỗi đánh dấu dữ liệu trong chuỗi có màu khác nhau. Đọc/ghi Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Lấy phần tử tại chỉ mục đã chỉ định. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Xác định mức độ chồng lấn của thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% đến 100%). - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). - 0%: Các thanh đặt cạnh nhau mà không chồng lấn hay khoảng cách. - 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là Đọc/ghi SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Xác định cách xác định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đọc/ghi [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Thông tin phân tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có phân tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Chỉ đọc [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Xác định một giá trị sẽ được sử dụng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đọc/ghi Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Cho biết nếu các chuỗi của nhóm này được vẽ trên trục phụ. Chỉ đọc Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của bánh đầu tiên (có thể nằm trong khoảng từ 5 đến 200%). Đọc/ghi UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Trả về một bộ sưu tập chỉ đọc của các chuỗi biểu đồ. Chỉ đọc [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Trả về kiểu của nhóm chuỗi này. Chỉ đọc [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Cung cấp quyền truy cập vào các thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu. Chỉ đọc [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Ghi chú

1) Xem tóm tắt và ghi chú cho lớp ChartSeriesGroupCollection và enum CombinableSeriesTypesGroup. 2) Nhóm các chuỗi chứa một số thuộc tính chung cho mỗi chuỗi trong nhóm ("thuộc tính nhóm chuỗi"). "Thuộc tính nhóm chuỗi" trong lớp ChartSeriesGroup là Đọc/ghi. Mỗi "thuộc tính nhóm chuỗi" có thể có một phiên bản chỉ đọc trong lớp ChartSeries.

### Xem thêm

* giao diện [IChartComponent](../ichartcomponent)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->