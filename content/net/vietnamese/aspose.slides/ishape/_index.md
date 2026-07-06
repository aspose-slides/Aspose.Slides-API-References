---
title: IShape
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Đại diện cho một hình dạng trên một slide.
type: docs
weight: 6950
url: /vi/aspose.slides/ishape/
---
## IShape giao diện

Đại diện cho một hình dạng trên một slide.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Trả về hoặc đặt văn bản thay thế liên quan đến một hình dạng. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan đến một hình dạng. Đọc/ghi String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Cho phép lấy giao diện IHyperlinkContainer cơ bản. Chỉ đọc [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Cho phép lấy giao diện ISlideComponent cơ bản. Chỉ đọc [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Thuộc tính chỉ định cách một hình dạng sẽ hiển thị trong chế độ đen-trắng.. Đọc/ghi [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Trả về số lượng vị trí kết nối trên hình dạng. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của hình dạng. Chỉ đọc [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho một hình dạng. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô đầy cho một hình dạng. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Trả về hoặc đặt các thuộc tính khung hình dạng. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Lấy hoặc đặt chiều cao của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Xác định xem hình dạng có bị ẩn hay không. Đọc/ghi Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Lấy hoặc đặt tùy chọn 'Mark as decorative'. Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Xác định xem hình dạng có được nhóm không. Chỉ đọc Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Xác định xem hình dạng có phải là TextHolder không. Chỉ đọc Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Trả về hoặc đặt tên của một hình dạng. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Trả về một định danh duy nhất có phạm vi slide, luôn không đổi trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không, trả về null. Chỉ đọc [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Trả về trình giữ chỗ cho một hình dạng. Chỉ đọc [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Trả về hoặc đặt các thuộc tính thô của khung hình dạng. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Trả về hoặc đặt số độ mà hình dạng được quay quanh trục z. Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm biểu thị quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Trả về các khóa của hình dạng. Chỉ đọc [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính định dạng đường cho một hình dạng. Chỉ đọc [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Trả về một định danh nội bộ, có phạm vi bản trình chiếu, dự định cho các add-in hoặc mã khác sử dụng. Vì giá trị này có thể được người dùng hoặc chương trình gán lại, không nên coi nó như một khóa duy nhất lâu dài. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Trả về vị trí của một hình dạng trong thứ tự z. Shapes[0] trả về hình dạng ở phía sau của thứ tự z, và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước của thứ tự z. Chỉ đọc Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Thêm một trình giữ chỗ mới nếu chưa có và thiết lập các thuộc tính trình giữ chỗ thành một đối tượng cụ thể. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Trả về một hình dạng trình giữ chỗ cơ bản (hình dạng từ bố cục và/hoặc slide master mà hình dạng hiện tại kế thừa). Trả về null nếu hình dạng hiện tại không được kế thừa. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Trả về ảnh thu nhỏ của hình dạng. Kiểu ShapeThumbnailBounds.Shape được sử dụng mặc định cho giới hạn ảnh thu nhỏ. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Trả về ảnh thu nhỏ của hình dạng. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Xác định rằng hình dạng này không phải là trình giữ chỗ. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |

### Xem Thêm

* giao diện [IHyperlinkContainer](../ihyperlinkcontainer)
* giao diện [ISlideComponent](../islidecomponent)
* không gian tên [Aspose.Slides](../../aspose.slides)
* bộ chứa [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->