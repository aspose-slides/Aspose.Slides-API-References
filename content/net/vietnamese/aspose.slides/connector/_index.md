---
title: Connector
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn một connector.
type: docs
weight: 2670
url: /vi/aspose.slides/connector/
---
## Connector lớp

Biểu diễn một connector.

```csharp
public class Connector : GeometryShape, IConnector
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Trả về một tập hợp các giá trị điều chỉnh của shape. Chỉ đọc [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc đặt văn bản thay thế liên kết với một shape. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc đặt tiêu đề của văn bản thay thế liên kết với một shape. Đọc/ghi String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính chỉ định cách shape sẽ được hiển thị ở chế độ đen-trắng. Đọc/ghi [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số lượng vị trí kết nối trên shape. Chỉ đọc Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | Trả về các khóa của connector. Chỉ đọc [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của shape. Chỉ đọc [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính effect. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | Trả về hoặc đặt shape để gắn đầu cuối của connector vào. Đọc/ghi [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | Trả về hoặc đặt chỉ mục của vị trí kết nối cho shape cuối. Đọc/ghi UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính fill. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về các thuộc tính khung shape. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lấy hoặc đặt chiều cao của shape, đo bằng point. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định xem shape có bị ẩn hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc đặt hyperlink được định nghĩa cho nhấp chuột. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về trình quản lý hyperlink. Chỉ đọc [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc đặt hyperlink được định nghĩa cho di chuột qua. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lấy hoặc đặt tùy chọn 'Mark as decorative' Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định xem shape có được nhóm không. Chỉ đọc Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định xem shape là TextHolder_PPT hay không. Chỉ đọc Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính line. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc đặt tên của một shape. Không được null. Sử dụng chuỗi trống nếu cần. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về một định danh duy nhất trong phạm vi slide, không thay đổi trong suốt vòng đời của shape và cho phép PowerPoint hoặc mã interop tham chiếu shape một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu shape được nhóm. Nếu không, trả về null. Chỉ đọc [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về placeholder cho một shape. Trả về null nếu shape không có placeholder. Chỉ đọc [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về bản trình bày cha của một slide. Chỉ đọc [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc đặt các thuộc tính thô của khung shape. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc đặt số độ mà shape được quay quanh trục z. Giá trị dương chỉ quay theo chiều kim đồng hồ; giá trị âm chỉ quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | Trả về các khóa của shape. Chỉ đọc [`IConnectorLock`](../iconnectorlock). (2 thuộc tính) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Trả về đối tượng style của shape. Chỉ đọc [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | Trả về hoặc đặt loại AutoShape. Đọc/ghi [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của một shape. Chỉ đọc [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | Trả về hoặc đặt shape để gắn đầu đầu của connector vào. Đọc/ghi [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | Trả về hoặc đặt chỉ mục của vị trí kết nối cho shape bắt đầu. Đọc/ghi UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3d cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính 3d. Chỉ đọc [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về một định danh nội bộ, giới hạn trong presentation, dành cho add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, không nên coi là khóa duy nhất lâu dài. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lấy hoặc đặt chiều rộng của shape, đo bằng point. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lấy hoặc đặt tọa độ x của góc trên-trái của shape, đo bằng point. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lấy hoặc đặt tọa độ y của góc trên-trái của shape, đo bằng point. Đọc/ghi Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của một shape trong thứ tự z. Shapes[0] trả về shape ở phía sau cùng của thứ tự z, và Shapes[Shapes.Count - 1] trả về shape ở phía trước cùng của thứ tự z. Chỉ đọc Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một placeholder mới nếu không có và đặt các thuộc tính placeholder cho một placeholder chỉ định. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Tạo và trả về mảng các phần tử của shape. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một shape placeholder cơ bản (shape từ layout và/hoặc master slide mà shape hiện tại kế thừa). Trả về null nếu shape hiện tại không được kế thừa. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Trả về bản sao của đường dẫn của shape hình học. Các tọa độ tính tương đối so với góc trên-trái của shape. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về hình thu nhỏ của shape. Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn hình thu nhỏ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về hình thu nhỏ của shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lấy giới hạn trực quan của shape được tính từ nội dung đã render. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Xác định rằng shape này không phải là placeholder. |
| [Reroute](../../aspose.slides/connector/reroute)() | Định tuyến lại connector để nó lấy đường ngắn nhất có thể giữa các shape mà nó kết nối. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Cập nhật hình học của shape từ đối tượng [`IGeometryPath`](../igeometrypath). Các tọa độ phải tương đối so với góc trên-trái của shape. Thay đổi loại của shape ([`ShapeType`](../geometryshape/shapetype)) thành Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Cập nhật hình học của shape từ mảng [`IGeometryPath`](../igeometrypath). Các tọa độ phải tương đối so với góc trên-trái của shape. Thay đổi loại của shape ([`ShapeType`](../geometryshape/shapetype)) thành Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung của Shape dưới dạng file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung của Shape dưới dạng file SVG. |

### Xem thêm

* lớp [GeometryShape](../geometryshape)
* giao diện [IConnector](../iconnector)
* không gian tên [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->