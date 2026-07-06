---
title: AudioFrame
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn một đoạn âm thanh trên slide.
type: docs
weight: 870
url: /vi/aspose.slides/audioframe/
---
## AudioFrame lớp

Represents an audio clip on a slide.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Thuộc tính

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Trả về một bộ sưu tập các giá trị điều chỉnh của hình dạng. Chỉ đọc [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Trả về hoặc đặt văn bản thay thế liên kết với một hình dạng. Đọc/ghi String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Trả về hoặc đặt tiêu đề của văn bản thay thế liên kết với một hình dạng. Đọc/ghi String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Trả về hoặc đặt chỉ mục bản ghi cuối cùng. Đọc/ghi Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Trả về hoặc đặt thời gian bản ghi cuối cùng. Đọc/ghi Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Trả về hoặc đặt chỉ mục bản ghi bắt đầu. Đọc/ghi Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Trả về hoặc đặt thời gian bản ghi bắt đầu. Đọc/ghi Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Thuộc tính xác định cách hình dạng sẽ hiển thị ở chế độ đen-trắng. Đọc/ghi [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | Lấy bộ sưu tập phụ đề đóng liên kết với khung âm thanh. Thuộc tính này chỉ đọc và trả về một [`ICaptionsCollection`](../icaptionscollection) chứa tất cả các bản ghi phụ đề. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Trả về số lượng vị trí kết nối trên hình dạng. Chỉ đọc Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Trả về dữ liệu tùy chỉnh của hình dạng. Chỉ đọc [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính hiệu ứng. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Xác định liệu âm thanh có được nhúng vào bản trình chiếu hay không. Chỉ đọc Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Trả về hoặc đặt đối tượng âm thanh nhúng. Đọc/ghi [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Xác định thời lượng cho hiệu ứng mờ dần ban đầu của phương tiện tính bằng mili giây. Đọc/ghi Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Xác định thời lượng cho hiệu ứng mờ dần kết thúc của phương tiện tính bằng mili giây. Đọc/ghi Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính tô màu. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Trả về hoặc đặt các thuộc tính khung hình dạng. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lấy hoặc đặt chiều cao của hình dạng, đo bằng point. Đọc/ghi Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Xác định liệu hình dạng có bị ẩn hay không. Đọc/ghi Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Xác định liệu AudioFrame có bị ẩn hay không. Đọc/ghi Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho nhấp chuột. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Trả về trình quản lý siêu liên kết. Chỉ đọc [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Xác định liệu PictureFrame có phải là đối tượng Cameo hay không. Chỉ đọc Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lấy hoặc đặt tùy chọn 'Mark as decorative'. Đọc/ghi Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Xác định liệu hình dạng có được nhóm không. Chỉ đọc Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Xác định liệu hình dạng là TextHolder_PPT hay không. Chỉ đọc Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính đường. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Trả về hoặc đặt tên của tệp âm thanh được liên kết với AudioFrame. Đọc/ghi String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Trả về hoặc đặt tên của một hình dạng. Không được null. Sử dụng chuỗi rỗng nếu cần. Đọc/ghi String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Trả về một định danh duy nhất có phạm vi trong slide, ổn định trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách tin cậy từ bất kỳ vị trí nào trong tài liệu. Chỉ đọc UInt32. Xem thêm [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không trả về null. Chỉ đọc [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Trả về đối tượng PictureFillFormat cho khung hình ảnh. Chỉ đọc [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Trả về các khóa của hình dạng. Chỉ đọc [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Trả về placeholder cho một hình dạng. Trả về null nếu hình dạng không có placeholder. Chỉ đọc [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Xác định liệu âm thanh có phát xuyên suốt các slide hay không. Đọc/ghi Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Xác định liệu âm thanh có lặp lại không. Đọc/ghi Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Trả về hoặc đặt chế độ phát âm thanh. Đọc/ghi [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Trả về bản trình chiếu cha của một slide. Chỉ đọc [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Trả về hoặc đặt các thuộc tính thô của khung hình dạng. Đọc/ghi [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Trả về hoặc đặt tỷ lệ chiều cao (so với kích thước ảnh gốc) của khung ảnh. Giá trị 1.0 tương đương 100%. Đọc/ghi Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Trả về hoặc đặt tỷ lệ chiều rộng (so với kích thước ảnh gốc) của khung ảnh. Giá trị 1.0 tương đương 100%. Đọc/ghi Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Xác định liệu âm thanh có tự động tua lại về đầu sau khi phát không. Đọc/ghi Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Trả về hoặc đặt số độ mà hình dạng được quay quanh trục z. Giá trị dương biểu thị quay theo chiều kim đồng hồ; giá trị âm biểu thị quay ngược chiều kim đồng hồ. Đọc/ghi Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Trả về các khóa của hình dạng. Chỉ đọc [`IPictureFrameLock`](../ipictureframelock). (2 thuộc tính) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Trả về đối tượng style của hình dạng. Chỉ đọc [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Trả về hoặc đặt kiểu AutoShape cho PictureFrame. Tất cả các mục cho phép trong tập [`ShapeType`](../shapetype), ngoại trừ mọi loại đường: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Trả về slide cha của một hình dạng. Chỉ đọc [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một hình dạng. Lưu ý: có thể trả về null cho một số loại hình dạng không có thuộc tính 3D. Chỉ đọc [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Xác định thời lượng cần loại bỏ khỏi cuối phương tiện khi phát, tính bằng mili giây. Đọc/ghi Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Xác định thời lượng cần loại bỏ khỏi đầu phương tiện khi phát, tính bằng mili giây. Đọc/ghi Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Trả về một định danh nội bộ, có phạm vi trong bản trình chiếu, được dự định cho các add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình cấp lại, không nên coi là khóa duy nhất luôn tồn tại. Chỉ đọc UInt32. Xem thêm [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Trả về hoặc đặt âm lượng âm thanh. Đọc/ghi [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Trả về hoặc đặt âm lượng âm thanh tính theo phần trăm. Đọc/ghi Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng point. Đọc/ghi Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng point. Đọc/ghi Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng point. Đọc/ghi Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Trả về vị trí của một hình dạng trong thứ tự z. Shapes[0] trả về hình dạng ở cuối cùng (phía sau) của thứ tự z, và Shapes[Shapes.Count - 1] trả về hình dạng ở đầu (phía trước) của thứ tự z. Chỉ đọc Int32. |

## Phương thức

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Thêm một placeholder mới nếu không có và đặt các thuộc tính placeholder thành một placeholder được chỉ định. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Tạo và trả về mảng các phần tử của hình dạng. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Trả về một hình dạng placeholder cơ bản (hình dạng từ bố cục và/hoặc slide chủ mà hình dạng hiện tại kế thừa). Trả về null nếu hình dạng hiện tại không được kế thừa. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Trả về bản sao của đường dẫn của hình dạng hình học. Các tọa độ tính tương đối với góc trên-trái của hình dạng. |
| [GetImage](../../aspose.slides/shape/getimage)() | Trả về hình thu nhỏ của hình dạng. Kiểu ShapeThumbnailBounds.Shape được sử dụng mặc định cho giới hạn hình thu nhỏ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Trả về hình thu nhỏ của hình dạng. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lấy giới hạn hình ảnh của hình dạng được tính từ nội dung đã render. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Xác định rằng hình dạng này không phải là placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Cập nhật hình học của hình dạng từ đối tượng [`IGeometryPath`](../igeometrypath). Các tọa độ phải tính tương đối với góc trên-trái của hình dạng. Thay đổi kiểu của hình dạng ([`ShapeType`](../geometryshape/shapetype)) thành Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Cập nhật hình học của hình dạng từ mảng [`IGeometryPath`](../igeometrypath). Các tọa độ phải tính tương đối với góc trên-trái của hình dạng. Thay đổi kiểu của hình dạng ([`ShapeType`](../geometryshape/shapetype)) thành Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |

### Ví dụ

The following examples shows how to change Audio Play Options.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Lấy hình dạng AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Đặt chế độ Play để phát khi nhấp chuột
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Đặt âm lượng thành Thấp
    audioFrame.Volume = AudioVolumeMode.Low;
    // Đặt âm thanh phát xuyên suốt các slide
    audioFrame.PlayAcrossSlides = true;
    // Vô hiệu hoá vòng lặp cho âm thanh
    audioFrame.PlayLoopMode = false;
    // Ẩn AudioFrame trong khi trình chiếu
    audioFrame.HideAtShowing = true;
    // Tua lại âm thanh về đầu sau khi phát
    audioFrame.RewindAudio = true;
    // Lưu tệp PowerPoint vào đĩa
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Xem thêm

* lớp [PictureFrame](../pictureframe)
* giao diện [IAudioFrame](../iaudioframe)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->