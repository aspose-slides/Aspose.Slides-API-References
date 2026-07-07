---
title: IAxis
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Bao bọc đối tượng đại diện cho trục của biểu đồ.
type: docs
weight: 1710
url: /vi/aspose.slides.charts/iaxis/
---
## IAxis giao diện

Bao bọc đối tượng đại diện cho trục của biểu đồ.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Thuộc tính

| Name | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Xác định đơn vị chính thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Xác định tỉ lệ đơn vị chính thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Xác định giá trị tối đa thực tế trên trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Xác định đơn vị phụ thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Xác định tỉ lệ đơn vị phụ thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Xác định giá trị tối thiểu thực tế trên trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Đại diện cho kiểu tổng hợp của trục danh mục (phân nhóm). Áp dụng cho danh mục. Chỉ dùng với chuỗi Histogram hoặc HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Cho phép lấy giao diện cơ sở IFormattedTextContainer. Chỉ đọc [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Đại diện cho việc trục giá trị cắt qua trục danh mục giữa các danh mục. Thuộc tính này chỉ áp dụng cho trục danh mục và không áp dụng cho biểu đồ 3-D. Đọc/ghi Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Xác định đơn vị thời gian nhỏ nhất được biểu diễn trên trục ngày. Đọc/ghi [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Xác định độ rộng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. Áp dụng cho trục danh mục. Chỉ dùng với chuỗi Histogram hoặc HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Xác định kiểu của trục danh mục. Đọc/ghi [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Đại diện cho điểm trên trục mà trục vuông góc cắt qua. Đọc/ghi Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Đại diện cho CrossType trên trục đã chỉ định nơi trục khác cắt qua. Đọc/ghi [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Xác định giá trị tỉ lệ hiển thị đơn vị cho trục giá trị. Đọc/ghi [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Đại diện cho định dạng của trục. Chỉ đọc [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Xác định liệu trục có tiêu đề hiển thị hay không. Đọc/ghi Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Cho biết liệu đơn vị chính của trục có được gán tự động hay không. Đọc/ghi Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Cho biết liệu giá trị tối đa có được gán tự động hay không. Đọc/ghi Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Cho biết liệu đơn vị phụ của trục có được gán tự động hay không. Đọc/ghi Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Cho biết liệu giá trị tối thiểu có được gán tự động hay không. Đọc/ghi Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Xác định giá trị bin tràn tự động. Nếu false: sử dụng thuộc tính OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Xác định giá trị khoảng cách nhãn tick tự động. Nếu false: sử dụng thuộc tính TickLabelSpacing. Đọc/ghi Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Xác định giá trị khoảng cách dấu tick tự động. Nếu false: sử dụng thuộc tính TickMarksSpacing. Đọc/ghi Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Xác định giá trị bin thiếu tự động. Nếu false: sử dụng thuộc tính UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Đại diện cho việc trục giá trị có kiểu tỉ lệ logarit hay không. Đọc/ghi Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Cho biết liệu định dạng có liên kết với dữ liệu nguồn hay không. Đọc/ghi Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Xác định liệu bin tràn có được áp dụng hay không. Sử dụng IsAutomaticOverflowBin và OverflowBin để điều chỉnh giá trị bin tràn. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Đại diện cho việc MS PowerPoint vẽ các điểm dữ liệu từ cuối lên đầu. Đọc/ghi Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Xác định liệu bin thiếu có được áp dụng hay không. Sử dụng IsAutomaticUnderflowBin và UnderflowBin để điều chỉnh giá trị bin thiếu. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Đại diện cho việc trục có hiển thị hay không. Đọc/ghi Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Xác định khoảng cách của nhãn so với trục. Áp dụng cho trục danh mục hoặc ngày. Giá trị phải nằm trong khoảng 0% và 1000%. Đọc/ghi UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Đại diện cho cơ số logarit. Giá trị mặc định là 10. Đọc/ghi Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Đại diện cho định dạng lưới chính trên trục biểu đồ. Chỉ đọc [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Đại diện cho kiểu dấu tick chính cho trục đã chỉ định. Đọc/ghi [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Đại diện cho các đơn vị chính cho trục ngày hoặc giá trị. Đọc/ghi Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Đại diện cho tỉ lệ đơn vị chính cho trục ngày. Đọc/ghi [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Đại diện cho giá trị tối đa trên trục giá trị. Đọc/ghi Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Đại diện cho định dạng lưới phụ trên trục biểu đồ. Chỉ đọc [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Đại diện cho kiểu dấu tick phụ cho trục đã chỉ định. Đọc/ghi [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Đại diện cho các đơn vị phụ cho trục ngày hoặc giá trị. Đọc/ghi Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Đại diện cho tỉ lệ đơn vị chính cho trục ngày. Đọc/ghi [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Đại diện cho giá trị tối thiểu trên trục giá trị. Đọc/ghi Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Đại diện cho chuỗi định dạng cho Nhãn Trục. Đọc/ghi String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Xác định số lượng bin khi thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. Áp dụng cho trục danh mục. Chỉ dùng với chuỗi Histogram hoặc HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Xác định giá trị tùy chỉnh cho bin tràn. Áp dụng khi IsAutomaticOverflowBin được đặt thành false và IsOverflowBin bằng true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Đại diện cho vị trí của trục. Đọc/ghi [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Đại diện cho việc lưới chính có hiển thị hay không. Chỉ đọc Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Đại diện cho việc lưới phụ có hiển thị hay không. Chỉ đọc Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Đại diện cho vị trí của nhãn dấu tick trên trục đã chỉ định. Đọc/ghi [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Đại diện cho góc quay của nhãn tick. Đọc/ghi Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Xác định số lượng nhãn tick sẽ bỏ qua giữa các nhãn được vẽ. Đọc/ghi UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Xác định số lượng dấu tick sẽ bỏ qua trước khi vẽ dấu tiếp theo. Áp dụng cho trục danh mục hoặc series. Đọc/ghi UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Lấy tiêu đề của trục. Chỉ đọc [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Xác định giá trị tùy chỉnh cho bin thiếu. Áp dụng khi IsAutomaticUnderflowBin được đặt thành false và IsUnderflowBin bằng true. |

## Phương thức

| Name | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Đặt thuộc tính IAxis.CategoryAxisType với giá trị được xác định tự động dựa trên dữ liệu trục. |

### Xem thêm

* giao diện [IFormattedTextContainer](../iformattedtextcontainer)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->