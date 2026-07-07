---
title: ShapeCollection
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Biểu diễn một tập hợp các hình dạng.
type: docs
weight: 9860
url: /vi/aspose.slides/shapecollection/
---
## ShapeCollection lớp

Biểu diễn một tập hợp các hình dạng.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Lấy số phần tử thực sự chứa trong collection. Chỉ đọc Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Trả về một giá trị chỉ ra liệu việc truy cập vào collection có được đồng bộ (an toàn đa luồng) hay không. Chỉ đọc Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Lấy đối tượng shape nhóm cha cho collection các shape. Chỉ đọc [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Trả về một gốc đồng bộ hóa. Chỉ đọc Object. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Tạo một khung âm thanh mới liên kết với một track CD và thêm nó vào cuối collection shape. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Tạo một khung âm thanh mới và thêm nó vào cuối collection shape bằng cách sử dụng một đối tượng âm thanh hiện có từ danh sách Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Tạo một khung âm thanh mới với tệp WAV nhúng và thêm nó vào cuối collection shape. Audio nhúng sẽ được thêm vào collection Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Tạo một khung âm thanh mới liên kết với một tệp âm thanh bên ngoài và thêm nó vào cuối collection shape. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Tạo một auto shape mới với định dạng mặc định và thêm nó vào cuối collection shape. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Tạo một auto shape mới và thêm nó vào cuối collection shape, tùy chọn khởi tạo nó với định dạng mẫu mặc định. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và thêm nó vào cuối collection shape. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và thêm nó vào cuối collection shape. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Tạo một bản sao của shape được chỉ định và thêm nó vào cuối collection shape. Shape được sao chép giữ nguyên vị trí và kích thước của nguyên bản. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Tạo một bản sao của shape được chỉ định và thêm nó vào cuối collection shape. Shape mới giữ nguyên chiều rộng và chiều cao của *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Tạo một bản sao của shape được chỉ định và thêm nó vào cuối collection shape. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Tạo một connector shape mới với kiểu mẫu mặc định và thêm nó vào cuối collection shape. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Tạo một connector shape mới và thêm nó vào cuối collection shape, tùy chọn áp dụng kiểu mẫu mặc định. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Tạo một group shape trống mới và thêm nó vào cuối collection shape. Khung của nhóm sẽ tự động điều chỉnh để vừa với bất kỳ shape nào được thêm vào. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Tạo một group shape mới, chuyển đổi hình ảnh SVG được chỉ định thành các shape riêng lẻ, và thêm nhóm được tạo vào cuối collection shape. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Tạo một auto shape hình chữ nhật mới để chứa nội dung toán học và thêm nó vào cuối collection shape. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Tạo một khung đối tượng OLE mới và thêm nó vào cuối collection shape. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Tạo một khung đối tượng OLE mới và thêm nó vào cuối collection shape. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Tạo một khung ảnh mới chứa hình ảnh được chỉ định và thêm nó vào cuối collection shape. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Tạo một khung Section Zoom mới và thêm nó vào cuối collection shape. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Tạo một khung Section Zoom mới với hình ảnh được định sẵn và thêm nó vào cuối collection shape. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Tạo một sơ đồ SmartArt và thêm nó vào cuối collection shape. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Tạo một khung Summary Zoom mới và thêm nó vào cuối collection shape. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Tạo một bảng mới và thêm nó vào cuối collection shape. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Tạo một khung video mới và thêm nó vào cuối collection shape. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Tạo một khung video mới và thêm nó vào cuối collection shape. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Tạo một khung Zoom mới và thêm nó vào cuối collection shape. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Tạo một khung Zoom mới và thêm nó vào cuối collection shape. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Xóa tất cả các shape khỏi collection shape. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Sao chép tất cả các phần tử từ collection vào mảng được chỉ định. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Trả về một enumerator cho phép duyệt qua collection. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của shape được chỉ định trong collection. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Tạo một khung âm thanh mới liên kết với một track CD và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Tạo một khung âm thanh mới và chèn nó vào collection shape tại chỉ mục được chỉ định bằng cách sử dụng một đối tượng âm thanh hiện có từ danh sách Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Tạo một khung âm thanh mới với tệp WAV nhúng và chèn nó vào collection shape tại chỉ mục được chỉ định. Audio nhúng sẽ được thêm vào collection Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Tạo một khung âm thanh mới liên kết với một tệp âm thanh bên ngoài và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Tạo một auto shape mới và chèn nó vào collection shape tại chỉ mục được chỉ định, áp dụng định dạng mẫu mặc định. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Tạo một auto shape mới và chèn nó vào collection shape tại chỉ mục được chỉ định, tùy chọn khởi tạo nó với kiểu mẫu mặc định. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Tạo một bản sao của shape được chỉ định và chèn nó vào collection shape tại chỉ mục được chỉ định. Shape sao chép giữ nguyên vị trí và kích thước của nguyên bản. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Tạo một bản sao của shape được chỉ định và chèn nó vào collection shape tại chỉ mục được chỉ định. Shape mới giữ nguyên chiều rộng và chiều cao của *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Tạo một bản sao của shape được chỉ định và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Tạo một connector shape mới và chèn nó vào collection shape tại chỉ mục được chỉ định, áp dụng kiểu mẫu mặc định. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Tạo một connector shape mới và chèn nó vào collection shape tại chỉ mục được chỉ định, tùy chọn áp dụng kiểu mẫu mặc định. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Tạo một group shape trống mới và chèn nó vào collection shape tại chỉ mục được chỉ định. Khung của nhóm sẽ tự động điều chỉnh để vừa với bất kỳ shape nào được thêm vào. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Tạo một khung đối tượng OLE mới và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Tạo một khung đối tượng OLE mới và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Tạo một khung ảnh mới chứa hình ảnh được chỉ định và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Tạo một khung Section Zoom mới và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Tạo một khung Section Zoom mới với hình ảnh được định sẵn và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Tạo một khung Summary Zoom mới và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Tạo một bảng mới và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Tạo một khung video mới và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Tạo một khung Zoom mới và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Tạo một khung Zoom mới với hình ảnh được định sẵn và chèn nó vào collection shape tại chỉ mục được chỉ định. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Xóa lần xuất hiện đầu tiên của shape được chỉ định khỏi collection shape. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Xóa shape tại chỉ mục được chỉ định khỏi collection shape. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Di chuyển shape được chỉ định tới vị trí mới trong collection shape. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Di chuyển các shape được chỉ định trong collection shape, đặt chúng bắt đầu từ chỉ mục đã cho. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Tạo và trả về một mảng chứa tất cả các shape. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Tạo và trả về một mảng chứa tất cả các shape trong khoảng được chỉ định. |

### Xem thêm

* lớp [DomObject&lt;TParent&gt;](../domobject-1)
* lớp [GroupShape](../groupshape)
* giao diện [IShapeCollection](../ishapecollection)
* không gian tên [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->