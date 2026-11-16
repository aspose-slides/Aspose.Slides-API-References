---
title: IChartSeries
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Đại diện cho một chuỗi biểu đồ.
type: docs
weight: 1950
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
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | Xác định hình dạng của chuỗi trong biểu đồ cột 3-D. Thay đổi giá trị của thuộc tính này có thể gây thay đổi tự động Kiểu của chuỗi. Đọc/ghi [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeRepresentation đọc/ghi để thay đổi giá trị. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Xác định hệ số tỉ lệ cho biểu đồ bong bóng (có thể từ 0 đến 300 phần trăm kích thước mặc định). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeScale đọc/ghi để thay đổi giá trị. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Trả về tập hợp các điểm dữ liệu của chuỗi này. Chỉ đọc [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Xác định kích thước lỗ trong biểu đồ bánh donut (có thể từ 10 đến 90 phần trăm kích thước vùng vẽ). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.DoughnutHoleSize đọc/ghi để thay đổi giá trị. Chỉ đọc Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | Biểu thị ErrorBars của chuỗi với hướng X. ErrorBars với hướng X khả dụng cho các chuỗi loại area, bar, scatter và bubble. Đối với các loại biểu đồ khác thuộc tính này trả về null (bao gồm biểu đồ 3D). Trong trường hợp giá trị tùy chỉnh, sử dụng tập hợp DataPoints để chỉ định giá trị (với thuộc tính [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Chỉ đọc [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Biểu thị ErrorBars của chuỗi với hướng Y. ErrorBars với hướng Y khả dụng cho các chuỗi loại area, bar, line, scatter và bubble. Đối với các loại biểu đồ khác thuộc tính này trả về null (bao gồm biểu đồ 3D). Trong trường hợp giá trị tùy chỉnh, sử dụng tập hợp DataPoints để chỉ định giá trị (với thuộc tính [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Chỉ đọc [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | Khoảng cách của một lát bánh mở từ trung tâm biểu đồ bánh được biểu diễn dưới dạng phần trăm của đường kính bánh. Đọc/ghi Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | Xác định góc của lát bánh hoặc bánh donut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ lên trên, từ 0 đến 360 độ). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.FirstSliceAngle đọc/ghi để thay đổi giá trị. Chỉ đọc UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Trả về định dạng của một chuỗi. Chỉ đọc [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | Trả về hoặc đặt khoảng cách, tính bằng phần trăm chiều rộng dấu đánh dấu, giữa các chuỗi dữ liệu trong biểu đồ 3D. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.GapDepth đọc/ghi để thay đổi giá trị. Chỉ đọc Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Xác định khoảng cách giữa các cụm cột hoặc thanh, tính bằng phần trăm chiều rộng cột hoặc thanh. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.GapWidth đọc/ghi để thay đổi giá trị. Chỉ đọc Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Xác định có đường nối chuỗi cho chuỗi này và các chuỗi liên quan hay không. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.HasSeriesLines đọc/ghi để thay đổi giá trị. Sử dụng thuộc tính ParentSeriesGroup.SeriesLinesFormat để định dạng các đường nối chuỗi. Chỉ đọc Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Xác định biểu đồ Đường hoặc Cổ phiếu có thanh lên/xuống hay không. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars.HasUpDownBars đọc/ghi để thay đổi giá trị. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars để định dạng các thanh lên/xuống. Chỉ đọc Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Xác định màu nền đảo ngược cho chuỗi. Để áp dụng cài đặt màu, đặt FillType của định dạng chuỗi thành FillType.Solid. Đọc/ghi [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Xác định rằng chuỗi cột, thanh hoặc bong bóng sẽ đảo ngược màu nếu giá trị là âm. Đọc/ghi Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Xác định mỗi dấu đánh dấu dữ liệu trong chuỗi có màu khác nhau. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.IsColorVaried đọc/ghi để thay đổi giá trị. Chỉ đọc Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Trả về Labels của một chuỗi. Chỉ đọc [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Trả về dấu đánh dấu chuỗi. Chỉ đọc [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Trả về tên chuỗi. Chỉ đọc [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Trả về hoặc đặt định dạng số cho kích thước bong bóng của chuỗi. Đọc/ghi String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Trả về hoặc đặt định dạng số cho giá trị của chuỗi. Đọc/ghi String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Trả về hoặc đặt định dạng số cho giá trị x của chuỗi. Đọc/ghi String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Trả về hoặc đặt định dạng số cho giá trị y của chuỗi. Đọc/ghi String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Trả về thứ tự của một chuỗi. Đọc/ghi Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | Xác định mức độ chồng chéo của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% đến 100%). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha. Đây là phép chiếu của thuộc tính tương ứng trong nhóm chuỗi cha, do đó thuộc tính này chỉ đọc. Để thay đổi giá trị, sử dụng thuộc tính ParentSeriesGroup.Overlap đọc/ghi. Chỉ đọc SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Biểu thị bố cục của các nhãn danh mục cha. Chỉ áp dụng cho biểu đồ Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Trả về nhóm chuỗi cha. Chỉ đọc [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Xác định cách quyết định điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitBy đọc/ghi để thay đổi giá trị. Chỉ đọc [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | Thông tin chia tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có chia tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Chỉ đọc [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | Xác định giá trị dùng để quyết định điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitPosition đọc/ghi để thay đổi giá trị. Chỉ đọc Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Chỉ ra nếu chuỗi này được vẽ trên trục giá trị thứ hai. Đọc/ghi Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Biểu thị phương pháp quartile. Chỉ áp dụng cho biểu đồ BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Biểu thị mục nhập chú giải liên quan đến chuỗi này. Chỉ đọc [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước bánh đầu tiên (có thể từ 5 đến 200 phần trăm). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.SecondPieSize đọc/ghi để thay đổi giá trị. Chỉ đọc UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Biểu thị các đường nối. Chỉ áp dụng cho biểu đồ Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | Biểu thị các điểm trong. Đúng nếu các điểm trong được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Biểu thị các dấu trung bình. Đúng nếu đường trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Biểu thị các dấu trung bình. Đúng nếu các dấu trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Biểu thị các điểm ngoại lệ. Đúng nếu các điểm ngoại lệ được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Biểu thị làm trơn đường cong. Đúng nếu làm trơn đường cong được bật cho biểu đồ đường hoặc scatter. Chỉ áp dụng cho các biểu đồ đường và scatter nối bằng đường. Đọc/ghi Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Tập hợp các đường xu hướng chuỗi. Chỉ đọc [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Trả về loại của chuỗi này. Đọc/ghi [`ChartType`](../charttype). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Trả về màu tự động của chuỗi dựa trên chỉ mục chuỗi và kiểu biểu đồ. Màu này được sử dụng mặc định nếu FillType bằng NotDefined. |

### Xem thêm

* giao diện [IChartComponent](../ichartcomponent)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* bộ lắp ráp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->