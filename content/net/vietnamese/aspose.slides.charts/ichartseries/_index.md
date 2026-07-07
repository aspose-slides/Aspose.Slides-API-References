---
title: IChartSeries
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn một chuỗi biểu đồ.
type: docs
weight: 1930
url: /vi/aspose.slides.charts/ichartseries/
---

## IChartSeries giao diện

Biểu diễn một chuỗi biểu đồ.

```csharp
public interface IChartSeries : IChartComponent
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Cho phép lấy giao diện IChartComponent cơ bản. Chỉ đọc [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | Xác định hình dạng của một chuỗi trong biểu đồ cột 3D. Thay đổi giá trị của thuộc tính này có thể gây tự động thay đổi Type của chuỗi. Đọc/ghi [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeRepresentation Đọc/ghi để thay đổi giá trị. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể nằm trong khoảng từ 0 đến 300 phần trăm kích thước mặc định). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeScale Đọc/ghi để thay đổi giá trị. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Trả về bộ sưu tập các điểm dữ liệu của chuỗi này. Chỉ đọc [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Xác định kích thước lỗ trong biểu đồ vòng cung (có thể nằm trong khoảng từ 10 đến 90 phần trăm kích thước của vùng vẽ). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.DoughnutHoleSize Đọc/ghi để thay đổi giá trị. Chỉ đọc Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | Biểu diễn ErrorBars của chuỗi có hướng X. ErrorBars với hướng X khả dụng cho các chuỗi loại area, bar, scatter và bubble. Đối với các loại biểu đồ khác thuộc tính này trả về null (bao gồm biểu đồ 3D). Trong trường hợp giá trị tùy chỉnh, sử dụng bộ sưu tập DataPoints để chỉ định giá trị (với thuộc tính [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Chỉ đọc [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Biểu diễn ErrorBars của chuỗi có hướng Y. ErrorBars với hướng Y khả dụng cho các chuỗi loại area, bar, line, scatter và bubble. Đối với các loại biểu đồ khác thuộc tính này trả về null (bao gồm biểu đồ 3D). Trong trường hợp giá trị tùy chỉnh, sử dụng bộ sưu tập DataPoints để chỉ định giá trị (với thuộc tính [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Chỉ đọc [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | Khoảng cách của một lát bánh pie mở từ trung tâm biểu đồ pie được biểu diễn dưới dạng phần trăm của đường kính pie. Đọc/ghi Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | Xác định góc của lát bánh pie hoặc doughnut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.FirstSliceAngle Đọc/ghi để thay đổi giá trị. Chỉ đọc UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Trả về định dạng của một chuỗi. Chỉ đọc [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | Trả về hoặc đặt khoảng cách, tính bằng phần trăm của chiều rộng marker, giữa các chuỗi dữ liệu trong biểu đồ 3D. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.GapDepth Đọc/ghi để thay đổi giá trị. Chỉ đọc Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Xác định khoảng cách giữa các cụm cột hoặc thanh, tính bằng phần trăm chiều rộng cột hoặc thanh. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.GapWidth Đọc/ghi để thay đổi giá trị. Chỉ đọc Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Xác định có đường chuỗi cho chuỗi này và các chuỗi liên quan hay không. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.HasSeriesLines Đọc/ghi để thay đổi giá trị. Sử dụng thuộc tính ParentSeriesGroup.SeriesLinesFormat để định dạng đường chuỗi. Chỉ đọc Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Xác định biểu đồ Line hoặc Stock có thanh lên/xuống hay không. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars.HasUpDownBars Đọc/ghi để thay đổi giá trị. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars để định dạng thanh lên/xuống. Chỉ đọc Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Xác định màu nền đảo ngược cho chuỗi. Để áp dụng cài đặt màu, đặt FillType của định dạng chuỗi thành FillType.Solid. Đọc/ghi [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Xác định rằng chuỗi cột, thanh hoặc bong bóng sẽ đảo ngược màu nếu giá trị là âm. Đọc/ghi Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Xác định rằng mỗi marker dữ liệu trong chuỗi có màu khác nhau. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.IsColorVaried Đọc/ghi để thay đổi giá trị. Chỉ đọc Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Trả về Labels của một chuỗi. Chỉ đọc [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Trả về marker của chuỗi. Chỉ đọc [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Trả về tên chuỗi. Chỉ đọc [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Trả về hoặc đặt định dạng số cho kích thước bong bóng của chuỗi. Đọc/ghi String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Trả về hoặc đặt định dạng số cho các giá trị của chuỗi. Đọc/ghi String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Trả về hoặc đặt định dạng số cho các giá trị x của chuỗi. Đọc/ghi String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Trả về hoặc đặt định dạng số cho các giá trị y của chuỗi. Đọc/ghi String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Trả về thứ tự của một chuỗi. Đọc/ghi Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | Xác định mức độ chồng chập của các thanh và cột trên biểu đồ 2D, tính bằng phần trăm (từ -100% đến 100%). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Để thay đổi giá trị, sử dụng thuộc tính ParentSeriesGroup.Overlap Đọc/ghi. Chỉ đọc SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Biểu diễn bố cục của nhãn danh mục cha. Chỉ áp dụng cho biểu đồ Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Trả về nhóm chuỗi cha. Chỉ đọc [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Xác định cách xác định các điểm dữ liệu nào nằm trong bánh thứ hai hoặc thanh trên biểu đồ pie-of-pie hoặc bar-of-pie. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitBy Đọc/ghi để thay đổi giá trị. Chỉ đọc [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | Thông tin chia tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có chia tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh thứ hai hoặc thanh trên biểu đồ pie-of-pie hoặc bar-of-pie. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Chỉ đọc [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | Xác định giá trị sẽ được sử dụng để xác định các điểm dữ liệu nào nằm trong bánh thứ hai hoặc thanh trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitPosition Đọc/ghi để thay đổi giá trị. Chỉ đọc Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Chỉ ra liệu chuỗi này có được vẽ trên trục giá trị thứ hai hay không. Đọc/ghi Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Biểu diễn phương pháp quartile. Chỉ áp dụng cho biểu đồ BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Biểu diễn mục legend liên quan tới chuỗi này. Chỉ đọc [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 đến 200 phần trăm). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập vào nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.SecondPieSize Đọc/ghi để thay đổi giá trị. Chỉ đọc UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Biểu diễn các đường kết nối. Chỉ áp dụng cho biểu đồ Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | Biểu diễn các điểm nội. Đúng nếu các điểm nội được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Biểu diễn các dấu mean. Đúng nếu đường mean được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Biểu diễn các dấu mean. Đúng nếu các dấu mean được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Biểu diễn các điểm outlier. Đúng nếu các điểm outlier được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Biểu diễn làm mượt đường cong. Đúng nếu làm mượt đường cong được bật cho biểu đồ line hoặc scatter. Chỉ áp dụng cho biểu đồ line và scatter được nối bằng đường. Đọc/ghi Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Bộ sưu tập các trend line của chuỗi. Chỉ đọc [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Trả về kiểu của chuỗi này. Đọc/ghi [`ChartType`](../charttype). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Trả về màu tự động của chuỗi dựa trên chỉ số chuỗi và kiểu biểu đồ. Màu này được sử dụng mặc định nếu FillType bằng NotDefined. |

### Xem thêm

* giao diện [IChartComponent](../ichartcomponent)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* bộ lắp ráp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->