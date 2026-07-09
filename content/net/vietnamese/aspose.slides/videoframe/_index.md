---
title: VideoFrame
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn một đoạn video trên slide.
type: docs
weight: 11720
url: /vi/aspose.slides/videoframe/
---
## VideoFrame lớp

Biểu diễn một đoạn video trên một slide.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Trả về một bộ sưu tập các giá trị điều chỉnh của hình dạng. Chỉ đọc [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc thiết lập văn bản thay thế liên kết với một hình dạng. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc thiết lập tiêu đề của văn bản thay thế liên kết với một hình dạng. Đọc/ghi String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính xác định cách một hình dạng sẽ hiển thị trong chế độ đen-trắng. Đọc/ghi [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Lấy bộ sưu tập phụ đề đóng liên kết với khung video. Thuộc tính này chỉ đọc và trả về một [`ICaptionsCollection`](../icaptionscollection) chứa tất cả các track phụ đề. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số lượng điểm kết nối trên hình dạng. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của hình dạng. Chỉ đọc [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một hình dạng. Lưu ý: có thể trả về null đối với một số loại hình dạng không có thuộc tính hiệu ứng. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Trả về hoặc thiết lập đối tượng video nhúng. Đọc/ghi [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng. Lưu ý: có thể trả về null đối với một số loại hình dạng không có thuộc tính tô màu. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về hoặc thiết lập các thuộc tính khung của hình dạng. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Xác định xem video có được hiển thị ở chế độ toàn màn hình hay không. Đọc/ghi Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lấy hoặc thiết lập chiều cao của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định xem hình dạng có bị ẩn hay không. Đọc/ghi Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Xác định xem VideoFrame có bị ẩn hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc thiết lập siêu liên kết được định nghĩa cho nhấp chuột. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về trình quản lý siêu liên kết. Chỉ đọc [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc thiết lập siêu liên kết được định nghĩa cho rê chuột. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Xác định liệu PictureFrame có phải là đối tượng Cameo hay không. Chỉ đọc Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lấy hoặc thiết lập tùy chọn “Đánh dấu là trang trí”. Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định xem hình dạng có được nhóm hay không. Chỉ đọc Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định xem hình dạng có phải là TextHolder_PPT hay không. Chỉ đọc Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng. Lưu ý: có thể trả về null đối với một số loại hình dạng không có thuộc tính đường. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Trả về hoặc thiết lập tên của tệp video được liên kết với VideoFrame. Đọc/ghi String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc thiết lập tên của một hình dạng. Không được null. Sử dụng chuỗi rỗng nếu cần. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về một định danh duy nhất có phạm vi slide, không thay đổi trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không, trả về null. Chỉ đọc [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Trả về đối tượng PictureFillFormat cho khung ảnh. Chỉ đọc [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Trả về các khóa của hình dạng. Chỉ đọc [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về placeholder cho một hình dạng. Trả về null nếu hình dạng không có placeholder. Chỉ đọc [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Xác định xem video có được lặp lại hay không. Đọc/ghi Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Trả về hoặc thiết lập chế độ phát video. Đọc/ghi [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về bản trình chiếu cha của một slide. Chỉ đọc [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc thiết lập các thuộc tính thô của khung hình dạng. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Trả về hoặc thiết lập tỷ lệ chiều cao (so với kích thước ảnh gốc) của khung ảnh. Giá trị 1.0 tương đương 100 %. Đọc/ghi Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Trả về hoặc thiết lập tỷ lệ chiều rộng (so với kích thước ảnh gốc) của khung ảnh. Giá trị 1.0 tương đương 100 %. Đọc/ghi Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Xác định xem video có tự động tua lại về đầu khi phim kết thúc phát hay không. Đọc/ghi Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc thiết lập số độ mà hình dạng được xoay quanh trục z. Giá trị dương biểu thị xoay theo chiều kim đồng hồ; giá trị âm biểu thị xoay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Trả về các khóa của hình dạng. Chỉ đọc [`IPictureFrameLock`](../ipictureframelock). (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Trả về đối tượng style của hình dạng. Chỉ đọc [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Trả về hoặc thiết lập kiểu AutoShape cho PictureFrame. Tất cả các mục trong tập [`ShapeType`](../shapetype) đều cho phép, ngoại trừ mọi loại đường: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của một hình dạng. Chỉ đọc [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một hình dạng. Lưu ý: có thể trả về null đối với một số loại hình dạng không có thuộc tính 3D. Chỉ đọc [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Trim end [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Trim start [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về một định danh nội bộ có phạm vi presentation, dành cho add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình gán lại, không nên xem nó như một khóa duy nhất cố định. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Trả về hoặc thiết lập âm lượng âm thanh. Đọc/ghi [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lấy hoặc thiết lập chiều rộng của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lấy hoặc thiết lập tọa độ x của góc trên-trái của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lấy hoặc thiết lập tọa độ y của góc trên-trái của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của một hình dạng trong z-order. Shapes[0] trả về hình dạng ở phía sau cùng của z-order, và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước cùng. Chỉ đọc Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một placeholder mới nếu không có và thiết lập các thuộc tính placeholder cho một placeholder được chỉ định. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Tạo và trả về mảng các phần tử của hình dạng. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một hình dạng placeholder cơ bản (hình dạng từ layout và/hoặc master slide mà hình dạng hiện tại kế thừa). Trả về null nếu hình dạng hiện tại không được kế thừa. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Trả về bản sao của đường dẫn hình học của hình dạng. Các tọa độ tính tương đối so với góc trên-trái của hình dạng. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về ảnh thu nhỏ của hình dạng. Kiểu ShapeThumbnailBounds.Shape được dùng làm mặc định cho giới hạn ảnh thu nhỏ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về ảnh thu nhỏ của hình dạng. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lấy giới hạn trực quan của hình dạng được tính từ nội dung đã render. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Định nghĩa rằng hình dạng này không phải là một placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Cập nhật hình học của hình dạng từ đối tượng [`IGeometryPath`](../igeometrypath). Các tọa độ phải tính tương đối so với góc trên-trái của hình dạng. Thay đổi kiểu của hình dạng ([`ShapeType`](../geometryshape/shapetype)) thành Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Cập nhật hình học của hình dạng từ mảng [`IGeometryPath`](../igeometrypath). Các tọa độ phải tính tương đối so với góc trên-trái của hình dạng. Thay đổi kiểu của hình dạng ([`ShapeType`](../geometryshape/shapetype)) thành Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |

### Xem Thêm

* lớp [PictureFrame](../pictureframe)
* giao diện [IVideoFrame](../ivideoframe)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->