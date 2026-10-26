---
title: IShapeCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một bộ sưu tập các hình dạng.
type: docs
url: /vi/com.aspose.slides/ishapecollection/
---
**Tất cả các giao diện đã triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Đại diện cho một bộ sưu tập các hình dạng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [getParentGroup()](#getParentGroup--) | Lấy đối tượng nhóm cha cho bộ sưu tập các hình dạng. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Tạo một biểu đồ mới, khởi tạo với dữ liệu chuỗi mẫu và cài đặt, và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Tạo một biểu đồ mới, khởi tạo với dữ liệu chuỗi mẫu và cài đặt, và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Tạo một sơ đồ SmartArt và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Tạo một biểu đồ mới, khởi tạo với dữ liệu chuỗi mẫu và cài đặt, và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Tạo một biểu đồ mới, khởi tạo với dữ liệu chuỗi mẫu và cài đặt, và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Tạo một khung đối tượng OLE mới và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Tạo một khung đối tượng OLE mới và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Tạo một khung Zoom mới và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Tạo một khung Zoom mới và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Tạo một khung Zoom mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Tạo một khung Zoom mới với hình ảnh đã định trước và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Tạo một khung Section Zoom mới và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Tạo một khung Section Zoom mới với hình ảnh đã định trước và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Tạo một khung Section Zoom mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Tạo một khung Section Zoom mới với hình ảnh đã định trước và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Tạo một khung Summary Zoom mới và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Tạo một khung Summary Zoom mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Tạo một khung video mới và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Tạo một khung video mới và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Tạo một khung video mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Tạo một khung âm thanh mới liên kết tới bản ghi CD và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Tạo một khung âm thanh mới liên kết tới bản ghi CD và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Tạo một khung âm thanh mới liên kết tới tệp âm thanh bên ngoài và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Tạo một khung âm thanh mới liên kết tới tệp âm thanh bên ngoài và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Tạo một khung âm thanh mới với tệp WAV nhúng và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Tạo một khung âm thanh mới và thêm nó vào cuối bộ sưu tập các hình dạng bằng cách sử dụng một đối tượng âm thanh hiện có trong danh sách Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Tạo một khung âm thanh mới với tệp WAV nhúng và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Tạo một khung âm thanh mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định bằng cách sử dụng một đối tượng âm thanh hiện có trong danh sách Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của hình dạng đã chỉ định trong bộ sưu tập. |
| [toArray()](#toArray--) | Tạo và trả về một mảng chứa tất cả các hình dạng. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tạo và trả về một mảng chứa tất cả các hình dạng trong phạm vi đã chỉ định. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Di chuyển hình dạng đã chỉ định đến vị trí mới trong bộ sưu tập các hình dạng. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Di chuyển các hình dạng đã chỉ định trong bộ sưu tập các hình dạng, đặt chúng bắt đầu ở chỉ mục đã cho. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Tạo một auto shape mới với định dạng mặc định và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Tạo một auto shape mới và thêm nó vào cuối bộ sưu tập các hình dạng, tùy chọn khởi tạo với định dạng mẫu mặc định. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Tạo một auto shape hình chữ nhật mới để chứa nội dung toán học và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Tạo một auto shape mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định, áp dụng định dạng mẫu mặc định. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Tạo một auto shape mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định, tùy chọn khởi tạo với kiểu mẫu mặc định. |
| [addGroupShape()](#addGroupShape--) | Tạo một nhóm shape trống mới và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Tạo một nhóm shape mới, chuyển đổi hình ảnh SVG đã chỉ định thành các shape riêng lẻ, và thêm nhóm kết quả vào cuối bộ sưu tập các hình dạng. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Tạo một nhóm shape trống mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Tạo một connector shape mới với kiểu mẫu mặc định và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Tạo một connector shape mới và thêm nó vào cuối bộ sưu tập các hình dạng, tùy chọn áp dụng kiểu mẫu mặc định. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Tạo một connector shape mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định, áp dụng kiểu mẫu mặc định. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Tạo một connector shape mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định, tùy chọn áp dụng kiểu mẫu mặc định. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Tạo một picture frame mới chứa hình ảnh đã chỉ định và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Tạo một picture frame mới chứa hình ảnh đã chỉ định và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Tạo một bảng mới và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Tạo một bảng mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa hình dạng tại chỉ mục đã chỉ định khỏi bộ sưu tập các hình dạng. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Xóa lần xuất hiện đầu tiên của hình dạng đã chỉ định khỏi bộ sưu tập các hình dạng. |
| [clear()](#clear--) | Xóa tất cả các hình dạng khỏi bộ sưu tập các hình dạng. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Tạo một bản sao của hình dạng đã chỉ định và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Tạo một bản sao của hình dạng đã chỉ định và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Tạo một bản sao của hình dạng đã chỉ định và thêm nó vào cuối bộ sưu tập các hình dạng. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Tạo một bản sao của hình dạng đã chỉ định và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Tạo một bản sao của hình dạng đã chỉ định và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Tạo một bản sao của hình dạng đã chỉ định và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Lấy phần tử tại chỉ mục đã chỉ định. Chỉ-đọc [IShape](../../com.aspose.slides/ishape).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Lấy đối tượng nhóm cha cho bộ sưu tập các hình dạng. Chỉ-đọc [IGroupShape](../../com.aspose.slides/igroupshape).

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Tạo một biểu đồ mới, khởi tạo với dữ liệu chuỗi mẫu và cài đặt, và thêm nó vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại biểu đồ cần thêm. |
| x | float | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | float | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | float | Chiều rộng của biểu đồ, tính bằng điểm. |
| height | float | Chiều cao của biểu đồ, tính bằng điểm. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) mới được tạo.

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Tạo một biểu đồ mới, khởi tạo với dữ liệu chuỗi mẫu và cài đặt, và thêm nó vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại biểu đồ cần thêm. |
| x | float | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | float | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | float | Chiều rộng của biểu đồ, tính bằng điểm. |
| height | float | Chiều cao của biểu đồ, tính bằng điểm. |
| initWithSample | boolean | true để khởi tạo biểu đồ mới với dữ liệu chuỗi mẫu và cài đặt; false để tạo biểu đồ không có chuỗi và chỉ có cài đặt tối thiểu, giúp tạo nhanh hơn. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) mới được tạo.

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Tạo một sơ đồ SmartArt và thêm nó vào cuối bộ sưu tập các hình dạng.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung sơ đồ, tính bằng điểm. |
| y | float | Tọa độ y của khung sơ đồ, tính bằng điểm. |
| width | float | Chiều rộng của khung sơ đồ, tính bằng điểm. |
| height | float | Chiều cao của khung sơ đồ, tính bằng điểm. |
| layoutType | int | Loại bố cục SmartArt. |

**Trả về:**
[ISmartArt](../../com.aspose.slides/ismartart) - [ISmartArt](../../com.aspose.slides/ismartart) mới được tạo.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Tạo một biểu đồ mới, khởi tạo với dữ liệu chuỗi mẫu và cài đặt, và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại biểu đồ cần tạo. |
| x | float | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | float | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | float | Chiều rộng của biểu đồ mới, tính bằng điểm. |
| height | float | Chiều cao của biểu đồ mới, tính bằng điểm. |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn biểu đồ mới vào bộ sưu tập các hình dạng. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) mới được tạo.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Tạo một biểu đồ mới, khởi tạo với dữ liệu chuỗi mẫu và cài đặt, và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại biểu đồ cần tạo. |
| x | float | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | float | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | float | Chiều rộng của biểu đồ mới, tính bằng điểm. |
| height | float | Chiều cao của biểu đồ mới, tính bằng điểm. |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn biểu đồ mới vào bộ sưu tập các hình dạng. |
| initWithSample | boolean | true để khởi tạo biểu đồ mới với dữ liệu chuỗi mẫu và cài đặt; false để tạo biểu đồ không có chuỗi và chỉ có cài đặt tối thiểu, giúp tạo nhanh hơn. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) mới được tạo.

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Tạo một khung đối tượng OLE mới và thêm nó vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | float | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | float | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | float | Chiều cao của khung OLE mới, tính bằng điểm. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Thông tin dữ liệu OLE nhúng ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Trả về:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) mới được tạo.

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Tạo một khung đối tượng OLE mới và thêm nó vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | float | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | float | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | float | Chiều cao của khung OLE mới, tính bằng điểm. |
| className | java.lang.String | Tên lớp của đối tượng OLE. |
| path | java.lang.String | Đường dẫn tới tệp liên kết.

Đường dẫn này được lưu nguyên trong bản trình chiếu. Nếu chỉ định đường dẫn tương đối, tệp sẽ không thể truy cập khi mở bản trình chiếu từ thư mục khác. |

**Trả về:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) mới được tạo.

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn khung OLE. |
| x | float | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | float | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | float | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | float | Chiều cao của khung OLE mới, tính bằng điểm. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Thông tin dữ liệu OLE nhúng ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Trả về:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) mới được tạo.

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn khung OLE. |
| x | float | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | float | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | float | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | float | Chiều cao của khung OLE mới, tính bằng điểm. |
| className | java.lang.String | Tên lớp của đối tượng OLE. |
| path | java.lang.String | Đường dẫn tới tệp liên kết.

Đường dẫn này được lưu nguyên trong bản trình chiếu. Nếu chỉ định đường dẫn tương đối, tệp sẽ không thể truy cập khi mở bản trình chiếu từ thư mục khác. |

**Trả về:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) mới được tạo.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Tạo một khung Zoom mới và thêm nó vào cuối bộ sưu tập các hình dạng.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Zoom mới, tính bằng điểm. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) được tham chiếu bởi khung Zoom; phải thuộc bản trình chiếu này. |

**Trả về:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) mới được tạo.

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Tạo một khung Zoom mới và thêm nó vào cuối bộ sưu tập các hình dạng.

--------------------

> ```
> Ví dụ này minh họa cách thêm một đối tượng Zoom vào cuối một bộ sưu tập
>  (giả sử có ít nhất hai slide trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Zoom mới, tính bằng điểm. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) được tham chiếu bởi khung Zoom; phải thuộc bản trình chiếu này. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Hình ảnh cho slide được tham chiếu [IPPImage](../../com.aspose.slides/ippimage). |

**Trả về:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) mới được tạo.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Tạo một khung Zoom mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

--------------------

> ```
> Ví dụ này minh họa việc tạo và chèn một đối tượng Zoom vào vị trí chỉ định trong một bộ sưu tập
>  (giả sử có ít nhất hai slide trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn khung Zoom. |
| x | float | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Zoom mới, tính bằng điểm. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) được tham chiếu bởi khung Zoom. |

**Trả về:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) mới được tạo.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Tạo một khung Zoom mới với hình ảnh đã định trước và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

--------------------

> ```
> Ví dụ này minh họa việc tạo và chèn một đối tượng Zoom vào vị trí chỉ định trong một bộ sưu tập
>  (giả sử có ít nhất hai slide trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn khung Zoom. |
| x | float | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Zoom mới, tính bằng điểm. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) được tham chiếu bởi khung Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Hình ảnh cho slide được tham chiếu [IPPImage](../../com.aspose.slides/ippimage). |

**Trả về:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) mới được tạo.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Tạo một khung Section Zoom mới và thêm nó vào cuối bộ sưu tập các hình dạng.

--------------------

> ```
> Ví dụ này minh họa cách thêm một đối tượng Section Zoom vào cuối một bộ sưu tập
>  (giả sử có ít nhất hai phần trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Section Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Section Zoom mới, tính bằng điểm. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc bản trình chiếu này và chứa ít nhất một slide. |

**Trả về:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới được tạo.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Tạo một khung Section Zoom mới với hình ảnh đã định trước và thêm nó vào cuối bộ sưu tập các hình dạng.

--------------------

> ```
> Ví dụ này minh họa cách thêm một đối tượng Section Zoom vào cuối một bộ sưu tập
>  (giả sử có ít nhất hai phần trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Section Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Section Zoom mới, tính bằng điểm. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc bản trình chiếu này và chứa ít nhất một slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) sẽ hiển thị trong khung Section Zoom. |

**Trả về:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới được tạo.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Tạo một khung Section Zoom mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

--------------------

> ```
> Ví dụ này minh họa việc tạo và chèn một đối tượng Section Zoom vào vị trí chỉ định trong một bộ sưu tập
>  (giả sử có ít nhất hai phần trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn khung Section Zoom. |
| x | float | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Section Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Section Zoom mới, tính bằng điểm. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc bản trình chiếu này và chứa ít nhất một slide. |

**Trả về:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới được tạo.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Tạo một khung Section Zoom mới với hình ảnh đã định trước và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

--------------------

> ```
> Ví dụ này minh họa việc tạo và chèn một đối tượng Section Zoom vào vị trí chỉ định trong một bộ sưu tập
>  (giả sử có ít nhất hai phần trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn khung Section Zoom. |
| x | float | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Section Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Section Zoom mới, tính bằng điểm. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc bản trình chiếu này và chứa ít nhất một slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Hình ảnh sẽ hiển thị trong khung Section Zoom. |

**Trả về:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới được tạo.

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Tạo một khung Summary Zoom mới và thêm nó vào cuối bộ sưu tập các hình dạng.

--------------------

> ```
> Ví dụ này minh họa cách thêm một đối tượng Summary Zoom vào cuối một bộ sưu tập
>  (giả sử có ít nhất hai phần trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung Summary Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Summary Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Summary Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Summary Zoom mới, tính bằng điểm. |

--------------------

Phương thức này tạo một Summary Zoom frame tổng hợp các liên kết tóm tắt cho tất cả các phần trong bản trình chiếu. |

**Trả về:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) mới được tạo.

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Tạo một Summary Zoom frame mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

--------------------

> ```
> Ví dụ này minh họa việc tạo và chèn một đối tượng Summary Zoom vào vị trí chỉ định trong một bộ sưu tập
>  (giả sử có ít nhất hai phần trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn Summary Zoom frame. |
| x | float | Tọa độ x của Summary Zoom frame mới, tính bằng điểm. |
| y | float | Tọa độ y của Summary Zoom frame mới, tính bằng điểm. |
| width | float | Chiều rộng của Summary Zoom frame mới, tính bằng điểm. |
| height | float | Chiều cao của Summary Zoom frame mới, tính bằng điểm. |

--------------------

Phương thức này tạo một Summary Zoom frame tổng hợp các liên kết tóm tắt cho tất cả các phần trong bản trình chiếu. |

**Trả về:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) mới được tạo.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Tạo một khung video mới và thêm nó vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung video mới, tính bằng điểm. |
| y | float | Tọa độ y của khung video mới, tính bằng điểm. |
| width | float | Chiều rộng của khung video mới, tính bằng điểm. |
| height | float | Chiều cao của khung video mới, tính bằng điểm. |
| fname | java.lang.String | Đường dẫn hoặc tên tệp video để nhúng. |

**Trả về:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) mới được tạo.

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Tạo một khung video mới và thêm nó vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung video mới, tính bằng điểm. |
| y | float | Tọa độ y của khung video mới, tính bằng điểm. |
| width | float | Chiều rộng của khung video mới, tính bằng điểm. |
| height | float | Chiều cao của khung video mới, tính bằng điểm. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) để nhúng trong khung video. |

**Trả về:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) mới được tạo.

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Tạo một khung video mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn khung video. |
| x | float | Tọa độ x của khung video mới, tính bằng điểm. |
| y | float | Tọa độ y của khung video mới, tính bằng điểm. |
| width | float | Chiều rộng của khung video mới, tính bằng điểm. |
| height | float | Chiều cao của khung video mới, tính bằng điểm. |
| fname | java.lang.String | Đường dẫn hoặc tên tệp video để nhúng. |

**Trả về:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) mới được tạo.

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Tạo một khung âm thanh mới liên kết tới bản ghi CD và thêm nó vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Tạo một khung âm thanh mới liên kết tới bản ghi CD và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn khung âm thanh. |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Tạo một khung âm thanh mới liên kết tới tệp âm thanh bên ngoài và thêm nó vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |
| fname | java.lang.String | Đường dẫn hoặc tên tệp âm thanh bên ngoài để liên kết. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Tạo một khung âm thanh mới liên kết tới tệp âm thanh bên ngoài và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn khung âm thanh. |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |
| fname | java.lang.String | Đường dẫn hoặc tên tệp âm thanh bên ngoài để liên kết. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Tạo một khung âm thanh mới với tệp WAV nhúng và thêm nó vào cuối bộ sưu tập các hình dạng. Âm thanh nhúng được thêm vào bộ sưu tập Presentation.Audios.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |
| audio_stream | java.io.InputStream | Luồng đầu vào chứa dữ liệu âm thanh WAV để nhúng. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Tạo một khung âm thanh mới và thêm nó vào cuối bộ sưu tập các hình dạng bằng cách sử dụng một đối tượng âm thanh hiện có trong danh sách Presentation.Audios.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Một thể hiện [IAudio](../../com.aspose.slides/iaudio) từ bộ sưu tập Presentation.Audios. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Tạo một khung âm thanh mới với tệp WAV nhúng và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. Âm thanh nhúng được thêm vào bộ sưu tập Presentation.Audios.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn khung âm thanh. |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |
| audio_stream | java.io.InputStream | Luồng đầu vào chứa dữ liệu âm thanh WAV để nhúng. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Tạo một khung âm thanh mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định bằng cách sử dụng một đối tượng âm thanh hiện có trong danh sách Presentation.Audios.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn khung âm thanh. |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Một thể hiện [IAudio](../../com.aspose.slides/iaudio) từ bộ sưu tập Presentation.Audios để nhúng. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của hình dạng đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Hình dạng cần tìm trong bộ sưu tập. |

**Trả về:**
int - Chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của hình dạng trong bộ sưu tập nếu tìm thấy; nếu không, \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Tạo và trả về một mảng chứa tất cả các hình dạng.

**Trả về:**
com.aspose.slides.IShape[] - Một mảng các đối tượng [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Tạo và trả về một mảng chứa tất cả các hình dạng trong phạm vi đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| startIndex | int | Chỉ mục của hình dạng đầu tiên cần trả về. |
| count | int | Số lượng hình dạng cần trả về. |

**Trả về:**
com.aspose.slides.IShape[] - Một mảng các đối tượng [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Di chuyển hình dạng đã chỉ định đến vị trí mới trong bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục đích bắt đầu từ 0 nơi hình dạng sẽ được đặt. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) cần di chuyển trong bộ sưu tập. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Di chuyển các hình dạng đã chỉ định trong bộ sưu tập các hình dạng, đặt chúng bắt đầu ở chỉ mục đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục đích bắt đầu từ 0 nơi hình dạng đầu tiên sẽ được đặt; các hình dạng tiếp theo sẽ theo thứ tự đã cung cấp. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Một hoặc nhiều thể hiện [IShape](../../com.aspose.slides/ishape) để di chuyển trong bộ sưu tập. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Tạo một auto shape mới với định dạng mặc định và thêm nó vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của auto shape cần thêm. |
| x | float | Tọa độ x của khung shape, tính bằng điểm. |
| y | float | Tọa độ y của khung shape, tính bằng điểm. |
| width | float | Chiều rộng của khung shape, tính bằng điểm. |
| height | float | Chiều cao của khung shape, tính bằng điểm. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới được tạo.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một auto shape mới và thêm nó vào cuối bộ sưu tập các hình dạng, tùy chọn khởi tạo với định dạng mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của auto shape cần thêm. |
| x | float | Tọa độ x của khung shape, tính bằng điểm. |
| y | float | Tọa độ y của khung shape, tính bằng điểm. |
| width | float | Chiều rộng của khung shape, tính bằng điểm. |
| height | float | Chiều cao của khung shape, tính bằng điểm. |
| createFromTemplate | boolean | true để áp dụng kiểu mẫu mặc định (kiểu đơn giản, văn bản căn giữa, và tên không rỗng) cho shape mới; false để tạo shape với tất cả thuộc tính mặc định. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới được tạo.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Tạo một auto shape hình chữ nhật mới để chứa nội dung toán học và thêm nó vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung shape, tính bằng điểm. |
| y | float | Tọa độ y của khung shape, tính bằng điểm. |
| width | float | Chiều rộng của khung shape, tính bằng điểm. |
| height | float | Chiều cao của khung shape, tính bằng điểm. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới được tạo.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Tạo một auto shape mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định, áp dụng định dạng mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn auto shape mới. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của auto shape cần chèn. |
| x | float | Tọa độ x của khung shape, tính bằng điểm. |
| y | float | Tọa độ y của khung shape, tính bằng điểm. |
| width | float | Chiều rộng của khung shape, tính bằng điểm. |
| height | float | Chiều cao của khung shape, tính bằng điểm. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới được tạo.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một auto shape mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định, tùy chọn khởi tạo với kiểu mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn auto shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của auto shape cần chèn. |
| x | float | Tọa độ x của khung shape, tính bằng điểm. |
| y | float | Tọa độ y của khung shape, tính bằng điểm. |
| width | float | Chiều rộng của khung shape, tính bằng điểm. |
| height | float | Chiều cao của khung shape, tính bằng điểm. |
| createFromTemplate | boolean | true để áp dụng kiểu mẫu mặc định (bao gồm tên không rỗng, kiểu đơn giản, và văn bản căn giữa); false để tạo shape với tất cả thuộc tính mặc định. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới được tạo.

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Tạo một nhóm shape trống mới và thêm nó vào cuối bộ sưu tập các hình dạng. Khung của nhóm sẽ tự động điều chỉnh để phù hợp với bất kỳ shape nào được thêm vào.

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) mới được tạo.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Tạo một nhóm shape mới, chuyển đổi SVG image đã chỉ định thành các shape riêng lẻ, và thêm nhóm kết quả vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) chứa nội dung vector để chuyển thành shape. |
| x | float | Tọa độ x của khung nhóm, tính bằng điểm. |
| y | float | Tọa độ y của khung nhóm, tính bằng điểm. |
| width | float | Chiều rộng của khung nhóm, tính bằng điểm. |
| height | float | Chiều cao của khung nhóm, tính bằng điểm. |

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) mới được tạo.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Tạo một nhóm shape trống mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. Khung của nhóm sẽ tự động điều chỉnh để phù hợp với bất kỳ shape nào được thêm vào.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn nhóm shape. |

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) mới được tạo.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Tạo một connector shape mới với kiểu mẫu mặc định và thêm nó vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của connector shape cần thêm. |
| x | float | Tọa độ x của khung connector, tính bằng điểm. |
| y | float | Tọa độ y của khung connector, tính bằng điểm. |
| width | float | Chiều rộng của khung connector, tính bằng điểm. |
| height | float | Chiều cao của khung connector, tính bằng điểm. |

**Trả về:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) mới được tạo.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một connector shape mới và thêm nó vào cuối bộ sưu tập các hình dạng, tùy chọn áp dụng kiểu mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của connector shape cần tạo. |
| x | float | Tọa độ x của khung connector, tính bằng điểm. |
| y | float | Tọa độ y của khung connector, tính bằng điểm. |
| width | float | Chiều rộng của khung connector, tính bằng điểm. |
| height | float | Chiều cao của khung connector, tính bằng điểm. |
| createFromTemplate | boolean | true để áp dụng kiểu mẫu mặc định (tên không rỗng, kiểu đơn giản); false để tạo connector với các giá trị thuộc tính mặc định. |

**Trả về:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) mới được tạo.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Tạo một connector shape mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định, áp dụng kiểu mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn connector shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của connector shape cần chèn. |
| x | float | Tọa độ x của khung connector, tính bằng điểm. |
| y | float | Tọa độ y của khung connector, tính bằng điểm. |
| width | float | Chiều rộng của khung connector, tính bằng điểm. |
| height | float | Chiều cao của khung connector, tính bằng điểm. |

**Trả về:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) mới được tạo.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một connector shape mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định, tùy chọn áp dụng kiểu mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn connector shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của connector shape cần chèn. |
| x | float | Tọa độ x của khung connector, tính bằng điểm. |
| y | float | Tọa độ y của khung connector, tính bằng điểm. |
| width | float | Chiều rộng của khung connector, tính bằng điểm. |
| height | float | Chiều cao của khung connector, tính bằng điểm. |
| createFromTemplate | boolean | true để áp dụng kiểu mẫu mặc định (tên không rỗng, kiểu đơn giản); false để tạo connector với các giá trị thuộc tính mặc định. |

**Trả về:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) mới được tạo.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Tạo một picture frame mới chứa hình ảnh đã chỉ định và thêm nó vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | Xác định loại shape chứa trong [ShapeType](../../com.aspose.slides/shapetype), ngoại trừ mọi loại đường thẳng: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Tọa độ x của picture frame, tính bằng điểm. |
| y | float | Tọa độ y của picture frame, tính bằng điểm. |
| width | float | Chiều rộng của picture frame, tính bằng điểm. |
| height | float | Chiều cao của picture frame, tính bằng điểm. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) để hiển thị trong picture frame. |

**Trả về:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) mới được tạo.

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Tạo một picture frame mới chứa hình ảnh đã chỉ định và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn picture frame. |
| shapeType | int | Xác định loại shape chứa trong [ShapeType](../../com.aspose.slides/shapetype), ngoại trừ mọi loại đường thẳng: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Tọa độ x của picture frame, tính bằng điểm. |
| y | float | Tọa độ y của picture frame, tính bằng điểm. |
| width | float | Chiều rộng của picture frame, tính bằng điểm. |
| height | float | Chiều cao của picture frame, tính bằng điểm. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) để hiển thị trong picture frame. |

**Trả về:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) mới được tạo.

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Tạo một bảng mới và thêm nó vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của bảng, tính bằng điểm. |
| y | float | Tọa độ y của bảng, tính bằng điểm. |
| columnWidths | double[] | Một mảng double đại diện cho độ rộng của các cột bảng, tính bằng điểm. |
| rowHeights | double[] | Một mảng double đại diện cho độ cao của các hàng bảng, tính bằng điểm. |

**Trả về:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) mới được tạo.

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Tạo một bảng mới và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn bảng. |
| x | float | Tọa độ x của bảng, tính bằng điểm. |
| y | float | Tọa độ y của bảng, tính bằng điểm. |
| columnWidths | double[] | Một mảng double đại diện cho độ rộng của các cột bảng, tính bằng điểm. |
| rowHeights | double[] | Một mảng double đại diện cho độ cao của các hàng bảng, tính bằng điểm. |

**Trả về:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) mới được tạo.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa hình dạng tại chỉ mục đã chỉ định khỏi bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của hình dạng cần xóa. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Xóa lần xuất hiện đầu tiên của hình dạng đã chỉ định khỏi bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) cần xóa. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các hình dạng khỏi bộ sưu tập các hình dạng.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Tạo một bản sao của hình dạng đã chỉ định và thêm nó vào cuối bộ sưu tập các hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Hình dạng cần sao chép. |
| x | float | Tọa độ x của khung hình dạng sao chép, tính bằng điểm. |
| y | float | Tọa độ y của khung hình dạng sao chép, tính bằng điểm. |
| width | float | Chiều rộng của khung hình dạng sao chép, tính bằng điểm. |
| height | float | Chiều cao của khung hình dạng sao chép, tính bằng điểm. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới được tạo.

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Tạo một bản sao của hình dạng đã chỉ định và thêm nó vào cuối bộ sưu tập các hình dạng. Hình dạng mới giữ nguyên chiều rộng và chiều cao của sourceShape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) cần sao chép. |
| x | float | Tọa độ x của khung hình dạng sao chép, tính bằng điểm. |
| y | float | Tọa độ y của khung hình dạng sao chép, tính bằng điểm. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới được tạo.

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Tạo một bản sao của hình dạng đã chỉ định và thêm nó vào cuối bộ sưu tập các hình dạng. Hình dạng sao chép giữ nguyên vị trí và kích thước gốc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) cần sao chép. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới được tạo.

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Tạo một bản sao của hình dạng đã chỉ định và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn hình dạng sao chép. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) cần sao chép. |
| x | float | Tọa độ x của khung hình dạng sao chép, tính bằng điểm. |
| y | float | Tọa độ y của khung hình dạng sao chép, tính bằng điểm. |
| width | float | Chiều rộng của khung hình dạng sao chép, tính bằng điểm. |
| height | float | Chiều cao của khung hình dạng sao chép, tính bằng điểm. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới được tạo.

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Tạo một bản sao của hình dạng đã chỉ định và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. Hình dạng mới giữ nguyên chiều rộng và chiều cao của sourceShape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn hình dạng sao chép. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) cần sao chép. |
| x | float | Tọa độ x của khung hình dạng sao chép, tính bằng điểm. |
| y | float | Tọa độ y của khung hình dạng sao chép, tính bằng điểm. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới được tạo.

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Tạo một bản sao của hình dạng đã chỉ định và chèn nó vào bộ sưu tập các hình dạng tại chỉ mục đã chỉ định. Hình dạng sao chép giữ nguyên vị trí và kích thước gốc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi chèn hình dạng sao chép. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) cần sao chép. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới được tạo.