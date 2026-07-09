---
title: IAxis
second_title: Aspose.Sildes cho .NET Tham chiếu API
description: Bao bọc đối tượng đại diện cho trục của biểu đồ.
type: docs
weight: 1710
url: /vi/aspose.slides.charts/iaxis/
---
## Giao diện IAxis

Bao bọc đối tượng đại diện cho trục của biểu đồ.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Xác định đơn vị chính thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Xác định thang đo đơn vị chính thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Xác định giá trị tối đa thực tế trên trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Xác định đơn vị phụ thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Xác định thang đo đơn vị phụ thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Xác định giá trị tối thiểu thực tế trên trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Biểu thị loại tổng hợp của trục danh mục (phân nhóm). Áp dụng cho danh mục. Chỉ sử dụng với chuỗi Histogram hoặc HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Cho phép lấy giao diện IFormattedTextContainer cơ bản. Chỉ đọc [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Biểu thị liệu trục giá trị có cắt trục danh mục giữa các danh mục hay không. Thuộc tính này chỉ áp dụng cho trục danh mục và không áp dụng cho biểu đồ 3D. Đọc/ghi Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Xác định đơn vị thời gian nhỏ nhất được biểu thị trên trục ngày. Đọc/ghi [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Xác định độ rộng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. Áp dụng cho trục danh mục. Chỉ sử dụng với chuỗi Histogram hoặc HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Xác định loại trục danh mục. Đọc/ghi [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Biểu thị điểm trên trục nơi trục vuông góc cắt nó. Đọc/ghi Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Biểu thị CrossType trên trục đã chỉ định nơi trục khác cắt. Đọc/ghi [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Xác định giá trị tỷ lệ của các đơn vị hiển thị cho trục giá trị. Đọc/ghi [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Biểu thị định dạng của trục. Chỉ đọc [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Xác định liệu trục có tiêu đề hiển thị hay không. Đọc/ghi Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Chỉ ra liệu đơn vị chính của trục có được gán tự động hay không. Đọc/ghi Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Chỉ ra liệu giá trị tối đa có được gán tự động hay không. Đọc/ghi Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Chỉ ra liệu đơn vị phụ của trục có được gán tự động hay không. Đọc/ghi Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Chỉ ra liệu giá trị tối thiểu có được gán tự động hay không. Đọc/ghi Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Xác định giá trị bin tràn tự động. Nếu false: sử dụng thuộc tính OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Xác định giá trị khoảng cách nhãn tick tự động. Nếu false: sử dụng thuộc tính TickLabelSpacing. Đọc/ghi Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Xác định giá trị khoảng cách dấu tick tự động. Nếu false: sử dụng thuộc tính TickMarksSpacing. Đọc/ghi Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Xác định giá trị bin thiếu tự động. Nếu false: sử dụng thuộc tính UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Biểu thị liệu loại thang đo của trục giá trị có là logarit hay không. Đọc/ghi Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Chỉ ra liệu định dạng có được liên kết với dữ liệu nguồn hay không. Đọc/ghi Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Xác định liệu bin tràn có được áp dụng hay không. Sử dụng IsAutomaticOverflowBin và OverflowBin để điều chỉnh giá trị bin tràn. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Biểu thị liệu MS PowerPoint vẽ các điểm dữ liệu từ cuối đến đầu hay không. Đọc/ghi Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Xác định liệu bin thiếu có được áp dụng hay không. Sử dụng IsAutomaticUnderflowBin và UnderflowBin để điều chỉnh giá trị bin thiếu. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Biểu thị liệu trục có hiển thị hay không. Đọc/ghi Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Xác định khoảng cách của nhãn so với trục. Áp dụng cho trục danh mục hoặc ngày. Giá trị phải nằm trong khoảng 0% và 1000%. Đọc/ghi UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Biểu thị cơ số logarit. Giá trị mặc định là 10. Đọc/ghi Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Biểu thị định dạng đường lưới chính trên trục biểu đồ. Chỉ đọc [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Biểu thị loại dấu tick chính cho trục đã chỉ định. Đọc/ghi [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Biểu thị các đơn vị chính cho trục ngày hoặc giá trị. Đọc/ghi Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Biểu thị thang đo đơn vị chính cho trục ngày. Đọc/ghi [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Biểu thị giá trị tối đa trên trục giá trị. Đọc/ghi Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Biểu thị định dạng đường lưới phụ trên trục biểu đồ. Chỉ đọc [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Biểu thị loại dấu tick phụ cho trục đã chỉ định. Đọc/ghi [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Biểu thị các đơn vị phụ cho trục ngày hoặc giá trị. Đọc/ghi Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Biểu thị thang đo đơn vị chính cho trục ngày. Đọc/ghi [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Biểu thị giá trị tối thiểu trên trục giá trị. Đọc/ghi Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Biểu thị chuỗi định dạng cho Nhãn Trục. Đọc/ghi String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Xác định số lượng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. Áp dụng cho trục danh mục. Chỉ sử dụng với chuỗi Histogram hoặc HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Xác định giá trị tùy chỉnh cho bin tràn. Áp dụng khi thuộc tính IsAutomaticOverflowBin được đặt thành false và thuộc tính IsOverflowBin bằng true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Biểu thị vị trí của trục. Đọc/ghi [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Biểu thị liệu các đường lưới chính có được hiển thị hay không. Chỉ đọc Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Biểu thị liệu các đường lưới phụ có được hiển thị hay không. Chỉ đọc Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Biểu thị vị trí của nhãn dấu tick trên trục đã chỉ định. Đọc/ghi [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Biểu thị góc quay của nhãn tick. Đọc/ghi Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Xác định số lượng nhãn tick cần bỏ qua giữa các nhãn được vẽ. Đọc/ghi UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Xác định số lượng dấu tick sẽ bị bỏ qua trước khi vẽ dấu tiếp theo. Áp dụng cho trục danh mục hoặc chuỗi. Đọc/ghi UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Lấy tiêu đề của trục. Chỉ đọc [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Xác định giá trị tùy chỉnh cho bin thiếu. Áp dụng khi thuộc tính IsAutomaticUnderflowBin được đặt thành false và thuộc tính IsUnderflowBin bằng true. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Đặt thuộc tính IAxis.CategoryAxisType với một giá trị được xác định tự động dựa trên dữ liệu trục. |

### Xem thêm

* giao diện [IFormattedTextContainer](../iformattedtextcontainer)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->