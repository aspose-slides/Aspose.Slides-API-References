---
title: IChartSeries
second_title: Aspose.Sildes cho .NET API Reference
description: Đại diện cho một chuỗi biểu đồ.
type: docs
weight: 1930
url: /vi/aspose.slides.charts/ichartseries/
---
## IChartSeries giao diện

Đại diện cho một chuỗi biểu đồ.

```csharp
public interface IChartSeries : IChartComponent
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Cho phép lấy giao diện IChartComponent cơ bản. Chỉ đọc [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | Xác định hình dạng của một chuỗi biểu đồ cột 3-D. Thay đổi giá trị của thuộc tính này có thể gây tự động thay đổi Type của chuỗi. Đọc/ghi [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là phép chiếu của thuộc tính nhóm liên quan. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeRepresentation để đọc/ghi khi thay đổi giá trị. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 đến 300 % kích thước mặc định). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là phép chiếu của thuộc tính nhóm liên quan. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeScale để đọc/ghi khi thay đổi giá trị. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Trả về tập hợp các điểm dữ liệu của chuỗi này. Chỉ đọc [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Xác định kích thước lỗ trong biểu đồ bánh rời (có thể từ 10 % đến 90 % kích thước vùng vẽ). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là phép chiếu của thuộc tính nhóm liên quan. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.DoughnutHoleSize để đọc/ghi khi thay đổi giá trị. Chỉ đọc Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | Đại diện cho ErrorBars của chuỗi có hướng X. ErrorBars với hướng X khả dụng cho các chuỗi loại area, bar, scatter và bubble. Đối với các loại biểu đồ khác thuộc tính này trả về null (bao gồm cả biểu đồ 3D). Khi sử dụng giá trị tùy chỉnh, hãy dùng tập hợp DataPoints để chỉ định giá trị (với thuộc tính [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Chỉ đọc [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Đại diện cho ErrorBars của chuỗi có hướng Y. ErrorBars với hướng Y khả dụng cho các chuỗi loại area, bar, line, scatter và bubble. Đối với các loại biểu đồ khác thuộc tính này trả về null (bao gồm cả biểu đồ 3D). Khi sử dụng giá trị tùy chỉnh, hãy dùng tập hợp DataPoints để chỉ định giá trị (với thuộc tính [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Chỉ đọc [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | Khoảng cách của miếng bánh mở so với tâm bánh được biểu diễn bằng phần trăm của đường kính bánh. Đọc/ghi Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | Xác định góc của miếng bánh hoặc bánh rời đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ vị trí lên, từ 0 đến 360 độ). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là phép chiếu của thuộc tính nhóm liên quan. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.FirstSliceAngle để đọc/ghi khi thay đổi giá trị. Chỉ đọc UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Trả về định dạng của một chuỗi. Chỉ đọc [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | Trả về hoặc đặt khoảng cách, tính bằng phần trăm của chiều rộng marker, giữa các chuỗi dữ liệu trong biểu đồ 3D. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là phép chiếu của thuộc tính nhóm liên quan. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.GapDepth để đọc/ghi khi thay đổi giá trị. Chỉ đọc Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Xác định khoảng cách giữa các cụm cột hoặc thanh, tính bằng phần trăm của chiều rộng cột hoặc thanh. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là phép chiếu của thuộc tính nhóm liên quan. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.GapWidth để đọc/ghi khi thay đổi giá trị. Chỉ đọc Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Xác định có đường nối chuỗi cho chuỗi này và các chuỗi liên quan hay không. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là phép chiếu của thuộc tính nhóm liên quan. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.HasSeriesLines để đọc/ghi khi thay đổi giá trị. Sử dụng thuộc tính ParentSeriesGroup.SeriesLinesFormat để định dạng đường nối chuỗi. Chỉ đọc Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Xác định biểu đồ Line hoặc Stock có thanh lên/xuống hay không. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là phép chiếu của thuộc tính nhóm liên quan. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars.HasUpDownBars để đọc/ghi khi thay đổi giá trị. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars để định dạng thanh lên/xuống. Chỉ đọc Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Xác định màu nền đảo ngược cho chuỗi. Để áp dụng cài đặt màu, đặt thuộc tính Format của chuỗi FillType thành FillType.Solid. Đọc/ghi [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Xác định thanh, cột hoặc chuỗi bong bóng sẽ đảo ngược màu nếu giá trị âm. Đọc/ghi Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Xác định mỗi marker dữ liệu trong chuỗi có màu khác nhau. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là phép chiếu của thuộc tính nhóm liên quan. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.IsColorVaried để đọc/ghi khi thay đổi giá trị. Chỉ đọc Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Trả về Labels của một chuỗi. Chỉ đọc [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Trả về marker của chuỗi. Chỉ đọc [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Trả về tên chuỗi. Chỉ đọc [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Trả về hoặc đặt định dạng số cho kích thước bong bóng của chuỗi. Đọc/ghi String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Trả về hoặc đặt định dạng số cho giá trị của chuỗi. Đọc/ghi String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Trả về hoặc đặt định dạng số cho giá trị x của chuỗi. Đọc/ghi String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Trả về hoặc đặt định dạng số cho giá trị y của chuỗi. Đọc/ghi String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Trả về thứ tự của chuỗi. Đọc/ghi Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | Xác định mức độ chồng chập của thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ –100 % đến 100 %). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là phép chiếu của thuộc tính nhóm liên quan. Vì vậy thuộc tính này chỉ đọc. Để thay đổi giá trị, sử dụng thuộc tính ParentSeriesGroup.Overlap. Chỉ đọc SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Đại diện cho bố cục của nhãn danh mục cha. Chỉ áp dụng cho biểu đồ Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Trả về nhóm chuỗi cha. Chỉ đọc [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Xác định cách xác định các điểm dữ liệu nằm trong bánh hay thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là phép chiếu của thuộc tính nhóm liên quan. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitBy để đọc/ghi khi thay đổi giá trị. Chỉ đọc [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | Thông tin chia tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie với chia tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là phép chiếu của thuộc tính nhóm liên quan. Chỉ đọc [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | Xác định giá trị được dùng để quyết định các điểm dữ liệu nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là phép chiếu của thuộc tính nhóm liên quan. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitPosition để đọc/ghi khi thay đổi giá trị. Chỉ đọc Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Chỉ ra liệu chuỗi này có được vẽ trên trục giá trị thứ hai hay không. Đọc/ghi Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Đại diện cho phương pháp tứ phân vị. Chỉ áp dụng cho biểu đồ BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Đại diện cho mục legend liên quan đến chuỗi này. Chỉ đọc [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Xác định kích thước của bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 % đến 200 %). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha – đây là phép chiếu của thuộc tính nhóm liên quan. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.SecondPieSize để đọc/ghi khi thay đổi giá trị. Chỉ đọc UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Đại diện cho các đường kết nối. Chỉ áp dụng cho biểu đồ Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | Đại diện cho các điểm nội. Đúng nếu các điểm nội được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Đại diện cho các ký hiệu trung bình. Đúng nếu đường trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Đại diện cho các ký hiệu trung bình. Đúng nếu các ký hiệu trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Đại diện cho các điểm ngoại lệ. Đúng nếu các điểm ngoại lệ được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Đại diện cho việc làm mượt đường cong. Đúng nếu làm mượt đường cong được bật cho biểu đồ line hoặc scatter. Chỉ áp dụng cho biểu đồ line và scatter nối bằng đường. Đọc/ghi Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Tập hợp các đường xu hướng của chuỗi. Chỉ đọc [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Trả về kiểu của chuỗi này. Đọc/ ghi [`ChartType`](../charttype). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Trả về màu tự động của chuỗi dựa trên chỉ số chuỗi và kiểu biểu đồ. Màu này được dùng mặc định nếu FillType bằng NotDefined. |

### Xem thêm

* giao diện [IChartComponent](../ichartcomponent)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->