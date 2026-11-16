---
title: IShape
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Đại diện cho một hình dạng trên một slide.
type: docs
weight: 6970
url: /vi/aspose.slides/ishape/
---
## IShape interface

Represents a shape on a slide.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Trả về hoặc đặt văn bản thay thế liên quan đến hình dạng. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan đến hình dạng. Đọc/ghi String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Cho phép lấy giao diện IHyperlinkContainer cơ bản. Chỉ đọc [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Cho phép lấy giao diện ISlideComponent cơ bản. Chỉ đọc [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Thuộc tính xác định cách hình dạng sẽ hiển thị ở chế độ hiển thị đen-trắng. Đọc/ghi [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Trả về số lượng vị trí kết nối trên hình dạng. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của hình dạng. Chỉ đọc [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho hình dạng. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho hình dạng. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Trả về hoặc đặt các thuộc tính khung hình dạng. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Lấy hoặc đặt chiều cao của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Xác định liệu hình dạng có bị ẩn hay không. Đọc/ghi Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'. Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Xác định liệu hình dạng có được nhóm hay không. Chỉ đọc Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Xác định liệu hình dạng có phải là TextHolder hay không. Chỉ đọc Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho hình dạng. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Trả về hoặc đặt tên của hình dạng. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Trả về mã định danh duy nhất trong phạm vi slide, không thay đổi trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không, trả về null. Chỉ đọc [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Trả về chỗ giữ chỗ cho hình dạng. Chỉ đọc [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Trả về hoặc đặt các thuộc tính khung hình dạng thô. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Trả về hoặc đặt số độ mà hình dạng được xoay quanh trục z. Giá trị dương chỉ quay theo chiều kim đồng hồ; giá trị âm chỉ quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Trả về các khóa của hình dạng. Chỉ đọc [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính định dạng đường cho hình dạng. Chỉ đọc [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Trả về một mã định danh nội bộ, có phạm vi trong bản trình chiếu, dành cho add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, không nên coi nó là khóa duy nhất cố định. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Trả về vị trí của hình dạng trong thứ tự z. Shapes[0] trả về hình dạng ở cuối thứ tự z, và Shapes[Shapes.Count - 1] trả về hình dạng ở đầu thứ tự z. Chỉ đọc Int32. |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Thêm một chỗ giữ chỗ mới nếu không có và đặt các thuộc tính chỗ giữ chỗ thành một chỗ giữ chỗ được chỉ định. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Trả về một hình dạng chỗ giữ chỗ cơ bản (hình dạng từ bố cục và/hoặc slide mẫu mà hình dạng hiện tại kế thừa). Trả về null nếu hình dạng hiện tại không kế thừa. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Trả về ảnh thu nhỏ của hình dạng. Kiểu ShapeThumbnailBounds.Shape được sử dụng mặc định cho giới hạn ảnh thu nhỏ. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Trả về ảnh thu nhỏ của hình dạng. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Xác định rằng hình dạng này không phải là chỗ giữ chỗ. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Lưu nội dung Shape dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Lưu nội dung Shape dưới dạng tệp SVG. |

### See Also

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->