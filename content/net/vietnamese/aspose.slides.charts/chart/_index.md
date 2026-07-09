---
title: Chart
second_title: Aspose.Sildes cho .NET Tham khảo API
description: Biểu diễn một biểu đồ đồ họa trên một slide.
type: docs
weight: 1260
url: /vi/aspose.slides.charts/chart/
---
## Lớp Chart

Biểu diễn một biểu đồ đồ họa trên một slide.

```csharp
public class Chart : GraphicalObject, IChart
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc thiết lập văn bản thay thế liên kết với một shape. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc thiết lập tiêu đề của văn bản thay thế liên kết với một shape. Đọc/ghi String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Cho phép lấy giao diện IFormattedTextContainer cơ bản. Chỉ đọc [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Cho phép lấy giao diện IThemeable cơ bản. Chỉ đọc [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Cung cấp truy cập tới các trục của biểu đồ. Chỉ đọc [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Trả về một đối tượng cho phép thay đổi định dạng tường phía sau của biểu đồ 3D. Chỉ đọc [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính xác định cách shape sẽ hiển thị ở chế độ đen-trắng. Đọc/ghi [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Trả về thông tin về dữ liệu đã liên kết hoặc nhúng liên quan tới biểu đồ. Chỉ đọc [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Trả về bảng dữ liệu của biểu đồ. Chỉ đọc [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Trả về hoặc thiết lập tiêu đề biểu đồ. Chỉ đọc [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số lượng điểm kết nối trên shape. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của shape. Chỉ đọc [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Trả về hoặc thiết lập cách vẽ các ô trống trên biểu đồ. Đọc/ghi [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính hiệu ứng. Chỉ đọc [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính tô màu. Chỉ đọc [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Trả về một đối tượng cho phép thay đổi định dạng mặt sàn của biểu đồ 3D. Chỉ đọc [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về hoặc thiết lập các thuộc tính khung shape. Đọc/ghi [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Trả về các khóa của shape. Chỉ đọc [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Xác định liệu biểu đồ có bảng dữ liệu hay không. Đọc/ghi Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Xác định liệu biểu đồ có chú giải hay không. Đọc/ghi Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Xác định khu vực biểu đồ sẽ có các góc bo tròn. Đọc/ghi Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Xác định liệu biểu đồ có tiêu đề hiển thị hay không. Đọc/ghi Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lấy hoặc thiết lập chiều cao của shape, đo bằng point. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định liệu shape có bị ẩn hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc thiết lập siêu liên kết được định nghĩa cho cú nhấp chuột. Đọc/ghi [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về quản lý siêu liên kết. Chỉ đọc [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc thiết lập siêu liên kết được định nghĩa cho chuột di chuột qua. Đọc/ghi [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lấy hoặc thiết lập tùy chọn 'Đánh dấu là trang trí'. Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định liệu shape có được nhóm không. Chỉ đọc Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định liệu shape là TextHolder_PPT hay không. Chỉ đọc Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Trả về hoặc thiết lập chú giải cho biểu đồ. Chỉ đọc [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính đường. Chỉ đọc [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc thiết lập tên của shape. Phải không null. Sử dụng giá trị chuỗi rỗng nếu cần. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về một định danh duy nhất theo phạm vi slide, cố định trong suốt vòng đời của shape và cho phép PowerPoint hoặc mã interop tham chiếu shape một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu shape được nhóm. Nếu không, trả về null. Chỉ đọc [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về placeholder cho shape. Trả về null nếu shape không có placeholder. Chỉ đọc [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Biểu diễn khu vực vẽ của biểu đồ. Chỉ đọc [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Xác định liệu chỉ các ô hiển thị được vẽ. Đặt false để vẽ cả ô hiển thị và ô ẩn. Đọc/ghi Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về bản trình bày cha của slide. Chỉ đọc [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc thiết lập các thuộc tính khung raw shape. Đọc/ghi [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc thiết lập số độ mà shape được quay quanh trục z. Giá trị dương cho biết quay theo chiều kim đồng hồ; giá trị âm cho biết quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Trả về một phép quay 3D của biểu đồ. Chỉ đọc [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Trả về các khóa của shape. Chỉ đọc [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 thuộc tính) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Xác định nhãn dữ liệu trên mức tối đa của biểu đồ sẽ được hiển thị. Đọc/ghi Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Trả về một đối tượng cho phép thay đổi định dạng tường bên của biểu đồ 3D. Chỉ đọc [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của shape. Chỉ đọc [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Trả về hoặc thiết lập kiểu biểu đồ. Đọc/ghi [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Trả về định dạng văn bản của biểu đồ. Thuộc tính này không áp dụng cho các loại sau: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Chỉ đọc [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Trả về quản lý theme. Chỉ đọc [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3d cho shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính 3d. Chỉ đọc [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Trả về hoặc thiết lập loại biểu đồ. Đọc/ghi [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về một định danh nội bộ theo phạm vi presentation, dự định cho các add-in hoặc mã khác sử dụng. Vì giá trị này có thể được gán lại bởi người dùng hoặc chương trình, không nên coi là khóa duy nhất kéo dài. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Xác định các shape được vẽ trên biểu đồ. Chỉ đọc [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lấy hoặc thiết lập chiều rộng của shape, đo bằng point. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lấy hoặc thiết lập tọa độ x của góc trên trái của shape, đo bằng point. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lấy hoặc thiết lập tọa độ y của góc trên trái của shape, đo bằng point. Đọc/ghi Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của shape trong thứ tự z. Shapes[0] trả về shape ở cuối của thứ tự z, và Shapes[Shapes.Count - 1] trả về shape ở đầu của thứ tự z. Chỉ đọc Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một placeholder mới nếu không có và thiết lập các thuộc tính placeholder cho một placeholder được chỉ định. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Trả về theme hiệu quả cho biểu đồ này. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một shape placeholder cơ bản (shape từ bố cục và/hoặc slide master mà shape hiện tại kế thừa). Trả về null nếu shape hiện tại không được kế thừa. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về thumbnail của shape. Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho các bounds của thumbnail. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về thumbnail của shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lấy giới hạn hình ảnh của shape được tính dựa trên nội dung đã render. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Xác định rằng shape này không phải là placeholder. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Tính toán các giá trị thực của các phần tử biểu đồ. Các giá trị thực bao gồm vị trí của các phần tử thực thi giao diện IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) và các giá trị trục thực (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung của Shape thành tệp SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung của Shape thành tệp SVG. |

### Xem thêm

* lớp [GraphicalObject](../../aspose.slides/graphicalobject)
* giao diện [IChart](../ichart)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->