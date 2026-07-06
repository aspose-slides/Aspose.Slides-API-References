---
title: ChartSeries
second_title: Tham khảo API Aspose.Sildes cho .NET
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

| Tên | Mô tả |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Xác định hình dạng của một chuỗi trong biểu đồ thanh 3D. Thay đổi giá trị của thuộc tính này có thể gây tự động thay đổi Type của chuỗi. Đọc/ghi [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeRepresentation để đọc/ghi khi thay đổi giá trị. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể nằm trong khoảng 0 đến 300 phần trăm kích thước mặc định). Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeScale để đọc/ghi khi thay đổi giá trị. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Trả về biểu đồ cha. Chỉ đọc [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Trả về tập hợp các điểm dữ liệu của chuỗi này. Chỉ đọc [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Xác định kích thước của lỗ trong biểu đồ doughnut (có thể nằm trong khoảng 10 đến 90 phần trăm kích thước của vùng vẽ). Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.DoughnutHoleSize để đọc/ghi khi thay đổi giá trị. Chỉ đọc Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Biểu diễn ErrorBars của chuỗi với hướng X. ErrorBars có hướng X khả dụng cho các chuỗi loại area, bar, scatter và bubble. Đối với các loại biểu đồ khác, thuộc tính này trả về null (bao gồm biểu đồ 3D). Trong trường hợp giá trị tùy chỉnh, sử dụng tập hợp DataPoints để chỉ định giá trị (với thuộc tính [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Chỉ đọc [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Biểu diễn ErrorBars của chuỗi với hướng Y. ErrorBars có hướng Y khả dụng cho các chuỗi loại area, bar, line, scatter và bubble. Đối với các loại biểu đồ khác, thuộc tính này trả về null (bao gồm biểu đồ 3D). Trong trường hợp giá trị tùy chỉnh, sử dụng tập hợp DataPoints để chỉ định giá trị (với thuộc tính [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Chỉ đọc [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Khoảng cách của một miếng bánh mở từ trung tâm biểu đồ bánh được biểu thị dưới dạng phần trăm của đường kính bánh. Đọc/ghi Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Xác định góc của miếng bánh hoặc doughnut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.FirstSliceAngle để đọc/ghi khi thay đổi giá trị. Chỉ đọc UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Trả về định dạng của một chuỗi. Chỉ đọc [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Trả về hoặc đặt khoảng cách, tính bằng phần trăm độ rộng marker, giữa các chuỗi dữ liệu trong biểu đồ 3D. Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.GapDepth để đọc/ghi khi thay đổi giá trị. Chỉ đọc Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Xác định khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm độ rộng thanh hoặc cột. Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.GapWidth để đọc/ghi khi thay đổi giá trị. Chỉ đọc Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Xác định liệu có các đường chuỗi cho chuỗi này và các chuỗi liên quan không. Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.HasSeriesLines để đọc/ghi khi thay đổi giá trị. Sử dụng thuộc tính ParentSeriesGroup.SeriesLinesFormat để định dạng các đường chuỗi. Chỉ đọc Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Xác định liệu biểu đồ Line hoặc Stock có các thanh lên/xuống hay không. Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars.HasUpDownBars để đọc/ghi khi thay đổi giá trị. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars để định dạng các thanh lên/xuống. Chỉ đọc Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Xác định màu nền đặc đảo ngược cho chuỗi. Để áp dụng cài đặt màu, đặt FillType của định dạng chuỗi thành FillType.Solid. Đọc/ghi [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Xác định thanh, cột hoặc chuỗi bubble sẽ đảo ngược màu nếu giá trị âm. Đọc/ghi Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Xác định mỗi marker dữ liệu trong chuỗi có màu khác nhau. Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.IsColorVaried để đọc/ghi khi thay đổi giá trị. Chỉ đọc Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Trả về Labels của một chuỗi. Chỉ đọc [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Marker. Chỉ đọc [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Trả về tên chuỗi. Chỉ đọc [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Đọc/ghi String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Đọc/ghi String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Đọc/ghi String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Đọc/ghi String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Trả về thứ tự của một chuỗi. Đọc/ghi Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Xác định mức độ chồng lên nhau của các thanh và cột trên biểu đồ 2D, tính bằng phần trăm (từ -100% đến 100%). Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha. Nó là phép chiếu của thuộc tính phù hợp trong nhóm chuỗi cha, do đó thuộc tính này chỉ đọc. Để thay đổi giá trị, sử dụng thuộc tính !:ParentSeriesGroup.Overlap để đọc/ghi. Chỉ đọc SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Biểu diễn bố cục của các nhãn danh mục cha. Chỉ áp dụng cho biểu đồ Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Chỉ đọc [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Xác định cách xác định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitBy để đọc/ghi khi thay đổi giá trị. Chỉ đọc [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Thông tin tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie. Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Chỉ đọc [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Xác định một giá trị sẽ được dùng để xác định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitPosition để đọc/ghi khi thay đổi giá trị. Chỉ đọc Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Cho biết liệu chuỗi này có được vẽ trên trục phụ không. Đọc/ghi Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Biểu diễn phương pháp tứ phân vị. Chỉ áp dụng cho biểu đồ BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Biểu diễn mục chú giải liên quan tới chuỗi này. Chỉ đọc [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của bánh đầu tiên (có thể nằm trong khoảng 5 đến 200 phần trăm). Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.SecondPieSize để đọc/ghi khi thay đổi giá trị. Chỉ đọc UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Biểu diễn các đường nối. Chỉ áp dụng cho biểu đồ Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Biểu diễn các điểm nội. Đúng nếu các điểm nội được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Biểu diễn đường trung bình. Đúng nếu đường trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Biểu diễn các điểm trung bình. Đúng nếu các điểm trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Biểu diễn các điểm ngoại lệ. Đúng nếu các điểm ngoại lệ được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Biểu diễn làm mượt đường cong. Đúng nếu làm mượt đường cong được bật cho biểu đồ đường hoặc scatter. Chỉ áp dụng cho biểu đồ đường và scatter được nối bằng đường thẳng. Đọc/ghi Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Tập hợp các đường xu hướng của chuỗi. Chỉ đọc [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Trả về kiểu của chuỗi này. Đọc/ghi [`ChartType`](../charttype). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Trả về màu tự động của chuỗi dựa trên chỉ số chuỗi và kiểu biểu đồ. Màu này được sử dụng mặc định nếu FillType bằng NotDefined. |

### Xem thêm

* giao diện [IChartSeries](../ichartseries)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->