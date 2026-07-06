---
title: GeometryShape
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Đại diện cho lớp cha của tất cả các hình dạng hình học.
type: docs
weight: 4970
url: /vi/aspose.slides/geometryshape/
---
## GeometryShape lớp

Represents the parent class for all geometric shapes.

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Trả về một bộ sưu tập các giá trị điều chỉnh của hình dạng. Chỉ đọc [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc đặt văn bản thay thế liên kết với một hình dạng. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc đặt tiêu đề của văn bản thay thế liên kết với một hình dạng. Đọc/ghi String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính này chỉ định cách một hình dạng sẽ được hiển thị ở chế độ đen-trắng. Đọc/ghi [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số lượng điểm kết nối trên hình dạng. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của hình dạng. Chỉ đọc [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho một hình dạng. Lưu ý: có thể trả về null đối với một số loại hình dạng không có thuộc tính hiệu ứng. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng. Lưu ý: có thể trả về null đối với một số loại hình dạng không có thuộc tính tô màu. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về hoặc đặt các thuộc tính khung của hình dạng. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lấy hoặc đặt chiều cao của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định xem hình dạng có bị ẩn hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho nhấp chuột. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về trình quản lý siêu liên kết. Chỉ đọc [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột qua. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'. Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định xem hình dạng có được nhóm hay không. Chỉ đọc Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định xem hình dạng có phải là TextHolder_PPT hay không. Chỉ đọc Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng. Lưu ý: có thể trả về null đối với một số loại hình dạng không có thuộc tính đường. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc đặt tên của một hình dạng. Không được null. Sử dụng chuỗi rỗng nếu cần. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về một định danh duy nhất trong phạm vi slide, không thay đổi trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không, trả về null. Chỉ đọc [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về placeholder cho một hình dạng. Trả về null nếu hình dạng không có placeholder. Chỉ đọc [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về bản trình bày cha của một slide. Chỉ đọc [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc đặt các thuộc tính khung hình dạng thô. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc đặt số độ mà hình dạng được quay quanh trục z. Giá trị dương chỉ hướng quay theo chiều kim đồng hồ; giá trị âm chỉ hướng quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Trả về các khóa của hình dạng. Chỉ đọc [`IBaseShapeLock`](../ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Trả về đối tượng style của hình dạng. Chỉ đọc [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Trả về hoặc đặt kiểu preset hình học. Lưu ý: khi giá trị thay đổi, tất cả các giá trị điều chỉnh sẽ được đặt lại về giá trị mặc định. Đọc/ghi [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của một hình dạng. Chỉ đọc [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một hình dạng. Lưu ý: có thể trả về null đối với một số loại hình dạng không có thuộc tính 3D. Chỉ đọc [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về một định danh nội bộ, có phạm vi trong bản trình bày, dành cho các add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, nó không nên được coi là khóa duy nhất bền vững. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của một hình dạng trong thứ tự z. Shapes[0] trả về hình dạng ở phía sau nhất, và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước nhất. Chỉ đọc Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một placeholder mới nếu không có và đặt thuộc tính placeholder cho một placeholder được chỉ định. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Tạo và trả về mảng các phần tử của hình dạng. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một hình placeholder cơ bản (hình từ layout và/hoặc master slide mà hình hiện tại kế thừa). Trả về null nếu hình hiện tại không được kế thừa. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Trả về bản sao của đường dẫn của hình dạng hình học. Các tọa độ tương đối với góc trái-trên của hình dạng. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về hình thu nhỏ của hình dạng. Kiểu ShapeThumbnailBounds.Shape được dùng mặc định cho giới hạn hình thu nhỏ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về hình thu nhỏ của hình dạng. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lấy giới hạn trực quan của hình dạng được tính từ nội dung đã render. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Xác định rằng hình dạng này không phải là một placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Cập nhật hình học của hình dạng từ đối tượng [`IGeometryPath`](../igeometrypath). Các tọa độ phải tương đối với góc trái-trên của hình dạng. Thay đổi kiểu của hình dạng ([`ShapeType`](./shapetype)) thành Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Cập nhật hình học của hình dạng từ mảng [`IGeometryPath`](../igeometrypath). Các tọa độ phải tương đối với góc trái-trên của hình dạng. Thay đổi kiểu của hình dạng ([`ShapeType`](./shapetype)) thành Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |

### Xem thêm

* lớp [Shape](../shape)
* giao diện [IGeometryShape](../igeometryshape)
* không gian tên [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->