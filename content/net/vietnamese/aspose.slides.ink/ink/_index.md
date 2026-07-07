---
title: Ink
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu thị một đối tượng mực trên một slide.
type: docs
weight: 7550
url: /vi/aspose.slides.ink/ink/
---
## Lớp Ink

Represents an ink object on a slide.

```csharp
public class Ink : GraphicalObject, IInk
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc đặt văn bản thay thế liên kết với shape. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc đặt tiêu đề của văn bản thay thế liên kết với shape. Đọc/ghi String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính xác định cách shape sẽ render trong chế độ đen-trắng.. Đọc/ghi [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số lượng vị trí kết nối trên shape. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của shape. Chỉ đọc [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho shape. Lưu ý: có thể trả về null đối với một số loại shape không có thuộc tính hiệu ứng. Chỉ đọc [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng màu cho shape. Lưu ý: có thể trả về null đối với một số loại shape không có thuộc tính màu. Chỉ đọc [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về hoặc đặt các thuộc tính khung của shape. Đọc/ghi [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Trả về các khóa của shape. Chỉ đọc [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lấy hoặc đặt chiều cao của shape, đo bằng điểm. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định xem shape có bị ẩn hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho cú nhấp chuột. Đọc/ghi [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về trình quản lý siêu liên kết. Chỉ đọc [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột qua. Đọc/ghi [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'. Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định xem shape có được nhóm hay không. Chỉ đọc Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định xem shape có phải là TextHolder_PPT hay không. Chỉ đọc Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho shape. Lưu ý: có thể trả về null đối với một số loại shape không có thuộc tính đường. Chỉ đọc [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc đặt tên của shape. Không được null. Sử dụng chuỗi rỗng nếu cần. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về định danh duy nhất trong phạm vi slide, luôn không thay đổi trong suốt vòng đời của shape và cho phép PowerPoint hoặc mã interop tham chiếu shape một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu shape được nhóm. Nếu không trả về null. Chỉ đọc [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về placeholder cho shape. Trả về null nếu shape không có placeholder. Chỉ đọc [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về bài thuyết trình cha của slide. Chỉ đọc [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc đặt các thuộc tính thô của khung shape. Đọc/ghi [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc đặt số độ mà shape được quay quanh trục z. Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm biểu thị quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Trả về các khóa của shape. Chỉ đọc [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 thuộc tính) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của shape. Chỉ đọc [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho shape. Lưu ý: có thể trả về null đối với một số loại shape không có thuộc tính 3D. Chỉ đọc [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | Lấy tất cả các dấu vết chứa trong phần tử IInk [`IInkTrace`](../iinktrace). Chỉ đọc. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về một định danh nội bộ, phạm vi bài thuyết trình, dùng cho add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, không nên dùng làm khóa duy nhất cố định. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lấy hoặc đặt chiều rộng của shape, đo bằng điểm. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lấy hoặc đặt tọa độ x của góc trên-trái của shape, đo bằng điểm. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lấy hoặc đặt tọa độ y của góc trên-trái của shape, đo bằng điểm. Đọc/ghi Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của shape trong thứ tự z. Shapes[0] trả về shape ở phía sau nhất, và Shapes[Shapes.Count - 1] trả về shape ở phía trước nhất. Chỉ đọc Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | Lấy tập hợp các hình ảnh tùy chỉnh dùng để mô phỏng hiệu ứng hình ảnh cho bút mực. Các hình ảnh này được dùng khi kết xuất mực với các giá trị [`InkEffectType`](../inkeffecttype) cụ thể, như Galaxy, Rainbow, v.v. Bằng cách cung cấp hình ảnh riêng, bạn có thể kiểm soát cách mỗi hiệu ứng mực hiển thị. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một placeholder mới nếu chưa có và đặt các thuộc tính placeholder cho một placeholder đã chỉ định. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một shape placeholder cơ bản (shape từ bố cục và/hoặc slide master mà shape hiện tại kế thừa). Trả về null nếu shape hiện tại không được kế thừa. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về hình thu nhỏ của shape. Kiểu ShapeThumbnailBounds.Shape được dùng làm mặc định cho giới hạn hình thu nhỏ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về hình thu nhỏ của shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lấy giới hạn hình ảnh của shape được tính từ nội dung đã kết xuất. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Xác định rằng shape này không phải là placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |

### Xem thêm

* lớp [GraphicalObject](../../aspose.slides/graphicalobject)
* giao diện [IInk](../iink)
* không gian tên [Aspose.Slides.Ink](../../aspose.slides.ink)
* tập tin lắp ráp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->