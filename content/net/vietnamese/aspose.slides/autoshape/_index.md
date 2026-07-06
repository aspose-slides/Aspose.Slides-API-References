---
title: AutoShape
second_title: Aspose.Sildes cho .NET Tham chiếu API
description: Biểu diễn một AutoShape.
type: docs
weight: 900
url: /vi/aspose.slides/autoshape/
---
## Lớp AutoShape

Biểu diễn một AutoShape.

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Trả về một tập hợp các giá trị điều chỉnh của shape. Chỉ đọc [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc đặt văn bản thay thế liên kết với một shape. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc đặt tiêu đề của văn bản thay thế liên kết với một shape. Đọc/ghi String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | Trả về các khóa của autoshape. Chỉ đọc [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính chỉ định cách một shape sẽ hiển thị trong chế độ đen-trắng. Đọc/ghi [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số lượng điểm kết nối trên shape. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của shape. Chỉ đọc [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính hiệu ứng. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính tô màu. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về hoặc đặt các thuộc tính khung shape. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lấy hoặc đặt chiều cao của shape, đo bằng điểm. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định xem shape có bị ẩn hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho nhấp chuột. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về trình quản lý siêu liên kết. Chỉ đọc [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột qua. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lấy hoặc đặt tùy chọn 'Mark as decorative' Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định xem shape có được nhóm không. Chỉ đọc Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | Chỉ định nếu shape là một text box. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định xem shape là TextHolder_PPT hay không. Chỉ đọc Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính đường. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc đặt tên của một shape. Không được null. Sử dụng chuỗi rỗng nếu cần. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về một định danh duy nhất có phạm vi slide, không thay đổi trong vòng đời của shape và cho phép PowerPoint hoặc mã interop tham chiếu shape một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu shape được nhóm. Nếu không, trả về null. Chỉ đọc [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về placeholder cho một shape. Trả về null nếu shape không có placeholder. Chỉ đọc [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về presentation cha của một slide. Chỉ đọc [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc đặt các thuộc tính khung shape thô. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc đặt số độ mà shape được quay quanh trục z. Giá trị dương chỉ chiều quay theo kim đồng hồ; giá trị âm chỉ chiều quay ngược lại. Đọc/ghi Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | Trả về các khóa của shape. Chỉ đọc [`IAutoShapeLock`](../iautoshapelock). (2 thuộc tính) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Trả về đối tượng style của shape. Chỉ đọc [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Trả về hoặc đặt loại geometry preset. Lưu ý: khi giá trị thay đổi, tất cả các giá trị điều chỉnh sẽ được đặt lại về mặc định. Đọc/ghi [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của một shape. Chỉ đọc [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | Trả về đối tượng TextFrame cho AutoShape. Chỉ đọc [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính 3D. Chỉ đọc [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về một định danh nội bộ, có phạm vi presentation, dành cho các add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình gán lại, nó không nên được coi là khóa duy nhất lâu dài. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | Xác định xem autoshape này có nên được tô bằng nền slide thay vì sử dụng style hoặc fill format không. Đọc/ghi Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lấy hoặc đặt chiều rộng của shape, đo bằng điểm. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lấy hoặc đặt tọa độ x của góc trên-trái của shape, đo bằng điểm. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lấy hoặc đặt tọa độ y của góc trên-trái của shape, đo bằng điểm. Đọc/ghi Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của một shape trong thứ tự z. Shapes[0] trả về shape ở cuối cùng của thứ tự z, và Shapes[Shapes.Count - 1] trả về shape ở phía trước nhất của thứ tự z. Chỉ đọc Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một placeholder mới nếu chưa có và đặt các thuộc tính placeholder thành một placeholder được chỉ định. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | Thêm một TextFrame mới vào một shape. Nếu shape đã có TextFrame thì chỉ thay đổi văn bản của nó. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Tạo và trả về một mảng các phần tử của shape. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một shape placeholder cơ bản (shape từ layout và/hoặc master slide mà shape hiện tại kế thừa). Trả về null nếu shape hiện tại không được kế thừa. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Trả về bản sao của đường dẫn của shape geometry. Các tọa độ tính từ góc trên-trái của shape. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về hình thu nhỏ của shape. Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho vùng giới hạn hình thu nhỏ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về hình thu nhỏ của shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lấy vùng giới hạn trực quan của shape được tính từ nội dung đã render. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Xác định rằng shape này không phải là một placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Cập nhật geometry của shape từ đối tượng [`IGeometryPath`](../igeometrypath). Các tọa độ phải tính từ góc trên-trái của shape. Thay đổi loại của shape ([`ShapeType`](../geometryshape/shapetype)) thành Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Cập nhật geometry của shape từ mảng [`IGeometryPath`](../igeometrypath). Các tọa độ phải tính từ góc trên-trái của shape. Thay đổi loại của shape ([`ShapeType`](../geometryshape/shapetype)) thành Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung của Shape thành tệp SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung của Shape thành tệp SVG. |

### Xem thêm

* lớp [GeometryShape](../geometryshape)
* giao diện [IAutoShape](../iautoshape)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập tin lắp ráp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->