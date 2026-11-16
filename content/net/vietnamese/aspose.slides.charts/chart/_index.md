---
title: Chart
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu thị một biểu đồ đồ họa trên một slide.
type: docs
weight: 1270
url: /vi/aspose.slides.charts/chart/
---
## Lớp Chart

Biểu thị một biểu đồ đồ họa trên một slide.

```csharp
public class Chart : GraphicalObject, IChart
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc đặt văn bản thay thế liên quan đến một hình dạng. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan đến một hình dạng. Đọc/ghi String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Cho phép lấy giao diện IFormattedTextContainer cơ bản. Chỉ-đọc [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Cho phép lấy giao diện IThemeable cơ bản. Chỉ-đọc [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Cung cấp quyền truy cập vào các trục của biểu đồ. Chỉ-đọc [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Trả về một đối tượng cho phép thay đổi định dạng của tường sau của biểu đồ 3D. Chỉ-đọc [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính chỉ định cách một hình dạng sẽ được hiển thị ở chế độ đen-trắng. Đọc/ghi [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Trả về thông tin về dữ liệu được liên kết hoặc nhúng với biểu đồ. Chỉ-đọc [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Trả về bảng dữ liệu của biểu đồ. Chỉ-đọc [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Trả về hoặc đặt tiêu đề của biểu đồ. Chỉ-đọc [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số lượng điểm kết nối trên hình dạng. Chỉ-đọc Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của hình dạng. Chỉ-đọc [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Trả về hoặc đặt cách vẽ các ô trống trên biểu đồ. Đọc/ghi [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho hình dạng. Lưu ý: có thể trả về null đối với một số loại hình dạng không có thuộc tính hiệu ứng. Chỉ-đọc [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho hình dạng. Lưu ý: có thể trả về null đối với một số loại hình dạng không có thuộc tính tô màu. Chỉ-đọc [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Trả về một đối tượng cho phép thay đổi định dạng của sàn của biểu đồ 3D. Chỉ-đọc [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về hoặc đặt các thuộc tính khung của hình dạng. Đọc/ghi [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Trả về các khóa của hình dạng. Chỉ-đọc [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Xác định liệu biểu đồ có bảng dữ liệu hay không. Đọc/ghi Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Xác định liệu biểu đồ có chú giải hay không. Đọc/ghi Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Chỉ định khu vực biểu đồ sẽ có góc bo tròn. Đọc/ghi Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Xác định liệu biểu đồ có tiêu đề hiển thị hay không. Đọc/ghi Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lấy hoặc đặt chiều cao của hình dạng, tính bằng điểm. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định liệu hình dạng có bị ẩn hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho cú nhấp chuột. Đọc/ghi [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về trình quản lý siêu liên kết. Chỉ-đọc [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột qua. Đọc/ghi [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lấy hoặc đặt tùy chọn “Đánh dấu là trang trí”. Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định liệu hình dạng có được nhóm hay không. Chỉ-đọc Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định liệu hình dạng là TextHolder_PPT hay không. Chỉ-đọc Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Trả về hoặc đặt một chú giải cho biểu đồ. Chỉ-đọc [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho hình dạng. Lưu ý: có thể trả về null đối với một số loại hình dạng không có thuộc tính đường. Chỉ-đọc [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc đặt tên của hình dạng. Không được để null. Sử dụng chuỗi rỗng nếu cần. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về một định danh duy nhất trong slide, không thay đổi trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ-đọc UInt32. Xem thêm [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Ngược lại trả về null. Chỉ-đọc [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về placeholder cho hình dạng. Trả về null nếu hình dạng không có placeholder. Chỉ-đọc [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Đại diện cho khu vực vẽ của biểu đồ. Chỉ-đọc [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Xác định liệu chỉ các ô hiển thị mới được vẽ. Đặt false để vẽ cả ô hiển thị và ẩn. Đọc/ghi Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về bản trình bày cha của slide. Chỉ-đọc [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc đặt các thuộc tính khung thô của hình dạng. Đọc/ghi [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc đặt số độ mà hình dạng được quay quanh trục z. Giá trị dương chỉ quay theo chiều kim đồng hồ; giá trị âm chỉ quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Trả về xoay 3D của biểu đồ. Chỉ-đọc [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Trả về các khóa của hình dạng. Chỉ-đọc [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 thuộc tính) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Chỉ định nhãn dữ liệu trên mức tối đa của biểu đồ sẽ được hiển thị. Đọc/ghi Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Trả về một đối tượng cho phép thay đổi định dạng của tường bên của biểu đồ 3D. Chỉ-đọc [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của một hình dạng. Chỉ-đọc [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Trả về hoặc đặt kiểu biểu đồ. Đọc/ghi [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Trả về định dạng văn bản của biểu đồ. Thuộc tính không áp dụng cho các loại sau: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Chỉ-đọc [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Trả về trình quản lý theme. Chỉ-đọc [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho hình dạng. Lưu ý: có thể trả về null đối với một số loại hình dạng không có thuộc tính 3D. Chỉ-đọc [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Trả về hoặc đặt kiểu biểu đồ. Đọc/ghi [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về một định danh nội bộ, scoped theo bản trình bày, dành cho add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, không nên coi là khóa duy nhất lâu dài. Chỉ-đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Chỉ định các hình dạng được vẽ phía trên biểu đồ. Chỉ-đọc [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lấy hoặc đặt chiều rộng của hình dạng, tính bằng điểm. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, tính bằng điểm. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, tính bằng điểm. Đọc/ghi Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của hình dạng trong thứ tự z. Shapes[0] trả về hình dạng ở cuối z-order, và Shapes[Shapes.Count - 1] trả về hình dạng ở đầu. Chỉ-đọc Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một placeholder mới nếu không có và đặt các thuộc tính placeholder thành một placeholder được chỉ định. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Trả về một theme hiệu quả cho biểu đồ này. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một hình placeholder cơ bản (hình từ bố cục và/hoặc slide mẫu mà hình hiện tại kế thừa). Trả về null nếu hình hiện tại không được kế thừa. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về thumbnail của hình dạng. Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn thumbnail. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về thumbnail của hình dạng. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lấy giới hạn hình ảnh của hình dạng được tính từ nội dung đã render. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Xác định rằng hình dạng này không phải là placeholder. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Tính toán các giá trị thực tế của các yếu tố biểu đồ. Các giá trị thực tế bao gồm vị trí của các yếu tố thực hiện giao diện IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) và các giá trị trục thực tế (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |

### Xem thêm

* lớp [GraphicalObject](../../aspose.slides/graphicalobject)
* giao diện [IChart](../ichart)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->