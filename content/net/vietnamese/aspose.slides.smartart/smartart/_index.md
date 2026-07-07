---
title: SmartArt
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Biểu thị một sơ đồ SmartArt
type: docs
weight: 10600
url: /vi/aspose.slides.smartart/smartart/
---
## SmartArt lớp

Represents a SmartArt diagram

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | Trả về các bộ sưu tập của tất cả các nút trong đối tượng SmartArt. Chỉ đọc [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc đặt văn bản thay thế liên kết với một hình dạng. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc đặt tiêu đề của văn bản thay thế liên kết với một hình dạng. Đọc/ghi String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính chỉ định cách một hình dạng sẽ hiển thị ở chế độ đen trắng. Đọc/ghi [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | Trả về hoặc đặt kiểu màu của đối tượng SmartArt. Đọc/ghi [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số lượng vị trí kết nối trên hình dạng. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của hình dạng. Chỉ đọc [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính hiệu ứng. Chỉ đọc [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính tô màu. Chỉ đọc [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về các thuộc tính khung hình dạng. Đọc/ghi [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Trả về khóa của hình dạng. Chỉ đọc [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lấy hoặc đặt chiều cao của hình dạng, đo bằng points. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định liệu hình dạng có bị ẩn hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho nhấp chuột. Đọc/ghi [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về trình quản lý siêu liên kết. Chỉ đọc [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột qua. Đọc/ghi [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí' Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định liệu hình dạng có được nhóm hay không. Chỉ đọc Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | Trả về hoặc đặt trạng thái của sơ đồ SmartArt liên quan đến LTR (trái sang phải) hoặc RTL (phải sang trái), nếu sơ đồ hỗ trợ đảo ngược. Đọc/ghi Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định liệu hình dạng là TextHolder_PPT hay không. Chỉ đọc Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | Trả về hoặc đặt bố cục của đối tượng SmartArt. Đọc/ghi [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính đường. Chỉ đọc [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc đặt tên của một hình dạng. Phải không null. Sử dụng giá trị chuỗi rỗng nếu cần. Đọc/ghi String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | Trả về các bộ sưu tập của các nút gốc trong đối tượng SmartArt. Chỉ đọc [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về định danh duy nhất trong phạm vi slide, không thay đổi trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không trả về null. Chỉ đọc [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về placeholder cho một hình dạng. Trả về null nếu hình dạng không có placeholder. Chỉ đọc [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về bản trình chiếu cha của một slide. Chỉ đọc [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | Trả về hoặc đặt kiểu nhanh của đối tượng SmartArt. Đọc/ghi [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc đặt các thuộc tính khung hình dạng thô. Đọc/ghi [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc đặt số độ mà hình dạng được chỉ định quay quanh trục z. Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm biểu thị quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Trả về khóa của hình dạng. Chỉ đọc [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 thuộc tính) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của một hình dạng. Chỉ đọc [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính 3D. Chỉ đọc [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về định danh nội bộ trong phạm vi bản trình chiếu, dành cho add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình gán lại, nên không nên coi là khóa duy nhất lâu dài. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng points. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lấy hoặc đặt tọa độ x của góc trên bên trái của hình dạng, đo bằng points. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lấy hoặc đặt tọa độ y của góc trên bên trái của hình dạng, đo bằng points. Đọc/ghi Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của một hình dạng trong z-order. Shapes[0] trả về hình dạng ở cuối z-order, và Shapes[Shapes.Count - 1] trả về hình dạng ở đầu z-order. Chỉ đọc Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một placeholder mới nếu không tồn tại và đặt các thuộc tính placeholder cho một placeholder được chỉ định. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một hình dạng placeholder cơ bản (hình dạng từ layout và/hoặc master slide mà hình dạng hiện tại kế thừa). Trả về null nếu hình dạng hiện tại không được kế thừa. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về hình thu nhỏ của hình dạng. Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn hình thu nhỏ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về hình thu nhỏ của hình dạng. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lấy giới hạn visual của hình dạng được tính từ nội dung đã render. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Xác định rằng hình dạng này không phải là một placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |

### Xem thêm

* lớp [GraphicalObject](../../aspose.slides/graphicalobject)
* giao diện [ISmartArt](../ismartart)
* không gian tên [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->