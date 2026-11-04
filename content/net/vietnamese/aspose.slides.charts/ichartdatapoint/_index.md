---
title: IChartDataPoint
second_title: Aspose.Sildes cho Tham chiếu API .NET
description: Biểu diễn điểm dữ liệu của series.
type: docs
weight: 1840
url: /vi/aspose.slides.charts/ichartdatapoint/
---
## Giao diện IChartDataPoint

Biểu diễn điểm dữ liệu của series.

```csharp
public interface IChartDataPoint : IActualLayout
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | Trả về giao diện IActualLayout. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | Lấy kích thước bong bóng của một điểm dữ liệu biểu đồ. Chỉ đọc [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | Lấy kích thước bong bóng đã lưu trong bộ nhớ cache của một điểm dữ liệu biểu đồ. Chỉ đọc [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | Lấy giá trị đã lưu trong bộ nhớ cache của một điểm dữ liệu biểu đồ. Chỉ đọc [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | Lấy giá trị X đã lưu trong bộ nhớ cache của một điểm dữ liệu biểu đồ. Chỉ đọc [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | Lấy giá trị Y đã lưu trong bộ nhớ cache của một điểm dữ liệu biểu đồ. Chỉ đọc [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | Lấy giá trị màu của một điểm dữ liệu biểu đồ. Được sử dụng với biểu đồ Bản đồ. Chỉ đọc [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | Trả về container của các cấp độ điểm dữ liệu. Áp dụng cho series Treeamp và Sunburst. Chỉ mục các cấp độ điểm dữ liệu bắt đầu từ 0. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | Đại diện cho giá trị thanh lỗi của series trong trường hợp kiểu giá trị Custom. Chỉ đọc [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | Xác định khoảng cách di chuyển của điểm dữ liệu so với trung tâm của bánh. Đọc/ghi Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | Đại diện cho các thuộc tính định dạng. Đọc/ghi [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | Xác định tập hợp con của cha mà điểm dữ liệu này áp dụng. Đọc UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | Xác định điểm dữ liệu sẽ đảo ngược màu nếu giá trị là âm. Đọc/ghi Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | Xác định các bong bóng có hiệu ứng 3D được áp dụng. Đọc/ghi Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | Đại diện cho nhãn của điểm dữ liệu biểu đồ. Chỉ đọc [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | Xác định một dấu dữ liệu. Chỉ đọc [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | Thuộc tính của mục chú giải tương ứng trong trường hợp loại biểu đồ thuộc danh sách này: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Chỉ đọc [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | Đặt điểm dữ liệu làm tổng. Chỉ áp dụng cho loại series Waterfall. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | Lấy giá trị kích thước của một điểm dữ liệu biểu đồ. Được sử dụng với biểu đồ Treemap và Sunburst. Chỉ đọc [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | Lấy giá trị của một điểm dữ liệu biểu đồ. Chỉ đọc [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | Lấy giá trị x của một điểm dữ liệu biểu đồ. Chỉ đọc [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | Lấy giá trị y của một điểm dữ liệu biểu đồ. Chỉ đọc [`IDoubleChartValue`](../idoublechartvalue). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | Trả về một màu tự động của điểm dữ liệu dựa trên chỉ mục series, chỉ mục điểm dữ liệu, thuộc tính ParentSeriesGroup.IsColorVaried và kiểu biểu đồ. Màu này được sử dụng mặc định nếu FillType bằng NotDefined. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | Xóa DataPoint khỏi series biểu đồ. |

### Xem thêm

* giao diện [IActualLayout](../iactuallayout)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->