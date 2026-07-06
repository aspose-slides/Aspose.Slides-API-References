---
title: Table
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu thị một bảng trên một slide.
type: docs
weight: 10860
url: /vi/aspose.slides/table/
---
## Lớp Table

Biểu thị một bảng trên một slide.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Thuộc tính

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc đặt văn bản thay thế được liên kết với một shape. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc đặt tiêu đề của văn bản thay thế được liên kết với một shape. Đọc/ghi String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính chỉ định cách một shape sẽ hiển thị ở chế độ đen-trắng.. Đọc/ghi [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Trả về bộ sưu tập các cột. Chỉ đọc [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số vị trí kết nối trên shape. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của shape. Chỉ đọc [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một shape. Lưu ý: có thể trả về null đối với một số loại shape không có thuộc tính hiệu ứng. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Trả về đối tượng TableFormat.FillFormat chứa định dạng tô cho Table. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Xác định liệu cột đầu tiên của bảng có được vẽ với định dạng đặc biệt hay không. Đọc/ghi Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Xác định liệu hàng đầu tiên của bảng có được vẽ với định dạng đặc biệt hay không. Đọc/ghi Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về hoặc đặt các thuộc tính khung shape. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Trả về các khóa của shape. Chỉ đọc [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lấy hoặc đặt chiều cao của shape, đo bằng điểm. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định liệu shape có bị ẩn hay không. Đọc/ghi Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Xác định liệu các hàng chẵn có cần được vẽ với định dạng khác hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho nhấp chuột. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về trình quản lý siêu liên kết. Chỉ đọc [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột qua. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'. Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định liệu shape có được nhóm không. Chỉ đọc Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định liệu shape là TextHolder_PPT hay không. Chỉ đọc Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Trả về ô tại chỉ mục cột và hàng được chỉ định. Chỉ đọc [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Xác định liệu cột cuối cùng của bảng có được vẽ với định dạng đặc biệt hay không. Đọc/ghi Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Xác định liệu hàng cuối cùng của bảng có được vẽ với định dạng đặc biệt hay không. Đọc/ghi Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một shape. Lưu ý: có thể trả về null đối với một số loại shape không có thuộc tính đường. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc đặt tên của một shape. Không được null. Sử dụng giá trị chuỗi rỗng nếu cần. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về một định danh duy nhất có phạm vi slide, giữ nguyên trong suốt vòng đời của shape và cho phép PowerPoint hoặc mã interop tham chiếu shape một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu shape được nhóm. Nếu không, trả về null. Chỉ đọc [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về placeholder cho một shape. Trả về null nếu shape không có placeholder. Chỉ đọc [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về bài thuyết trình cha của một slide. Chỉ đọc [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc đặt các thuộc tính khung shape thô. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Xác định liệu bảng có thứ tự đọc từ phải sang trái hay không. Đọc/ghi Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc đặt số độ mà shape được quay quanh trục z. Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm biểu thị quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Trả về bộ sưu tập các hàng. Chỉ đọc [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Trả về các khóa của shape. Chỉ đọc [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của một shape. Chỉ đọc [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Lấy hoặc đặt kiểu bảng dựng sẵn. Đọc/ghi [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Trả về đối tượng TableFormat chứa các thuộc tính định dạng cho bảng này. Chỉ đọc [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3d cho một shape. Lưu ý: có thể trả về null đối với một số loại shape không có thuộc tính 3d. Chỉ đọc [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về một định danh nội bộ, có phạm vi trong bài thuyết trình, dành cho các add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình gán lại, không nên coi nó là khóa duy nhất cố định. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Xác định liệu các cột chẵn có cần được vẽ với định dạng khác hay không. Đọc/ghi Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lấy hoặc đặt chiều rộng của shape, đo bằng điểm. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lấy hoặc đặt tọa độ x của góc trên-trái của shape, đo bằng điểm. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lấy hoặc đặt tọa độ y của góc trên-trái của shape, đo bằng điểm. Đọc/ghi Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của một shape trong thứ tự z. Shapes[0] trả về shape ở phía sau cùng của thứ tự z, và Shapes[Shapes.Count - 1] trả về shape ở phía trước cùng của thứ tự z. Chỉ đọc Int32. |

## Phương thức

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một placeholder mới nếu không có và đặt các thuộc tính placeholder cho một placeholder được chỉ định. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một shape placeholder cơ bản (shape từ bố cục và/hoặc slide master mà shape hiện tại kế thừa). Trả về null nếu shape hiện tại không được kế thừa. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về hình thu nhỏ của shape. Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn hình thu nhỏ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về hình thu nhỏ của shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lấy giới hạn trực quan của shape được tính từ nội dung đã render. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Hợp nhất các ô lân cận. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Xác định rằng shape này không phải là placeholder. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Đặt các thuộc tính định dạng đoạn văn đã xác định cho tất cả đoạn văn của các ô bảng. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Đặt các thuộc tính định dạng phần đã xác định cho tất cả phần của các ô bảng. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Đặt các thuộc tính định dạng khung văn bản đã xác định cho tất cả khung văn bản của các ô bảng. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |

### Xem thêm

* lớp [GraphicalObject](../graphicalobject)
* giao diện [ITable](../itable)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->