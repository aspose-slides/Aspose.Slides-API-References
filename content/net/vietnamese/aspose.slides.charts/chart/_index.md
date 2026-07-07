---
title: Chart
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn một biểu đồ đồ họa trên một slide.
type: docs
weight: 1260
url: /vi/aspose.slides.charts/chart/
---
## Lớp Chart

Represents an graphic chart on a slide.

```csharp
public class Chart : GraphicalObject, IChart
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc đặt văn bản thay thế liên quan đến một shape. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan đến một shape. Đọc/ghi String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Cho phép lấy giao diện IFormattedTextContainer cơ bản. Chỉ đọc [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Cho phép lấy giao diện IThemeable cơ bản. Chỉ đọc [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Cung cấp quyền truy cập vào các trục biểu đồ. Chỉ đọc [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Trả về một đối tượng cho phép thay đổi định dạng của tường phía sau của biểu đồ 3D. Chỉ đọc [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính chỉ định cách một shape sẽ hiển thị trong chế độ đen và trắng. Đọc/ghi [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Trả về thông tin về dữ liệu liên kết hoặc nhúng liên quan đến một chart. Chỉ đọc [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Trả về bảng dữ liệu của một chart. Chỉ đọc [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Trả về hoặc đặt tiêu đề chart. Chỉ đọc [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số lượng điểm kết nối trên shape. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của shape. Chỉ đọc [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Trả về hoặc đặt cách vẽ các ô trống trên chart. Đọc/ghi [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính hiệu ứng. Chỉ đọc [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính tô màu. Chỉ đọc [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Trả về một đối tượng cho phép thay đổi định dạng của nền của biểu đồ 3D. Chỉ đọc [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về hoặc đặt các thuộc tính khung shape. Đọc/ghi [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Trả về các khóa của shape. Chỉ đọc [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Xác định xem chart có bảng dữ liệu hay không. Đọc/ghi Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Xác định xem chart có chú giải hay không. Đọc/ghi Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Chỉ định khu vực chart sẽ có các góc bo tròn. Đọc/ghi Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Xác định xem chart có tiêu đề hiển thị hay không. Đọc/ghi Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lấy hoặc đặt chiều cao của shape, đo bằng points. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định xem shape có bị ẩn hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho nhấp chuột. Đọc/ghi [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về trình quản lý siêu liên kết. Chỉ đọc [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột. Đọc/ghi [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lấy hoặc đặt tùy chọn 'Mark as decorative' option. Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định xem shape có được nhóm hay không. Chỉ đọc Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định xem shape là TextHolder_PPT hay không. Chỉ đọc Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Trả về hoặc đặt chú giải cho chart. Chỉ đọc [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính đường. Chỉ đọc [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc đặt tên của một shape. Không được null. Sử dụng chuỗi rỗng nếu cần. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về một định danh duy nhất có phạm vi slide, giữ cố định trong suốt vòng đời của shape và cho phép PowerPoint hoặc mã interop tham chiếu shape một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu shape được nhóm. Nếu không trả về null. Chỉ đọc [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về trình giữ chỗ cho một shape. Trả về null nếu shape không có trình giữ chỗ. Chỉ đọc [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Biểu thị khu vực vẽ của một chart. Chỉ đọc [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Xác định xem chỉ các ô hiển thị được vẽ hay không. False để vẽ cả ô hiển thị và ẩn. Đọc/ghi Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về bản trình bày cha của một slide. Chỉ đọc [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc đặt các thuộc tính khung shape thô. Đọc/ghi [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc đặt số độ shape được quay quanh trục z. Giá trị dương chỉ quay theo chiều kim đồng hồ; giá trị âm chỉ quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Trả về một phép quay 3D của chart. Chỉ đọc [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Trả về các khóa của shape. Chỉ đọc [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 thuộc tính) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Chỉ định nhãn dữ liệu trên mức tối đa của chart sẽ được hiển thị. Đọc/ghi Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Trả về một đối tượng cho phép thay đổi định dạng của tường bên của biểu đồ 3D. Chỉ đọc [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của một shape. Chỉ đọc [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Trả về hoặc đặt kiểu chart. Đọc/ghi [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Trả về định dạng văn bản chart. Thuộc tính không áp dụng cho các loại sau: Treemap, Sunburst, Waterfall, Histogram, Funnel,BoxAndWhisker. Chỉ đọc [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Trả về trình quản lý giao diện. Chỉ đọc [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3d cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính 3d. Chỉ đọc [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Trả về hoặc đặt loại chart. Đọc/ghi [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về một định danh nội bộ, có phạm vi presentation, dành cho add-in hoặc mã khác. Vì giá trị này có thể được gán lại bởi người dùng hoặc lập trình, không nên coi là khóa duy nhất cố định. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Chỉ định các shape được vẽ trên chart. Chỉ đọc [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lấy hoặc đặt chiều rộng của shape, đo bằng points. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lấy hoặc đặt tọa độ x của góc trên-trái shape, đo bằng points. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lấy hoặc đặt tọa độ y của góc trên-trái shape, đo bằng points. Đọc/ghi Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của một shape trong thứ tự z. Shapes[0] trả về shape ở cuối thứ tự z, và Shapes[Shapes.Count - 1] trả về shape ở phía trước của thứ tự z. Chỉ đọc Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một trình giữ chỗ mới nếu không có và đặt các thuộc tính trình giữ chỗ cho một đối tượng được chỉ định. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Trả về một giao diện chủ đề hiệu quả cho chart này. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một hình dạng trình giữ chỗ cơ bản (hình dạng từ bố cục và/hoặc slide chủ mà shape hiện tại kế thừa). Trả về null nếu shape hiện tại không được kế thừa. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về hình thu nhỏ của shape. Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về hình thu nhỏ của shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lấy giới hạn trực quan của shape được tính từ nội dung đã hiển thị. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Xác định rằng shape này không phải là một trình giữ chỗ. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Tính toán các giá trị thực của các phần tử chart. Các giá trị thực bao gồm vị trí của các phần tử thực hiện giao diện IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) và các giá trị trục thực (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung Shape dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung Shape dưới dạng tệp SVG. |

### Xem thêm

* lớp [GraphicalObject](../../aspose.slides/graphicalobject)
* giao diện [IChart](../ichart)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->