---
title: SmartArtShape
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Đại diện cho hình SmartArt
type: docs
weight: 10660
url: /vi/aspose.slides.smartart/smartartshape/
---
## SmartArtShape lớp

Đại diện cho hình SmartArt

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Trả về một bộ sưu tập các giá trị điều chỉnh của hình. Chỉ đọc [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc đặt văn bản thay thế liên kết với một hình. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc đặt tiêu đề của văn bản thay thế liên kết với một hình. Đọc/ghi String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính xác định cách một hình sẽ được hiển thị ở chế độ đen-trắng. Đọc/ghi [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số vị trí kết nối trên hình. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của hình. Chỉ đọc [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho một hình. Lưu ý: có thể trả về null đối với một số loại hình không có thuộc tính hiệu ứng. Chỉ đọc [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình. Lưu ý: có thể trả về null đối với một số loại hình không có thuộc tính tô màu. Chỉ đọc [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về hoặc đặt các thuộc tính khung của hình. Đọc/ghi [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lấy hoặc đặt chiều cao của hình, đo bằng điểm. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định xem hình có bị ẩn hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho nhấp chuột. Đọc/ghi [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về trình quản lý siêu liên kết. Chỉ đọc [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho rê chuột. Đọc/ghi [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'. Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định xem hình có được nhóm không. Chỉ đọc Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định xem hình có phải là TextHolder_PPT không. Chỉ đọc Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình. Lưu ý: có thể trả về null đối với một số loại hình không có thuộc tính đường. Chỉ đọc [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc đặt tên của một hình. Không được null. Sử dụng chuỗi rỗng nếu cần. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về một định danh duy nhất có phạm vi slide, duy trì không đổi trong suốt vòng đời của hình và cho phép PowerPoint hoặc mã interop tham chiếu hình một cách đáng tin cậy từ bất kỳ nơi nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu hình được nhóm. Nếu không trả về null. Chỉ đọc [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về placeholder cho một hình. Trả về null nếu hình không có placeholder. Chỉ đọc [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về bản trình bày cha của một slide. Chỉ đọc [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc đặt các thuộc tính thô của khung hình. Đọc/ghi [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc đặt số độ mà hình được quay quanh trục z. Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm biểu thị quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Trả về các khóa của hình. Chỉ đọc [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Trả về đối tượng style của hình. Chỉ đọc [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | Trả về hoặc đặt loại geometry preset. Lưu ý: khi giá trị thay đổi, tất cả các giá trị điều chỉnh sẽ được đặt lại về giá trị mặc định. Đọc/ghi [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của một hình. Chỉ đọc [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | Trả về văn bản của hình SmartArt. Chỉ đọc [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một hình. Lưu ý: có thể trả về null đối với một số loại hình không có thuộc tính 3D. Chỉ đọc [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về một định danh nội bộ, có phạm vi trong bản trình bày, được dùng cho add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, nên không nên coi là khóa duy nhất cố định. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lấy hoặc đặt chiều rộng của hình, đo bằng điểm. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lấy hoặc đặt tọa độ x của góc trên-trái của hình, đo bằng điểm. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lấy hoặc đặt tọa độ y của góc trên-trái của hình, đo bằng điểm. Đọc/ghi Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của một hình trong thứ tự z. Shapes[0] trả về hình ở cuối thứ tự z, và Shapes[Shapes.Count - 1] trả về hình ở đầu thứ tự z. Chỉ đọc Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một placeholder mới nếu không có và thiết lập các thuộc tính placeholder thành một placeholder được chỉ định. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Tạo và trả về một mảng các phần tử của hình. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một hình placeholder cơ bản (hình từ bố cục và/hoặc slide chủ mà hình hiện tại kế thừa). Trả về null nếu hình hiện tại không được kế thừa. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Trả về bản sao của đường dẫn của hình geometry. Tọa độ tương đối với góc trên-trái của hình. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về hình thu nhỏ của hình. Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về hình thu nhỏ của hình. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lấy giới hạn trực quan của hình được tính từ nội dung đã render. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Xác định rằng hình này không phải là placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Cập nhật geometry của hình từ đối tượng [`IGeometryPath`](../../aspose.slides/igeometrypath). Tọa độ phải tương đối với góc trên-trái của hình. Thay đổi loại của hình ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) thành Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Cập nhật geometry của hình từ mảng [`IGeometryPath`](../../aspose.slides/igeometrypath). Tọa độ phải tương đối với góc trên-trái của hình. Thay đổi loại của hình ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) thành Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |

### Xem thêm

* lớp [GeometryShape](../../aspose.slides/geometryshape)
* giao diện [ISmartArtShape](../ismartartshape)
* không gian tên [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* bộ lắp ráp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->