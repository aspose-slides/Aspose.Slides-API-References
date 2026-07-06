---
title: OleObjectFrame
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn một đối tượng OLE trên một slide.
type: docs
weight: 9230
url: /vi/aspose.slides/oleobjectframe/
---
## Lớp OleObjectFrame

Represent một đối tượng OLE trên một slide.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Thuộc tính

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc thiết lập văn bản thay thế liên kết với một hình dạng. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc thiết lập tiêu đề của văn bản thay thế liên kết với một hình dạng. Đọc/ghi String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Cho phép lấy giao diện IGraphicalObject cơ bản. Chỉ đọc [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính chỉ định cách một hình dạng sẽ hiển thị trong chế độ trắng-đen. Đọc/ghi [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số lượng vị trí kết nối trên hình dạng. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của hình dạng. Chỉ đọc [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính hiệu ứng. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Lấy hoặc thiết lập thông tin về dữ liệu nhúng OLE. Đọc/ghi [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Trả về tên tệp của đối tượng OLE được nhúng |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Trả về đường dẫn của đối tượng OLE được nhúng |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính tô màu. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về hoặc thiết lập các thuộc tính khung hình dạng. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Trả về các khóa của hình dạng. Chỉ đọc [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lấy hoặc thiết lập chiều cao của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định xem hình dạng có bị ẩn hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc thiết lập siêu liên kết được xác định cho cú nhấp chuột. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về trình quản lý siêu liên kết. Chỉ đọc [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc thiết lập siêu liên kết được xác định cho di chuột qua. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lấy hoặc thiết lập tùy chọn 'Đánh dấu là trang trí'. Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định xem hình dạng có được nhóm hay không. Chỉ đọc Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Xác định xem đối tượng có hiển thị dưới dạng biểu tượng hay không. Đọc/ghi Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Xác định xem đối tượng có được liên kết tới tệp bên ngoài hay không. Chỉ đọc Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định xem hình dạng có phải là TextHolder_PPT hay không. Chỉ đọc Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính đường. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Trả về đường dẫn đầy đủ tới tệp được liên kết. Tên tệp ngắn sẽ được sử dụng. Chỉ đọc String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Trả về đường dẫn đầy đủ tới tệp được liên kết. Tên tệp dài sẽ được sử dụng. Đọc/ghi String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Trả về đường dẫn tương đối tới tệp được liên kết nếu có, nếu không trả về chuỗi rỗng. Chỉ đọc String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc thiết lập tên của một hình dạng. Không được null. Sử dụng giá trị chuỗi rỗng nếu cần. Đọc/ghi String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Trả về hoặc thiết lập tên của một đối tượng. Đọc/ghi String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Trả về ProgID của một đối tượng. Chỉ đọc String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về định danh duy nhất có phạm vi slide, không đổi trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không trả về null. Chỉ đọc [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về đối tượng placeholder cho một hình dạng. Trả về null nếu hình dạng không có placeholder. Chỉ đọc [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về bản trình bày cha của một slide. Chỉ đọc [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc thiết lập các thuộc tính khung hình dạng thô. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc thiết lập số độ mà hình dạng được quay quanh trục z. Giá trị dương chỉ quay theo chiều kim đồng hồ; giá trị âm chỉ quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Trả về các khóa của hình dạng. Chỉ đọc [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 thuộc tính) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của một hình dạng. Chỉ đọc [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Trả về đối tượng thuộc tính tô hình ảnh OleObject. Chỉ đọc [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Trả về hoặc thiết lập tiêu đề cho biểu tượng OleObject. Đọc/ghi String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính 3D. Chỉ đọc [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về định danh nội bộ, có phạm vi bản trình bày, dành cho add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, nên không nên coi là khóa duy nhất cố định. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Xác định xem đối tượng nhúng được liên kết có tự động cập nhật khi bản trình bày được mở hoặc in hay không. Đọc/ghi Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lấy hoặc thiết lập chiều rộng của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lấy hoặc thiết lập tọa độ x của góc trên-trái của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lấy hoặc thiết lập tọa độ y của góc trên-trái của hình dạng, đo bằng điểm. Đọc/ghi Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của một hình dạng trong thứ tự z. Shapes[0] trả về hình dạng ở phía sau cùng của thứ tự z, và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước cùng. Chỉ đọc Int32. |

## Phương thức

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một placeholder mới nếu không có và thiết lập các thuộc tính placeholder cho một placeholder được chỉ định. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một hình dạng placeholder cơ bản (hình dạng từ bố cục và/hoặc slide master mà hình dạng hiện tại kế thừa). Trả về null nếu hình dạng hiện tại không được kế thừa. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về hình thu nhỏ của hình dạng. Kiểu ShapeThumbnailBounds.Shape được sử dụng mặc định. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về hình thu nhỏ của hình dạng. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lấy giới hạn hình ảnh của hình dạng tính từ nội dung đã hiển thị. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Xác định rằng hình dạng này không phải là placeholder. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Thiết lập thông tin về dữ liệu OLE được nhúng. Phương pháp này thay đổi các thuộc tính của đối tượng để phản ánh dữ liệu mới và đặt cờ IsObjectLink thành false, chỉ ra rằng đối tượng OLE được nhúng. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |

### Ví dụ

Ví dụ sau đây cho thấy cách truy cập khung OLE Object frames.

```csharp
[C#]
// Tải tệp PPTX vào một đối tượng presentation
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Truy cập slide đầu tiên
    ISlide sld = pres.Slides[0];
    // Ép kiểu hình dạng thành OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Đọc đối tượng OLE và ghi nó ra đĩa
    if (oleObjectFrame != null)
    {
        // Lấy dữ liệu tệp được nhúng
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Lấy phần mở rộng tệp được nhúng
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Tạo đường dẫn để lưu tệp đã trích xuất
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Lưu dữ liệu đã trích xuất
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### Xem thêm

* lớp [GraphicalObject](../graphicalobject)
* giao diện [IOleObjectFrame](../ioleobjectframe)
* không gian tên [Aspose.Slides](../../aspose.slides)
* bộ lắp ráp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->