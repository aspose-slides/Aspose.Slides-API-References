---
title: PictureFrame
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Đại diện cho một khung có hình ảnh bên trong.
type: docs
weight: 9410
url: /vi/aspose.slides/pictureframe/
---
## PictureFrame lớp

Represents a frame with a picture inside.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Trả về một bộ sưu tập các giá trị điều chỉnh của shape. Chỉ đọc [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc thiết lập văn bản thay thế liên kết với một shape. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc thiết lập tiêu đề của văn bản thay thế liên kết với một shape. Đọc/ghi String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính chỉ định cách một shape sẽ hiển thị trong chế độ đen-trắng. Đọc/ghi [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số lượng điểm kết nối trên shape. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của shape. Chỉ đọc [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính hiệu ứng. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô đầy cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính tô đầy. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về hoặc thiết lập các thuộc tính khung shape. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Trả về hoặc thiết lập chiều cao của shape, đo bằng điểm. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định liệu shape có bị ẩn hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc thiết lập siêu liên kết được định nghĩa cho lần nhấp chuột. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về trình quản lý siêu liên kết. Chỉ đọc [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc thiết lập siêu liên kết được định nghĩa cho di chuột qua. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Xác định liệu PictureFrame có phải là đối tượng Cameo hay không. Chỉ đọc Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Trả về hoặc thiết lập tùy chọn 'Đánh dấu là trang trí'. Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định liệu shape có được nhóm không. Chỉ đọc Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định liệu shape có phải là TextHolder_PPT hay không. Chỉ đọc Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính đường. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc thiết lập tên của một shape. Không được null. Sử dụng giá trị chuỗi rỗng nếu cần. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về một định danh duy nhất trong phạm vi slide, cố định trong suốt vòng đời của shape và cho phép PowerPoint hoặc mã interop tham chiếu shape một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu shape được nhóm. Nếu không trả về null. Chỉ đọc [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Trả về đối tượng PictureFillFormat cho một khung hình. Chỉ đọc [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Trả về các khóa của shape. Chỉ đọc [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về chỗ giữ chỗ cho một shape. Trả về null nếu shape không có chỗ giữ chỗ. Chỉ đọc [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về bản trình chiếu cha của một slide. Chỉ đọc [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc thiết lập các thuộc tính thô của khung shape. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Trả về hoặc thiết lập tỉ lệ chiều cao (so với kích thước hình gốc) của khung hình. Giá trị 1.0 tương ứng với 100%. Đọc/ghi Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Trả về hoặc thiết lập tỉ lệ chiều rộng (so với kích thước hình gốc) của khung hình. Giá trị 1.0 tương ứng với 100%. Đọc/ghi Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc thiết lập số độ mà shape được quay quanh trục z. Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm biểu thị quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Trả về các khóa của shape. Chỉ đọc [`IPictureFrameLock`](../ipictureframelock). (2 thuộc tính) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Trả về đối tượng kiểu dáng của shape. Chỉ đọc [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Trả về hoặc thiết lập kiểu AutoShape cho một PictureFrame. Tất cả các mục cho phép của tập [`ShapeType`](../shapetype), ngoại trừ mọi loại đường: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của một shape. Chỉ đọc [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3d cho một shape. Lưu ý: có thể trả về null cho một số loại shape không có thuộc tính 3d. Chỉ đọc [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về một định danh nội bộ, có phạm vi trong bản trình chiếu, dành cho các add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình gán lại, nên không được coi là khóa duy nhất ổn định. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Trả về hoặc thiết lập chiều rộng của shape, đo bằng điểm. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Trả về hoặc thiết lập tọa độ x của góc trên-trái của shape, đo bằng điểm. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Trả về hoặc thiết lập tọa độ y của góc trên-trái của shape, đo bằng điểm. Đọc/ghi Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của một shape trong thứ tự z. Shapes[0] trả về shape ở phía sau cùng của thứ tự z, và Shapes[Shapes.Count - 1] trả về shape ở phía trước cùng. Chỉ đọc Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một placeholder mới nếu không có và thiết lập các thuộc tính placeholder thành một placeholder được chỉ định. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Tạo và trả về mảng các phần tử của shape. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một shape placeholder cơ bản (shape từ bố cục và/hoặc slide master mà shape hiện tại kế thừa). Trả về null nếu shape hiện tại không được kế thừa. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Trả về bản sao của đường dẫn của shape hình học. Tọa độ tính tương đối so với góc trên-trái của shape. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về hình thu nhỏ của shape. Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn hình thu nhỏ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về hình thu nhỏ của shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Trả về giới hạn hình ảnh của shape được tính từ nội dung đã render. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Xác định rằng shape này không phải là placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Cập nhật hình học của shape từ đối tượng [`IGeometryPath`](../igeometrypath). Tọa độ phải tính tương đối so với góc trên-trái của shape. Thay đổi kiểu của shape ([`ShapeType`](../geometryshape/shapetype)) thành Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Cập nhật hình học của shape từ mảng [`IGeometryPath`](../igeometrypath). Tọa độ phải tính tương đối so với góc trên-trái của shape. Thay đổi kiểu của shape ([`ShapeType`](../geometryshape/shapetype)) thành Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |

### Ví dụ

Các ví dụ sau đây cho thấy cách thay đổi hình thu nhỏ của Audio Frame Thumbnail.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // Thêm một khung âm thanh vào slide với vị trí và kích thước được chỉ định.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // Thêm một hình ảnh vào tài nguyên của bản trình chiếu.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // Đặt hình ảnh cho khung âm thanh.
	//Lưu bản trình chiếu đã chỉnh sửa vào đĩa
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### Xem thêm

* lớp [GeometryShape](../geometryshape)
* giao diện [IPictureFrame](../ipictureframe)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->