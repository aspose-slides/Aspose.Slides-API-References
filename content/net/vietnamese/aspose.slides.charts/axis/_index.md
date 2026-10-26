---
title: Axis
second_title: Aspose.Sildes cho Tham chiếu API .NET
description: Bao bọc đối tượng đại diện cho trục của biểu đồ.
type: docs
weight: 1180
url: /vi/aspose.slides.charts/axis/
---
## Axis lớp

Bao bọc đối tượng đại diện cho trục của biểu đồ.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Xác định đơn vị chính thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Xác định tỷ lệ đơn vị chính thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Xác định giá trị tối đa thực tế trên trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Xác định đơn vị phụ thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Xác định tỷ lệ đơn vị phụ thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Xác định giá trị tối thiểu thực tế trên trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Biểu diễn loại tổng hợp của trục danh mục (phân nhóm). Được áp dụng cho danh mục. Chỉ được sử dụng với chuỗi Histogram hoặc HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Biểu diễn liệu trục giá trị có cắt trục danh mục giữa các danh mục hay không. Thuộc tính này chỉ áp dụng cho các trục danh mục và không áp dụng cho biểu đồ 3-D. Đọc/ghi Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Xác định đơn vị thời gian nhỏ nhất được biểu diễn trên trục ngày. Đọc/ghi [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Xác định độ rộng phân nhóm khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. Được áp dụng cho các trục danh mục. Chỉ sử dụng với chuỗi Histogram hoặc HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Xác định loại trục danh mục. Đọc/ghi [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Trả về biểu đồ cha. Chỉ đọc [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Biểu diễn điểm trên trục nơi trục vuông góc cắt qua. Đọc/ghi Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Biểu diễn CrossType trên trục được chỉ định nơi trục khác cắt qua. Đọc/ghi [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Xác định giá trị tỷ lệ của các đơn vị hiển thị cho trục giá trị. Đọc/ghi [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Biểu diễn định dạng của trục. Chỉ đọc [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Xác định xem trục có tiêu đề hiển thị hay không. Đọc/ghi Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Cho biết liệu đơn vị chính của trục có được tự động gán hay không. Đọc/ghi Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Cho biết liệu giá trị tối đa có được tự động gán hay không. Đọc/ghi Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Cho biết liệu đơn vị phụ của trục có được tự động gán hay không. Đọc/ghi Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Cho biết liệu giá trị tối thiểu có được tự động gán hay không. Đọc/ghi Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Xác định giá trị thùng tràn tự động. Nếu false: sử dụng thuộc tính OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Xác định giá trị khoảng cách nhãn đánh dấu tự động. Nếu false: sử dụng thuộc tính TickLabelSpacing. Đọc/ghi Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Xác định giá trị khoảng cách dấu tick tự động. Nếu false: sử dụng thuộc tính TickMarksSpacing. Đọc/ghi Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Xác định giá trị thùng thiếu tự động. Nếu false: sử dụng thuộc tính UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Biểu diễn loại tỉ lệ của trục giá trị có phải là logarit hay không. Đọc/ghi Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Cho biết liệu định dạng có liên kết dữ liệu nguồn hay không. Đọc/ghi Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Xác định liệu thùng tràn có được áp dụng hay không. Sử dụng IsAutomaticOverflowBin và OverflowBin để điều chỉnh giá trị thùng tràn. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Biểu diễn liệu MS PowerPoint vẽ các điểm dữ liệu từ cuối lên đầu hay không. Đọc/ghi Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Xác định liệu thùng thiếu có được áp dụng hay không. Sử dụng IsAutomaticUnderflowBin và UnderflowBin để điều chỉnh giá trị thùng thiếu. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Biểu diễn liệu trục có hiển thị hay không. Đọc/ghi Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Xác định khoảng cách của nhãn so với trục. Được áp dụng cho trục danh mục hoặc ngày. Giá trị phải nằm trong khoảng từ 0% đến 1000%. Đọc/ghi UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Biểu diễn cơ số logarit. Giá trị mặc định là 10. Đọc/ghi Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Biểu diễn định dạng các đường lưới chính trên trục biểu đồ. Chỉ đọc [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Biểu diễn loại dấu tick chính cho trục được chỉ định. Đọc/ghi [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Biểu diễn các đơn vị chính cho trục ngày hoặc giá trị. Đọc/ghi Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Biểu diễn tỷ lệ đơn vị chính cho trục ngày. Đọc/ghi [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Biểu diễn giá trị tối đa trên trục giá trị. Đọc/ghi Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Biểu diễn định dạng các đường lưới phụ trên trục biểu đồ. Chỉ đọc [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Biểu diễn loại dấu tick phụ cho trục được chỉ định. Đọc/ghi [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Biểu diễn các đơn vị phụ cho trục ngày hoặc giá trị. Đọc/ghi Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Biểu diễn tỷ lệ đơn vị chính cho trục ngày. Đọc/ghi [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Biểu diễn giá trị tối thiểu trên trục giá trị. Đọc/ghi Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Biểu diễn chuỗi định dạng cho Nhãn trục. Đọc/ghi String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Xác định số lượng thùng khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. Được áp dụng cho các trục danh mục. Chỉ dùng với chuỗi Histogram hoặc HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Xác định giá trị tùy chỉnh của thùng tràn. Được áp dụng khi thuộc tính IsAutomaticOverflowBin được đặt thành false và thuộc tính IsOverflowBin bằng true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Biểu diễn vị trí của trục. Đọc/ghi [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Để ẩn đường lưới chính, đặt MajorGridLinesFormat.Line.FillFormat.FillType thành FillType.NoFill. Chỉ đọc Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Để ẩn đường lưới phụ, đặt MinorGridLinesFormat.Line.FillFormat.FillType thành FillType.NoFill. Chỉ đọc Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Biểu diễn định dạng của văn bản. Chỉ đọc [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Biểu diễn vị trí của nhãn dấu tick trên trục được chỉ định. Đọc/ghi [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Biểu diễn góc quay của nhãn tick. Đọc/ghi Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Xác định số lượng nhãn tick sẽ bỏ qua giữa các nhãn được vẽ. Được áp dụng cho trục danh mục hoặc chuỗi. Đọc/ghi UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Xác định số lượng dấu tick sẽ bỏ qua trước khi vẽ dấu tiếp theo. Được áp dụng cho trục danh mục hoặc chuỗi. Đọc/ghi UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Lấy tiêu đề của trục. Chỉ đọc [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Xác định giá trị tùy chỉnh của thùng thiếu. Được áp dụng khi thuộc tính IsAutomaticUnderflowBin được đặt thành false và thuộc tính IsUnderflowBin bằng true. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Đặt thuộc tính IAxis.CategoryAxisType với giá trị được xác định tự động dựa trên dữ liệu trục. |

### Xem thêm

* lớp [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* lớp [AxesManager](../axesmanager)
* giao diện [IAxis](../iaxis)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->