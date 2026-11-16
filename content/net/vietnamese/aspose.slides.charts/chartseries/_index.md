---
title: ChartSeries
second_title: Aspose.Sildes cho Tham chiếu API .NET
description: Biểu diễn một chuỗi biểu đồ.
type: docs
weight: 1450
url: /vi/aspose.slides.charts/chartseries/
---
## ChartSeries lớp

Biểu diễn một chuỗi biểu đồ.

```csharp
public class ChartSeries : IChartSeries
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Chỉ định hình dạng của một chuỗi trong biểu đồ cột 3-D. Thay đổi giá trị của thuộc tính này có thể gây tự động thay đổi Type của chuỗi. Đọc/ghi [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Chỉ định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Thuộc tính này không chỉ thuộc về chuỗi này mà còn thuộc về tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeRepresentation Đọc/ghi để thay đổi giá trị. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Chỉ định hệ số co cho biểu đồ bong bóng (có thể nằm trong khoảng từ 0 đến 300% kích thước mặc định). Thuộc tính này không chỉ thuộc về chuỗi này mà còn thuộc về tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeScale Đọc/ghi để thay đổi giá trị. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Trả về biểu đồ cha. Chỉ đọc [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Trả về bộ sưu tập các điểm dữ liệu của chuỗi này. Chỉ đọc [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Chỉ định kích thước của lỗ trong biểu đồ bánh răng (có thể nằm trong khoảng từ 10 đến 90% kích thước vùng vẽ). Thuộc tính này không chỉ thuộc về chuỗi này mà còn thuộc về tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.DoughnutHoleSize Đọc/ghi để thay đổi giá trị. Chỉ đọc Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Biểu diễn ErrorBars của chuỗi với hướng X. ErrorBars với hướng X khả dụng cho các chuỗi loại area, bar, scatter và bubble. Đối với các loại biểu đồ khác, thuộc tính này trả về null (bao gồm cả biểu đồ 3D). Trong trường hợp các giá trị tùy chỉnh, sử dụng bộ sưu tập DataPoints để chỉ định giá trị (với thuộc tính [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Chỉ đọc [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Biểu diễn ErrorBars của chuỗi với hướng Y. ErrorBars với hướng Y khả dụng cho các chuỗi loại area, bar, line, scatter và bubble. Đối với các loại biểu đồ khác, thuộc tính này trả về null (bao gồm cả biểu đồ 3D). Trong trường hợp các giá trị tùy chỉnh, sử dụng bộ sưu tập DataPoints để chỉ định giá trị (với thuộc tính [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Chỉ đọc [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Khoảng cách của một miếng bánh mở từ trung tâm của biểu đồ bánh được biểu thị dưới dạng phần trăm của đường kính bánh. Đọc/ghi Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Chỉ định góc của miếng bánh hoặc bánh răng đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Thuộc tính này không chỉ thuộc về chuỗi này mà còn thuộc về tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.FirstSliceAngle Đọc/ghi để thay đổi giá trị. Chỉ đọc UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Trả về định dạng của một chuỗi. Chỉ đọc [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Trả về hoặc đặt khoảng cách, tính theo phần trăm độ rộng marker, giữa các chuỗi dữ liệu trong biểu đồ 3D. Thuộc tính này không chỉ thuộc về chuỗi này mà còn thuộc về tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.GapDepth Đọc/ghi để thay đổi giá trị. Chỉ đọc Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Chỉ định khoảng cách giữa các cụm thanh hoặc cột, tính theo phần trăm độ rộng thanh hoặc cột. Thuộc tính này không chỉ thuộc về chuỗi này mà còn thuộc về tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.GapWidth Đọc/ghi để thay đổi giá trị. Chỉ đọc Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Xác định liệu có đường chuỗi cho chuỗi này và các chuỗi liên quan hay không. Thuộc tính này không chỉ thuộc về chuỗi này mà còn thuộc về tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.HasSeriesLines Đọc/ghi để thay đổi giá trị. Sử dụng thuộc tính ParentSeriesGroup.SeriesLinesFormat để định dạng đường chuỗi. Chỉ đọc Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Xác định liệu biểu đồ Đường hoặc Cổ phiếu có thanh lên/xuống hay không. Thuộc tính này không chỉ thuộc về chuỗi này mà còn thuộc về tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars.HasUpDownBars Đọc/ghi để thay đổi giá trị. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars để định dạng thanh lên/xuống. Chỉ đọc Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Chỉ định màu đặc đảo ngược cho chuỗi. Để áp dụng cài đặt màu, đặt FillType của định dạng chuỗi thành FillType.Solid. Đọc/ghi [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Chỉ định thanh, cột hoặc chuỗi bong bóng sẽ đảo ngược màu nếu giá trị âm. Đọc/ghi Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Chỉ định mỗi đánh dấu dữ liệu trong chuỗi có màu khác nhau. Thuộc tính này không chỉ thuộc về chuỗi này mà còn thuộc về tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.IsColorVaried Đọc/ghi để thay đổi giá trị. Chỉ đọc Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Trả về Labels của một chuỗi. Chỉ đọc [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Marker. Chỉ đọc [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Trả về tên chuỗi. Chỉ đọc [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Đọc/ghi String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Đọc/ghi String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Đọc/ghi String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Đọc/ghi String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Trả về thứ tự của một chuỗi. Đọc/ghi Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Chỉ định mức độ chồng lấp của các thanh và cột trên biểu đồ 2-D, tính theo phần trăm (từ -100% đến 100%). Thuộc tính này không chỉ thuộc về chuỗi này mà còn thuộc về tất cả các chuỗi trong nhóm chuỗi cha. Để thay đổi giá trị, sử dụng thuộc tính !:ParentSeriesGroup.Overlap Đọc/ghi. Chỉ đọc SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Biểu diễn bố cục của các nhãn danh mục cha. Chỉ áp dụng cho biểu đồ Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Chỉ đọc [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Chỉ định cách xác định những điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Thuộc tính này không chỉ thuộc về chuỗi này mà còn thuộc về tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitBy Đọc/ghi để thay đổi giá trị. Chỉ đọc [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Thông tin chia riêng tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có chia riêng. Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai. Thuộc tính này không chỉ thuộc về chuỗi này mà còn thuộc về tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Chỉ đọc [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Chỉ định giá trị được dùng để xác định những điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Thuộc tính này không chỉ thuộc về chuỗi này mà còn thuộc về tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitPosition Đọc/ghi để thay đổi giá trị. Chỉ đọc Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Cho biết nếu chuỗi này được vẽ trên trục phụ. Đọc/ghi Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Biểu diễn phương pháp tứ vị. Chỉ áp dụng cho biểu đồ BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Biểu diễn mục chú giải liên quan đến chuỗi này. Chỉ đọc [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Chỉ định kích thước của bánh hoặc thanh thứ hai của biểu đồ pie-of-pie hoặc bar-of-pie, tính theo phần trăm kích thước của bánh đầu tiên (có thể nằm trong khoảng từ 5 đến 200%). Thuộc tính này không chỉ thuộc về chuỗi này mà còn thuộc về tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.SecondPieSize Đọc/ghi để thay đổi giá trị. Chỉ đọc UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Biểu diễn các đường nối. Chỉ áp dụng cho biểu đồ Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Biểu diễn các điểm nội. Đúng nếu các điểm nội được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Biểu diễn đường trung bình. Đúng nếu đường trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Biểu diễn các điểm trung bình. Đúng nếu các điểm trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Biểu diễn các điểm ngoại lệ. Đúng nếu các điểm ngoại lệ được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Biểu diễn làm mịn đường cong. Đúng nếu làm mịn đường cong được bật cho biểu đồ đường hoặc biểu đồ phân tán. Chỉ áp dụng cho các biểu đồ đường và phân tán nối bằng đường. Đọc/ghi Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Bộ sưu tập các đường xu hướng của chuỗi. Chỉ đọc [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Trả về kiểu của chuỗi này. Đọc/ghi [`ChartType`](../charttype). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Trả về màu tự động của chuỗi dựa trên chỉ mục chuỗi và kiểu biểu đồ. Màu này được sử dụng mặc định nếu FillType bằng NotDefined. |

### Xem thêm

* giao diện [IChartSeries](../ichartseries)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->