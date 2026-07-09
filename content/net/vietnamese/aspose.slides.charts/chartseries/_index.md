---
title: ChartSeries
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn một chuỗi biểu đồ.
type: docs
weight: 1440
url: /vi/aspose.slides.charts/chartseries/
---
## ChartSeries lớp

Biểu diễn một chuỗi biểu đồ.

```csharp
public class ChartSeries : IChartSeries
```

## Thuộc tính

| Name | Description |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Xác định hình dạng của một chuỗi trong biểu đồ thanh 3D. Thay đổi giá trị của thuộc tính này có thể tự động thay đổi Loại của chuỗi. Đọc/ghi [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là sự chiếu của thuộc tính nhóm thích hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeRepresentation đọc/ghi để thay đổi giá trị. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể nằm trong khoảng 0 đến 300 phần trăm kích thước mặc định). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là sự chiếu của thuộc tính nhóm thích hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeScale đọc/ghi để thay đổi giá trị. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Trả về biểu đồ cha. Chỉ đọc [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Trả về bộ sưu tập các điểm dữ liệu của chuỗi này. Chỉ đọc [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Xác định kích thước lỗ trong biểu đồ bánh răng (có thể nằm trong khoảng 10 đến 90 phần trăm kích thước vùng vẽ). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là sự chiếu của thuộc tính nhóm thích hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.DoughnutHoleSize đọc/ghi để thay đổi giá trị. Chỉ đọc Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Đại diện cho ErrorBars của chuỗi với hướng X. ErrorBars với hướng X chỉ khả dụng cho các chuỗi loại area, bar, scatter và bubble. Đối với các loại biểu đồ khác thuộc tính này trả về null (bao gồm cả biểu đồ 3D). Khi sử dụng giá trị tùy chỉnh, dùng bộ sưu tập DataPoints để chỉ định giá trị (với thuộc tính [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Chỉ đọc [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Đại diện cho ErrorBars của chuỗi với hướng Y. ErrorBars với hướng Y chỉ khả dụng cho các chuỗi loại area, bar, line, scatter và bubble. Đối với các loại biểu đồ khác thuộc tính này trả về null (bao gồm cả biểu đồ 3D). Khi sử dụng giá trị tùy chỉnh, dùng bộ sưu tập DataPoints để chỉ định giá trị (với thuộc tính [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Chỉ đọc [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Khoảng cách của một miếng bánh mở từ trung tâm biểu đồ bánh được biểu diễn dưới dạng phần trăm của đường kính bánh. Đọc/ghi Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Xác định góc của miếng bánh hoặc phần bánh donut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là sự chiếu của thuộc tính nhóm thích hợp. Do vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.FirstSliceAngle đọc/ghi để thay đổi giá trị. Chỉ đọc UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Trả về định dạng của chuỗi. Chỉ đọc [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Trả về hoặc đặt khoảng cách, tính bằng phần trăm chiều rộng marker, giữa các chuỗi dữ liệu trong biểu đồ 3D. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là sự chiếu của thuộc tính nhóm thích hợp. Do vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.GapDepth đọc/ghi để thay đổi giá trị. Chỉ đọc Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Xác định khoảng cách giữa các cụm cột hoặc thanh, tính bằng phần trăm chiều rộng cột hoặc thanh. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là sự chiếu của thuộc tính nhóm thích hợp. Do vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.GapWidth đọc/ghi để thay đổi giá trị. Chỉ đọc Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Xác định liệu có đường chuỗi cho chuỗi này và các chuỗi liên quan hay không. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là sự chiếu của thuộc tính nhóm thích hợp. Do vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.HasSeriesLines đọc/ghi để thay đổi giá trị. Sử dụng thuộc tính ParentSeriesGroup.SeriesLinesFormat để định dạng đường chuỗi. Chỉ đọc Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Xác định liệu biểu đồ Đường hoặc Cổ phiếu có thanh lên/xuống hay không. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là sự chiếu của thuộc tính nhóm thích hợp. Do vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars.HasUpDownBars đọc/ghi để thay đổi giá trị. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars để định dạng thanh lên/xuống. Chỉ đọc Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Xác định màu rắn đảo ngược cho chuỗi. Để áp dụng cài đặt màu, đặt FillType của định dạng chuỗi thành FillType.Solid. Đọc/ghi [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Xác định liệu chuỗi thanh, cột hoặc bong bóng có đảo ngược màu khi giá trị âm không. Đọc/ghi Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Xác định mỗi marker dữ liệu trong chuỗi có màu khác nhau. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là sự chiếu của thuộc tính nhóm thích hợp. Do vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.IsColorVaried đọc/ghi để thay đổi giá trị. Chỉ đọc Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Trả về Labels của một chuỗi. Chỉ đọc [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Marker. Chỉ đọc [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Trả về tên chuỗi. Chỉ đọc [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Đọc/ghi String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Đọc/ghi String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Đọc/ghi String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Đọc/ghi String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Trả về thứ tự của chuỗi. Đọc/ghi Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2D, tính bằng phần trăm (từ -100% đến 100%). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là sự chiếu của thuộc tính nhóm thích hợp. Do vậy thuộc tính này chỉ đọc. Để thay đổi giá trị, sử dụng thuộc tính !:ParentSeriesGroup.Overlap đọc/ghi. Chỉ đọc SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Đại diện cho bố cục của các nhãn danh mục cha. Chỉ áp dụng cho biểu đồ Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Chỉ đọc [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Xác định cách xác định các điểm dữ liệu nào nằm trong miếng bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là sự chiếu của thuộc tính nhóm thích hợp. Do vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitBy đọc/ghi để thay đổi giá trị. Chỉ đọc [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Thông tin phân tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có phân tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong miếng bánh hoặc thanh thứ hai. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là sự chiếu của thuộc tính nhóm thích hợp. Chỉ đọc [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Xác định giá trị sẽ được sử dụng để xác định các điểm dữ liệu nào nằm trong miếng bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là sự chiếu của thuộc tính nhóm thích hợp. Do vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitPosition đọc/ghi để thay đổi giá trị. Chỉ đọc Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Cho biết liệu chuỗi này có được vẽ trên trục phụ không. Đọc/ghi Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Đại diện cho phương pháp quartile. Chỉ áp dụng cho biểu đồ BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Đại diện cho mục nhập chú giải liên quan tới chuỗi này. Chỉ đọc [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Xác định kích thước của miếng bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của miếng bánh đầu tiên (có thể nằm trong khoảng 5 đến 200 phần trăm). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là sự chiếu của thuộc tính nhóm thích hợp. Do vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.SecondPieSize đọc/ghi để thay đổi giá trị. Chỉ đọc UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Đại diện cho các đường nối. Chỉ áp dụng cho biểu đồ Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Đại diện cho các điểm nội bộ. Đúng nếu các điểm nội bộ được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Đại diện cho đường trung bình. Đúng nếu đường trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Đại diện cho các marker trung bình. Đúng nếu các marker trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Đại diện cho các điểm ngoại lệ. Đúng nếu các điểm ngoại lệ được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Đại diện cho làm mịn đường cong. Đúng nếu làm mịn đường cong được bật cho biểu đồ đường hoặc scatter. Chỉ áp dụng cho biểu đồ đường và scatter nối bằng đường thẳng. Đọc/ghi Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Bộ sưu tập các đường xu hướng của chuỗi. Chỉ đọc [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Trả về kiểu của chuỗi này. Đọc/ghi [`ChartType`](../charttype). |

## Phương thức

| Name | Description |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Trả về màu tự động của chuỗi dựa trên chỉ mục chuỗi và kiểu biểu đồ. Màu này được sử dụng mặc định nếu FillType bằng NotDefined. |

### Xem thêm

* interface [IChartSeries](../ichartseries)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->