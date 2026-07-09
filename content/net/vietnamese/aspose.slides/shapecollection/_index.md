---
title: ShapeCollection
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Đại diện cho một tập hợp các hình dạng.
type: docs
weight: 9860
url: /vi/aspose.slides/shapecollection/
---
## ShapeCollection lớp

Đại diện cho một tập hợp các hình dạng.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Lấy số phần tử thực sự được chứa trong tập hợp. Chỉ đọc Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Trả về giá trị cho biết liệu việc truy cập vào tập hợp có được đồng bộ (an toàn đa luồng) hay không. Chỉ đọc Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Lấy đối tượng hình dạng nhóm cha cho tập hợp các hình dạng. Chỉ đọc [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Trả về gốc đồng bộ hoá. Chỉ đọc Object. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Tạo một khung âm thanh mới liên kết với một track CD và thêm nó vào cuối tập hợp hình dạng. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Tạo một khung âm thanh mới và thêm nó vào cuối tập hợp hình dạng bằng cách sử dụng đối tượng âm thanh hiện có từ danh sách Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Tạo một khung âm thanh mới với tệp WAV được nhúng và thêm nó vào cuối tập hợp hình dạng. Âm thanh được nhúng sẽ được thêm vào tập hợp Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Tạo một khung âm thanh mới liên kết với tệp âm thanh bên ngoài và thêm nó vào cuối tập hợp hình dạng. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Tạo một hình dạng tự động mới với định dạng mặc định và thêm nó vào cuối tập hợp hình dạng. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Tạo một hình dạng tự động mới và thêm nó vào cuối tập hợp hình dạng, tùy chọn khởi tạo với định dạng mẫu mặc định. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và thêm nó vào cuối tập hợp hình dạng. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và thêm nó vào cuối tập hợp hình dạng. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Tạo một bản sao của hình dạng được chỉ định và thêm nó vào cuối tập hợp hình dạng. Hình dạng sao chép giữ nguyên vị trí và kích thước của hình dạng gốc. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Tạo một bản sao của hình dạng được chỉ định và thêm nó vào cuối tập hợp hình dạng. Hình dạng mới giữ nguyên chiều rộng và chiều cao của *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Tạo một bản sao của hình dạng được chỉ định và thêm nó vào cuối tập hợp hình dạng. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Tạo một hình dạng kết nối mới với kiểu mẫu mặc định và thêm nó vào cuối tập hợp hình dạng. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Tạo một hình dạng kết nối mới và thêm nó vào cuối tập hợp hình dạng, tùy chọn áp dụng kiểu mẫu mặc định. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Tạo một nhóm hình dạng rỗng mới và thêm nó vào cuối tập hợp hình dạng. Khung của nhóm sẽ tự động điều chỉnh để vừa với bất kỳ hình dạng nào được thêm vào. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Tạo một nhóm hình dạng mới, chuyển đổi hình ảnh SVG được chỉ định thành các hình dạng riêng lẻ, và thêm nhóm tạo ra vào cuối tập hợp hình dạng. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Tạo một hình chữ nhật tự động mới để chứa nội dung toán học và thêm nó vào cuối tập hợp hình dạng. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Tạo một khung đối tượng OLE mới và thêm nó vào cuối tập hợp hình dạng. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Tạo một khung đối tượng OLE mới và thêm nó vào cuối tập hợp hình dạng. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Tạo một khung ảnh mới chứa hình ảnh được chỉ định và thêm nó vào cuối tập hợp hình dạng. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Tạo một khung Zoom Section mới và thêm nó vào cuối tập hợp hình dạng. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Tạo một khung Zoom Section mới với hình ảnh được định sẵn và thêm nó vào cuối tập hợp hình dạng. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Tạo một sơ đồ SmartArt và thêm nó vào cuối tập hợp hình dạng. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Tạo một khung Summary Zoom mới và thêm nó vào cuối tập hợp hình dạng. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Tạo một bảng mới và thêm nó vào cuối tập hợp hình dạng. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Tạo một khung video mới và thêm nó vào cuối tập hợp hình dạng. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Tạo một khung video mới và thêm nó vào cuối tập hợp hình dạng. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Tạo một khung Zoom mới và thêm nó vào cuối tập hợp hình dạng. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Tạo một khung Zoom mới và thêm nó vào cuối tập hợp hình dạng. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Xóa tất cả các hình dạng khỏi tập hợp hình dạng. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Sao chép tất cả các phần tử từ tập hợp vào mảng được chỉ định. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Trả về một bộ liệt kê cho phép duyệt qua tập hợp. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của hình dạng được chỉ định trong tập hợp. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Tạo một khung âm thanh mới liên kết với một track CD và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Tạo một khung âm thanh mới và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định bằng cách sử dụng đối tượng âm thanh hiện có từ danh sách Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Tạo một khung âm thanh mới với tệp WAV được nhúng và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. Âm thanh được nhúng sẽ được thêm vào tập hợp Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Tạo một khung âm thanh mới liên kết với tệp âm thanh bên ngoài và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Tạo một hình dạng tự động mới và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định, áp dụng định dạng mẫu mặc định. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Tạo một hình dạng tự động mới và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định, tùy chọn khởi tạo với kiểu mẫu mặc định. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Tạo một bản sao của hình dạng được chỉ định và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. Hình dạng sao chép giữ nguyên vị trí và kích thước của hình dạng gốc. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Tạo một bản sao của hình dạng được chỉ định và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. Hình dạng mới giữ nguyên chiều rộng và chiều cao của *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Tạo một bản sao của hình dạng được chỉ định và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Tạo một hình dạng kết nối mới và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định, áp dụng kiểu mẫu mặc định. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Tạo một hình dạng kết nối mới và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định, tùy chọn áp dụng kiểu mẫu mặc định. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Tạo một nhóm hình dạng rỗng mới và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. Khung của nhóm sẽ tự động điều chỉnh để vừa với bất kỳ hình dạng nào được thêm vào. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Tạo một khung đối tượng OLE mới và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Tạo một khung đối tượng OLE mới và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Tạo một khung ảnh mới chứa hình ảnh được chỉ định và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Tạo một khung Zoom Section mới và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Tạo một khung Zoom Section mới với hình ảnh được định sẵn và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Tạo một khung Summary Zoom mới và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Tạo một bảng mới và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Tạo một khung video mới và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Tạo một khung Zoom mới và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Tạo một khung Zoom mới với hình ảnh được định sẵn và chèn nó vào tập hợp hình dạng tại chỉ mục được chỉ định. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Xóa lần xuất hiện đầu tiên của hình dạng được chỉ định khỏi tập hợp hình dạng. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Xóa hình dạng tại chỉ mục được chỉ định khỏi tập hợp hình dạng. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Di chuyển hình dạng được chỉ định đến vị trí mới trong tập hợp hình dạng. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Di chuyển các hình dạng được chỉ định trong tập hợp hình dạng, đặt chúng bắt đầu từ chỉ mục đã cho. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Tạo và trả về một mảng chứa tất cả các hình dạng. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Tạo và trả về một mảng chứa tất cả các hình dạng trong phạm vi được chỉ định. |

### Xem thêm

* lớp [DomObject&lt;TParent&gt;](../domobject-1)
* lớp [GroupShape](../groupshape)
* giao diện [IShapeCollection](../ishapecollection)
* không gian tên [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->