---
title: DataLabelFormat
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn các tùy chọn định dạng cho DataLabel.
type: docs
weight: 1570
url: /vi/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat lớp

Biểu diễn các tùy chọn định dạng cho DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Cho phép lấy giao diện IPresentationComponent cơ bản. Chỉ đọc [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Trả về biểu đồ. Chỉ đọc [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Biểu diễn định dạng của nhãn dữ liệu. Chỉ đọc [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Boolean đọc/ghi. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Biểu diễn chuỗi định dạng cho đối tượng DataLabels. String đọc/ghi. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Biểu diễn vị trí của nhãn dữ liệu. đọc/ghi [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Đặt hoặc trả về một Variant biểu diễn dấu phân cách được sử dụng cho nhãn dữ liệu trên biểu đồ. đọc/ghi String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Biểu diễn hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị kích thước bong bóng. False để ẩn. đọc/ghi Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Biểu diễn hành vi hiển thị tên danh mục của nhãn dữ liệu trên biểu đồ đã chỉ định. True để hiển thị tên danh mục cho các nhãn dữ liệu trên biểu đồ. False để ẩn. đọc/ghi Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Xác định liệu nhãn dữ liệu của biểu đồ đã chỉ định sẽ được hiển thị dưới dạng lời gọi dữ liệu hay là nhãn dữ liệu. Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelAsDataCallout cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelAsDataCallout của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ: "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" gây ra tất cả DataLabels[i].ShowLabelAsDataCallout bằng val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Biểu diễn hành vi hiển thị giá trị ô của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị ô. False để ẩn. đọc/ghi Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Biểu diễn hành vi hiển thị các đường dẫn của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị các đường dẫn. False để ẩn. đọc/ghi Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Biểu diễn hành vi hiển thị khóa chú giải của nhãn dữ liệu trên biểu đồ đã chỉ định. True nếu khóa chú giải của nhãn dữ liệu hiển thị. đọc/ghi Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Biểu diễn hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị phần trăm. False để ẩn. đọc/ghi Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Trả về hoặc đặt một Boolean để chỉ ra hành vi hiển thị tên chuỗi cho các nhãn dữ liệu trên biểu đồ. True để hiển thị tên chuỗi. False để ẩn. đọc/ghi Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Biểu diễn hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị phần trăm. False để ẩn. đọc/ghi Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Trả về định dạng văn bản của biểu đồ. Chỉ đọc [`IChartTextFormat`](../icharttextformat). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | So sánh với đối tượng được chỉ định. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Trả về mã băm. |

### Xem thêm

* lớp [PVIObject](../../aspose.slides/pviobject)
* giao diện [IDataLabelFormat](../idatalabelformat)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* bộ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->