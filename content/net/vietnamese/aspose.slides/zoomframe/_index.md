---
title: ZoomFrame
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Đại diện cho một đối tượng Slide Zoom trong một slide.
type: docs
weight: 11840
url: /vi/aspose.slides/zoomframe/
---
## Lớp ZoomFrame

Represents a Slide Zoom object in a slide.

```csharp
public class ZoomFrame : ZoomObject, IZoomFrame
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc thiết lập văn bản thay thế liên kết với một hình dạng. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc thiết lập tiêu đề của văn bản thay thế liên kết với một hình dạng. Đọc/ghi String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính xác định cách một hình dạng sẽ hiển thị trong chế độ đen trắng. Đọc/ghi [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số lượng điểm kết nối trên hình dạng. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của hình dạng. Chỉ đọc [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính hiệu ứng. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính tô màu. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về hoặc thiết lập các thuộc tính khung hình dạng. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Trả về các khóa của hình dạng. Chỉ đọc [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lấy hoặc thiết lập chiều cao của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định liệu hình dạng có bị ẩn hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc thiết lập siêu liên kết được xác định cho cú nhấp chuột. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về trình quản lý siêu liên kết. Chỉ đọc [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc thiết lập siêu liên kết được xác định khi di chuột qua. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Lấy hoặc thiết lập loại hình ảnh của đối tượng zoom. Đọc/ghi [`ZoomImageType`](../zoomimagetype). Giá trị mặc định: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lấy hoặc thiết lập tùy chọn 'Đánh dấu là trang trí'. Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định liệu hình dạng có được nhóm hay không. Chỉ đọc Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định liệu hình dạng là TextHolder_PPT hay không. Chỉ đọc Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính đường. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc thiết lập tên của một hình dạng. Không được null. Sử dụng chuỗi rỗng nếu cần. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về một định danh duy nhất trong phạm vi slide, không thay đổi trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không, trả về null. Chỉ đọc [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về placeholder cho một hình dạng. Trả về null nếu hình dạng không có placeholder. Chỉ đọc [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về bản trình bày cha của một slide. Chỉ đọc [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc thiết lập các thuộc tính khung hình dạng thô. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Lấy hoặc thiết lập hành vi điều hướng trong trình chiếu. Đọc/ghi Boolean. Giá trị mặc định: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc thiết lập số độ mà hình dạng được quay quanh trục z. Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm biểu thị quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Trả về các khóa của hình dạng. Chỉ đọc [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 thuộc tính) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Lấy hoặc thiết lập giá trị xác định liệu Zoom sẽ sử dụng nền của slide đích hay không. Đọc/ghi Boolean. Giá trị mặc định: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của một hình dạng. Chỉ đọc [`IBaseSlide`](../ibaseslide). |
| [TargetSlide](../../aspose.slides/zoomframe/targetslide) { get; set; } | Lấy hoặc thiết lập đối tượng slide mà đối tượng Slide Zoom liên kết tới. Đọc/ghi [`ISlide`](../islide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3d cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính 3d. Chỉ đọc [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Lấy hoặc thiết lập thời lượng chuyển đổi giữa Zoom và slide. Đọc/ghi Single. Giá trị mặc định: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về định danh nội bộ, thuộc phạm vi bản trình bày, dự định cho các add-in hoặc mã khác sử dụng. Vì giá trị này có thể được gán lại bởi người dùng hoặc chương trình, không nên coi là khóa duy nhất bền vững. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lấy hoặc thiết lập chiều rộng của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lấy hoặc thiết lập tọa độ x của góc trên-left của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lấy hoặc thiết lập tọa độ y của góc trên-left của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Lấy hoặc thiết lập hình ảnh cho đối tượng zoom. Đọc/ghi [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của một hình dạng trong thứ tự z. Shapes[0] trả về hình dạng ở phía sau nhất của thứ tự z, và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước nhất của thứ tự z. Chỉ đọc Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một placeholder mới nếu không có và thiết lập các thuộc tính placeholder cho một placeholder được chỉ định. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một hình dạng placeholder cơ bản (hình dạng từ bố cục và/hoặc slide master mà hình dạng hiện tại kế thừa). Trả về null nếu hình dạng hiện tại không được kế thừa. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về hình thu nhỏ của hình dạng. Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn hình thu nhỏ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về hình thu nhỏ của hình dạng. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lấy giới hạn trực quan của hình dạng được tính từ nội dung đã kết xuất. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Xác định rằng hình dạng này không phải là một placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |

### Xem thêm

* lớp [ZoomObject](../zoomobject)
* giao diện [IZoomFrame](../izoomframe)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->