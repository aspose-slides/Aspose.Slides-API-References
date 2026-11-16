---
title: IChartSeriesGroup
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu thị nhóm các dãy.
type: docs
weight: 1970
url: /vi/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup giao diện

Biểu thị nhóm các dãy.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Cho phép lấy giao diện IChartComponent cơ bản. Chỉ đọc [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Đọc/ghi [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 đến 300 phần trăm kích thước mặc định). Đọc/ghi Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Xác định kích thước lỗ trong biểu đồ donut (có thể từ 10 đến 90 phần trăm kích thước vùng vẽ). Đọc/ghi Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Lấy hoặc đặt góc của lát bánh pie hoặc donut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Đọc/ghi UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Lấy hoặc đặt khoảng cách giữa các dãy dữ liệu trong biểu đồ 3D, tính bằng phần trăm độ rộng của dấu hiệu. Giá trị phải nằm trong khoảng từ 0 đến 500. Đọc/ghi UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Lấy hoặc đặt khoảng cách giữa các cụm cột hoặc thanh, tính bằng phần trăm độ rộng của cột hoặc thanh. Giá trị phải nằm trong khoảng từ 0 đến 500. Đọc/ghi UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Đúng nếu biểu đồ có các đường dãy. Áp dụng cho biểu đồ thanh chồng và OfPie. Đọc/ghi Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Xác định định dạng HiLowLines. HiLowLines được áp dụng với các loại biểu đồ HiLowClose, OpenHiLowClose, VolumeHiLowClose và VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Xác định rằng mỗi dấu dữ liệu trong dãy có màu khác nhau. Đọc/ghi Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Lấy phần tử tại chỉ mục được chỉ định. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2D, tính bằng phần trăm (từ -100% đến 100%). - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). - 0%: Các thanh được đặt cạnh nhau mà không chồng lấn hay khoảng cách. - 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là Đọc/ghi SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Xác định cách xác định các điểm dữ liệu nào nằm trong bánh pie hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đọc/ghi [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Thông tin chia tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có chia tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh pie hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie. Chỉ đọc [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Xác định một giá trị sẽ được dùng để xác định các điểm dữ liệu nào nằm trong bánh pie hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đọc/ghi Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Cho biết liệu dãy của nhóm này có được vẽ trên trục phụ không. Chỉ đọc Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Xác định kích thước của bánh pie hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của bánh pie đầu tiên (có thể từ 5 đến 200 phần trăm). Đọc/ghi UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Trả về một bộ sưu tập chỉ đọc của các dãy biểu đồ. Chỉ đọc [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Trả về kiểu của nhóm dãy này. Chỉ đọc [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Cung cấp quyền truy cập vào các thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu. Chỉ đọc [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Ghi chú

1) Xem tóm tắt và ghi chú cho lớp ChartSeriesGroupCollection và enum CombinableSeriesTypesGroup. 2) Nhóm các dãy chứa một số thuộc tính dãy mà chung cho mỗi dãy trong nhóm ("thuộc tính nhóm dãy"). "Thuộc tính nhóm dãy" trong lớp ChartSeriesGroup là Đọc/ghi. Mỗi "thuộc tính nhóm dãy" có thể có một phiên bản chỉ đọc trong lớp ChartSeries.

### Xem thêm

* giao diện [IChartComponent](../ichartcomponent)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->