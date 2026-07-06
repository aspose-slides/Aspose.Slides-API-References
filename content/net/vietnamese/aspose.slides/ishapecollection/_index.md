---
title: IShapeCollection
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn một bộ sưu tập các hình dạng.
type: docs
weight: 6980
url: /vi/aspose.slides/ishapecollection/
---
## IShapeCollection giao diện

Biểu diễn một bộ sưu tập các hình dạng.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Lấy đối tượng nhóm cha cho bộ sưu tập các hình dạng. Chỉ đọc [`IGroupShape`](../igroupshape). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Tạo một khung âm thanh mới được liên kết với một rãnh CD và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Tạo một khung âm thanh mới và thêm nó vào cuối bộ sưu tập hình dạng bằng cách sử dụng một đối tượng âm thanh hiện có từ danh sách Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Tạo một khung âm thanh mới với tệp WAV được nhúng và thêm nó vào cuối bộ sưu tập hình dạng. Âm thanh được nhúng sẽ được thêm vào bộ sưu tập Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Tạo một khung âm thanh mới được liên kết với tệp âm thanh bên ngoài và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Tạo một hình dạng tự động mới với định dạng mặc định và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Tạo một hình dạng tự động mới và thêm nó vào cuối bộ sưu tập hình dạng, tùy chọn khởi tạo nó với định dạng mẫu mặc định. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu cho chuỗi, và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu cho chuỗi, và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Tạo một bản sao của hình dạng được chỉ định và thêm nó vào cuối bộ sưu tập hình dạng. Hình dạng sao chép giữ nguyên vị trí và kích thước của bản gốc. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Tạo một bản sao của hình dạng được chỉ định và thêm nó vào cuối bộ sưu tập hình dạng. Hình dạng mới giữ nguyên chiều rộng và chiều cao của *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Tạo một bản sao của hình dạng được chỉ định và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Tạo một hình kết nối mới với kiểu mẫu mặc định và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Tạo một hình kết nối mới và thêm nó vào cuối bộ sưu tập hình dạng, tùy chọn áp dụng kiểu mẫu mặc định. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Tạo một nhóm hình dạng trống mới và thêm nó vào cuối bộ sưu tập hình dạng. Khung của nhóm sẽ tự động điều chỉnh để chứa bất kỳ hình dạng nào được thêm vào. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Tạo một nhóm hình dạng mới, chuyển đổi hình ảnh SVG được chỉ định thành các hình dạng riêng lẻ, và thêm nhóm tạo được vào cuối bộ sưu tập hình dạng. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Tạo một hình dạng tự động hình chữ nhật mới để chứa nội dung toán học và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Tạo một khung đối tượng OLE mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Tạo một khung đối tượng OLE mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Tạo một khung ảnh mới chứa hình ảnh được chỉ định và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Tạo một khung Section Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Tạo một khung Section Zoom mới với hình ảnh được định sẵn và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Tạo một sơ đồ SmartArt và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Tạo một khung Summary Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Tạo một bảng mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Tạo một khung video mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Tạo một khung video mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Tạo một khung Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Tạo một khung Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Xóa tất cả các hình dạng khỏi bộ sưu tập hình dạng. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của hình dạng được chỉ định trong bộ sưu tập. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Tạo một khung âm thanh mới được liên kết với một rãnh CD và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Tạo một khung âm thanh mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định bằng cách sử dụng một đối tượng âm thanh hiện có từ danh sách Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Tạo một khung âm thanh mới với tệp WAV được nhúng và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. Âm thanh được nhúng sẽ được thêm vào bộ sưu tập Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Tạo một khung âm thanh mới được liên kết với tệp âm thanh bên ngoài và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Tạo một hình dạng tự động mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định, áp dụng định dạng mẫu mặc định. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Tạo một hình dạng tự động mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định, tùy chọn khởi tạo nó với kiểu mẫu mặc định. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu cho chuỗi, và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu cho chuỗi, và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Tạo một bản sao của hình dạng được chỉ định và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. Hình dạng sao chép giữ nguyên vị trí và kích thước của bản gốc. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Tạo một bản sao của hình dạng được chỉ định và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. Hình dạng mới giữ nguyên chiều rộng và chiều cao của *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Tạo một bản sao của hình dạng được chỉ định và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Tạo một hình kết nối mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định, áp dụng kiểu mẫu mặc định. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Tạo một hình kết nối mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định, tùy chọn áp dụng kiểu mẫu mặc định. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Tạo một nhóm hình dạng trống mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. Khung của nhóm sẽ tự động điều chỉnh để chứa bất kỳ hình dạng nào được thêm vào. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Tạo một khung ảnh mới chứa hình ảnh được chỉ định và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Tạo một khung Section Zoom mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Tạo một khung Section Zoom mới với hình ảnh được định sẵn và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Tạo một khung Summary Zoom mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Tạo một bảng mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Tạo một khung video mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Tạo một khung Zoom mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Tạo một khung Zoom mới với hình ảnh được định sẵn và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Xóa lần xuất hiện đầu tiên của hình dạng được chỉ định khỏi bộ sưu tập hình dạng. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Xóa hình dạng tại chỉ mục được chỉ định khỏi bộ sưu tập hình dạng. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Di chuyển hình dạng được chỉ định tới vị trí mới trong bộ sưu tập hình dạng. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Di chuyển các hình dạng được chỉ định trong bộ sưu tập hình dạng, đặt chúng bắt đầu tại chỉ mục đã cho. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Tạo và trả về một mảng chứa tất cả các hình dạng. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Tạo và trả về một mảng chứa tất cả các hình dạng trong khoảng đã chỉ định. |

### Xem thêm

* giao diện [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* giao diện [IShape](../ishape)
* không gian tên [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->