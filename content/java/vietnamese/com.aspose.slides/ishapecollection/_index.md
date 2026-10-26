---
title: IShapeCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một bộ sưu tập các hình dạng.
type: docs
url: /vi/com.aspose.slides/ishapecollection/
---
**Tất cả các giao diện được thực hiện:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Mô tả một tập hợp các shape.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ số đã chỉ định. |
| [getParentGroup()](#getParentGroup--) | Lấy đối tượng nhóm shape cha cho shape collection. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Tạo một chart mới, khởi tạo nó với dữ liệu mẫu cho series và các cài đặt, và thêm nó vào cuối shape collection. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Tạo một chart mới, khởi tạo nó với dữ liệu mẫu cho series và các cài đặt, và thêm nó vào cuối shape collection. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Tạo một SmartArt diagram và thêm nó vào cuối shape collection. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Tạo một chart mới, khởi tạo nó với dữ liệu mẫu cho series và các cài đặt, và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Tạo một chart mới, khởi tạo nó với dữ liệu mẫu cho series và các cài đặt, và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Tạo một OLE object frame mới và thêm nó vào cuối shape collection. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Tạo một OLE object frame mới và thêm nó vào cuối shape collection. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Tạo một OLE object frame mới và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Tạo một OLE object frame mới và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Tạo một Zoom frame mới và thêm nó vào cuối shape collection. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Tạo một Zoom frame mới và thêm nó vào cuối shape collection. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Tạo một Zoom frame mới và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Tạo một Zoom frame mới với hình ảnh được định trước và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Tạo một Section Zoom frame mới và thêm nó vào cuối shape collection. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Tạo một Section Zoom frame mới với hình ảnh được định trước và thêm nó vào cuối shape collection. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Tạo một Section Zoom frame mới và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Tạo một Section Zoom frame mới với hình ảnh được định trước và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Tạo một Summary Zoom frame mới và thêm nó vào cuối shape collection. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Tạo một Summary Zoom frame mới và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Tạo một video frame mới và thêm nó vào cuối shape collection. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Tạo một video frame mới và thêm nó vào cuối shape collection. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Tạo một video frame mới và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Tạo một audio frame mới liên kết tới một track CD và thêm nó vào cuối shape collection. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Tạo một audio frame mới liên kết tới một track CD và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Tạo một audio frame mới liên kết tới một tệp audio bên ngoài và thêm nó vào cuối shape collection. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Tạo một audio frame mới liên kết tới một tệp audio bên ngoài và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Tạo một audio frame mới với tệp WAV nhúng và thêm nó vào cuối shape collection. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Tạo một audio frame mới và thêm nó vào cuối shape collection bằng cách sử dụng một đối tượng audio hiện có từ danh sách Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Tạo một audio frame mới với tệp WAV nhúng và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Tạo một audio frame mới và chèn nó vào shape collection tại chỉ số đã chỉ định bằng cách sử dụng một đối tượng audio hiện có từ danh sách Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Trả về chỉ số dựa trên zero của lần xuất hiện đầu tiên của shape được chỉ định trong collection. |
| [toArray()](#toArray--) | Tạo và trả về một mảng chứa tất cả các shape. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tạo và trả về một mảng chứa tất cả các shape trong phạm vi đã chỉ định. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Di chuyển shape đã chỉ định đến vị trí mới trong shape collection. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Di chuyển các shape đã chỉ định trong shape collection, đặt chúng bắt đầu tại chỉ số cho trước. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Tạo một auto shape mới với định dạng mặc định và thêm nó vào cuối shape collection. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Tạo một auto shape mới và thêm nó vào cuối shape collection, tùy chọn khởi tạo nó với định dạng mẫu mặc định. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Tạo một rectangle auto shape mới để chứa nội dung toán học và thêm nó vào cuối shape collection. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Tạo một auto shape mới và chèn nó vào shape collection tại chỉ số đã chỉ định, áp dụng định dạng mẫu mặc định. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Tạo một auto shape mới và chèn nó vào shape collection tại chỉ số đã chỉ định, tùy chọn khởi tạo nó với kiểu mẫu mặc định. |
| [addGroupShape()](#addGroupShape--) | Tạo một nhóm shape rỗng mới và thêm nó vào cuối shape collection. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Tạo một nhóm shape mới, chuyển đổi hình ảnh SVG đã chỉ định thành các shape riêng lẻ, và thêm nhóm kết quả vào cuối shape collection. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Tạo một nhóm shape rỗng mới và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Tạo một connector shape mới với kiểu mẫu mặc định và thêm nó vào cuối shape collection. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Tạo một connector shape mới và thêm nó vào cuối shape collection, tùy chọn áp dụng kiểu mẫu mặc định. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Tạo một connector shape mới và chèn nó vào shape collection tại chỉ số đã chỉ định, áp dụng kiểu mẫu mặc định. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Tạo một connector shape mới và chèn nó vào shape collection tại chỉ số đã chỉ định, tùy chọn áp dụng kiểu mẫu mặc định. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Tạo một picture frame mới chứa hình ảnh đã chỉ định và thêm nó vào cuối shape collection. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Tạo một picture frame mới chứa hình ảnh đã chỉ định và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Tạo một table mới và thêm nó vào cuối shape collection. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Tạo một table mới và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa shape tại chỉ số đã chỉ định khỏi shape collection. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Xóa lần xuất hiện đầu tiên của shape đã chỉ định khỏi shape collection. |
| [clear()](#clear--) | Xóa tất cả các shape khỏi shape collection. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Tạo một bản sao của shape đã chỉ định và thêm nó vào cuối shape collection. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Tạo một bản sao của shape đã chỉ định và thêm nó vào cuối shape collection. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Tạo một bản sao của shape đã chỉ định và thêm nó vào cuối shape collection. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Tạo một bản sao của shape đã chỉ định và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Tạo một bản sao của shape đã chỉ định và chèn nó vào shape collection tại chỉ số đã chỉ định. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Tạo một bản sao của shape đã chỉ định và chèn nó vào shape collection tại chỉ số đã chỉ định. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Lấy phần tử tại chỉ số đã chỉ định. Chỉ đọc [IShape](../../com.aspose.slides/ishape).

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

Lấy đối tượng nhóm shape cha cho shape collection. Chỉ đọc [IGroupShape](../../com.aspose.slides/igroupshape).

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Tạo một chart mới, khởi tạo nó với dữ liệu mẫu cho series và các cài đặt, và thêm nó vào cuối shape collection.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại chart để thêm. |
| x | float | Tọa độ x của chart mới, tính bằng point. |
| y | float | Tọa độ y của chart mới, tính bằng point. |
| width | float | Độ rộng của chart, tính bằng point. |
| height | float | Độ cao của chart, tính bằng point. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) mới tạo.

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Tạo một chart mới, khởi tạo nó với dữ liệu mẫu cho series và các cài đặt, và thêm nó vào cuối shape collection.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại chart để thêm. |
| x | float | Tọa độ x của chart mới, tính bằng point. |
| y | float | Tọa độ y của chart mới, tính bằng point. |
| width | float | Độ rộng của chart, tính bằng point. |
| height | float | Độ cao của chart, tính bằng point. |
| initWithSample | boolean | Đúng để khởi tạo chart mới với dữ liệu mẫu và cài đặt; sai để tạo chart mà không có series và chỉ có các cài đặt tối thiểu, giúp tạo nhanh hơn. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) mới tạo.

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Tạo một SmartArt diagram và thêm nó vào cuối shape collection.

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
| x | float | Tọa độ x của khung diagram, tính bằng point. |
| y | float | Tọa độ y của khung diagram, tính bằng point. |
| width | float | Độ rộng của khung diagram, tính bằng point. |
| height | float | Độ cao của khung diagram, tính bằng point. |
| layoutType | int | Kiểu bố cục SmartArt. |

**Trả về:**
[ISmartArt](../../com.aspose.slides/ismartart) - [ISmartArt](../../com.aspose.slides/ismartart) mới tạo.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Tạo một chart mới, khởi tạo nó với dữ liệu mẫu cho series và các cài đặt, và chèn nó vào shape collection tại chỉ số đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại chart để tạo. |
| x | float | Tọa độ x của chart mới, tính bằng point. |
| y | float | Tọa độ y của chart mới, tính bằng point. |
| width | float | Độ rộng của chart mới, tính bằng point. |
| height | float | Độ cao của chart mới, tính bằng point. |
| index | int | Chỉ số zero-based tại nơi chèn chart mới vào shape collection. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) mới tạo.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Tạo một chart mới, khởi tạo nó với dữ liệu mẫu cho series và các cài đặt, và chèn nó vào shape collection tại chỉ số đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại chart để tạo. |
| x | float | Tọa độ x của chart mới, tính bằng point. |
| y | float | Tọa độ y của chart mới, tính bằng point. |
| width | float | Độ rộng của chart mới, tính bằng point. |
| height | float | Độ cao của chart mới, tính bằng point. |
| index | int | Chỉ số zero-based tại nơi chèn chart mới vào shape collection. |
| initWithSample | boolean | Đúng để khởi tạo chart mới với dữ liệu mẫu và cài đặt; sai để tạo chart không có series và chỉ có các cài đặt tối thiểu. |
| initWithSample | boolean | True để khởi tạo biểu đồ mới với dữ liệu và cài đặt mẫu; false để tạo biểu đồ không có chuỗi và chỉ với các cài đặt tối thiểu, giúp việc tạo nhanh hơn. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) mới được tạo.

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Tạo một khung đối tượng OLE mới và thêm nó vào cuối bộ sưu tập hình dạng.

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

Tạo một khung đối tượng OLE mới và thêm nó vào cuối bộ sưu tập hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | float | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | float | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | float | Chiều cao của khung OLE mới, tính bằng điểm. |
| className | java.lang.String | Tên lớp của đối tượng OLE. |
| path | java.lang.String | Đường dẫn tới tệp được liên kết.  

Đường dẫn này được lưu nguyên trong bản trình bày. Nếu chỉ định đường dẫn tương đối, tệp sẽ không khả dụng khi mở bản trình bày từ một thư mục khác. |

**Trả về:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) mới được tạo.

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập hình dạng tại vị trí chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi sẽ chèn khung đối tượng OLE. |
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

Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập hình dạng tại vị trí chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi sẽ chèn khung đối tượng OLE. |
| x | float | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | float | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | float | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | float | Chiều cao của khung OLE mới, tính bằng điểm. |
| className | java.lang.String | Tên lớp của đối tượng OLE. |
| path | java.lang.String | Đường dẫn tới tệp được liên kết.  

Đường dẫn này được lưu nguyên trong bản trình bày. Nếu chỉ định đường dẫn tương đối, tệp sẽ không khả dụng khi mở bản trình bày từ một thư mục khác. |

**Trả về:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) mới được tạo.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Tạo một khung Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng.

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
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) được tham chiếu bởi khung Zoom; phải thuộc về bản trình bày này. |

**Trả về:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) mới được tạo.

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Tạo một khung Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
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
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) được tham chiếu bởi khung Zoom; phải thuộc về bản trình bày này. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Hình ảnh cho slide được tham chiếu [IPPImage](../../com.aspose.slides/ippimage). |

**Trả về:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) mới được tạo.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Tạo một khung Zoom mới và chèn nó vào bộ sưu tập hình dạng tại vị trí chỉ định.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
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
| index | int | Chỉ mục bắt đầu từ 0 nơi sẽ chèn khung Zoom. |
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

Tạo một khung Zoom mới với hình ảnh được định sẵn và chèn nó vào bộ sưu tập hình dạng tại vị trí chỉ định.

--------------------

> ```
> Ví dụ này minh họa việc tạo và chèn một đối tượng Zoom vào vị trí chỉ định trong một bộ sưu tập
>  (giả sử rằng có ít nhất hai slide trong bản trình bày "Presentation.pptx"):
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
| index | int | Chỉ mục bắt đầu từ 0 nơi sẽ chèn khung Zoom. |
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

Tạo một khung Section Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng.

--------------------

> ```
> Ví dụ này minh họa việc thêm một đối tượng Section Zoom vào cuối một bộ sưu tập
>  (giả sử rằng có ít nhất hai phần trong bản trình bày "Presentation.pptx"):
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
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc bản trình bày này và chứa ít nhất một slide. |

**Trả về:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới được tạo.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Tạo một khung Section Zoom mới với hình ảnh được định sẵn và thêm nó vào cuối bộ sưu tập hình dạng.

--------------------

> ```
> Ví dụ này minh họa việc thêm một đối tượng Section Zoom vào cuối một bộ sưu tập
>  (giả sử rằng có ít nhất hai phần trong bản trình bày "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
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
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc bản trình bày này và chứa ít nhất một slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) để hiển thị trong khung Section Zoom. |

**Trả về:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới được tạo.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Tạo một khung Section Zoom mới và chèn nó vào bộ sưu tập hình dạng tại vị trí chỉ định.

--------------------

> ```
> Ví dụ này minh họa việc tạo và chèn một đối tượng Section Zoom vào chỉ mục xác định trong một bộ sưu tập
>  (giả sử rằng có ít nhất hai phần trong bản trình bày "Presentation.pptx"):
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
| index | int | Chỉ mục bắt đầu từ 0 nơi sẽ chèn khung Section Zoom. |
| x | float | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Section Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Section Zoom mới, tính bằng điểm. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc bản trình bày này và chứa ít nhất một slide. |

**Trả về:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới được tạo.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Tạo một khung Section Zoom mới với hình ảnh được định sẵn và chèn nó vào bộ sưu tập hình dạng tại vị trí chỉ định.

--------------------

> ```
> Ví dụ này minh họa việc tạo và chèn một đối tượng Section Zoom vào vị trí chỉ định trong một bộ sưu tập
>  (giả sử rằng có ít nhất hai phần trong bản trình bày "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 nơi sẽ chèn khung Section Zoom. |
| x | float | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Section Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Section Zoom mới, tính bằng điểm. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc bản trình bày này và chứa ít nhất một slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Hình ảnh để hiển thị trong khung Section Zoom. |

**Trả về:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới được tạo.

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Tạo một khung Summary Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng.

--------------------

> ```
> Ví dụ này minh họa việc thêm một đối tượng Summary Zoom vào cuối một bộ sưu tập
>  (giả sử rằng có ít nhất hai phần trong bản trình bày "Presentation.pptx"):
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
Phương thức này tạo một khung Summary Zoom tổng hợp các liên kết tóm tắt cho tất cả các phần trong bản trình chiếu. |

**Giá trị trả về:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) mới tạo.
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Tạo một khung Summary Zoom mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định.

--------------------

> ```
> Ví dụ này minh họa việc tạo và chèn một đối tượng Summary Zoom vào vị trí chỉ định trong một bộ sưu tập
>  (giả sử rằng có ít nhất hai phần trong bản trình bày "Presentation.pptx"):
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
| index | int | Chỉ mục bắt đầu từ 0, nơi chèn khung Summary Zoom. |
| x | float | Tọa độ x của khung Summary Zoom mới, tính bằng point. |
| y | float | Tọa độ y của khung Summary Zoom mới, tính bằng point. |
| width | float | Chiều rộng của khung Summary Zoom mới, tính bằng point. |
| height | float | Chiều cao của khung Summary Zoom mới, tính bằng point. |

--------------------

Phương thức này tạo một khung Summary Zoom tổng hợp các liên kết tóm tắt cho tất cả các phần trong bản trình chiếu. |

**Giá trị trả về:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) mới tạo.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Tạo một khung video mới và thêm nó vào cuối bộ sưu tập hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung video mới, tính bằng point. |
| y | float | Tọa độ y của khung video mới, tính bằng point. |
| width | float | Chiều rộng của khung video mới, tính bằng point. |
| height | float | Chiều cao của khung video mới, tính bằng point. |
| fname | java.lang.String | Đường dẫn hoặc tên của tệp video cần nhúng. |

**Giá trị trả về:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) mới tạo.
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Tạo một khung video mới và thêm nó vào cuối bộ sưu tập hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung video mới, tính bằng point. |
| y | float | Tọa độ y của khung video mới, tính bằng point. |
| width | float | Chiều rộng của khung video mới, tính bằng point. |
| height | float | Chiều cao của khung video mới, tính bằng point. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Đối tượng [IVideo](../../com.aspose.slides/ivideo) để nhúng vào khung video. |

**Giá trị trả về:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) mới tạo.
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Tạo một khung video mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, nơi chèn khung video. |
| x | float | Tọa độ x của khung video mới, tính bằng point. |
| y | float | Tọa độ y của khung video mới, tính bằng point. |
| width | float | Chiều rộng của khung video mới, tính bằng point. |
| height | float | Chiều cao của khung video mới, tính bằng point. |
| fname | java.lang.String | Đường dẫn hoặc tên của tệp video cần nhúng. |

**Giá trị trả về:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) mới tạo.
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Tạo một khung âm thanh mới được liên kết với một bản ghi CD và thêm nó vào cuối bộ sưu tập hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng point. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng point. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng point. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng point. |

**Giá trị trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Tạo một khung âm thanh mới được liên kết với một bản ghi CD và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, nơi chèn khung âm thanh. |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng point. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng point. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng point. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng point. |

**Giá trị trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Tạo một khung âm thanh mới được liên kết với một tệp âm thanh bên ngoài và thêm nó vào cuối bộ sưu tập hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng point. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng point. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng point. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng point. |
| fname | java.lang.String | Đường dẫn hoặc tên của tệp âm thanh bên ngoài cần liên kết. |

**Giá trị trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Tạo một khung âm thanh mới được liên kết với một tệp âm thanh bên ngoài và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, nơi chèn khung âm thanh. |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng point. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng point. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng point. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng point. |
| fname | java.lang.String | Đường dẫn hoặc tên của tệp âm thanh bên ngoài cần liên kết. |

**Giá trị trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Tạo một khung âm thanh mới với tệp WAV được nhúng và thêm nó vào cuối bộ sưu tập hình dạng. Âm thanh được nhúng sẽ được thêm vào bộ sưu tập Presentation.Audios.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng point. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng point. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng point. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng point. |
| audio_stream | java.io.InputStream | Luồng nhập chứa dữ liệu âm thanh WAV để nhúng. |

**Giá trị trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Tạo một khung âm thanh mới và thêm nó vào cuối bộ sưu tập hình dạng bằng cách sử dụng một đối tượng âm thanh hiện có từ danh sách Presentation.Audios.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng point. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng point. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng point. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng point. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Một [IAudio](../../com.aspose.slides/iaudio) instance từ bộ sưu tập Presentation.Audios. |

**Giá trị trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Tạo một khung âm thanh mới với tệp WAV được nhúng và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định. Âm thanh được nhúng sẽ được thêm vào bộ sưu tập Presentation.Audios.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, nơi chèn khung âm thanh. |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng point. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng point. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng point. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng point. |
| audio_stream | java.io.InputStream | Luồng nhập chứa dữ liệu âm thanh WAV để nhúng. |

**Giá trị trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Tạo một khung âm thanh mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định bằng cách sử dụng một đối tượng âm thanh hiện có từ danh sách Presentation.Audios.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, nơi chèn khung âm thanh. |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng point. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng point. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng point. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng point. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Một [IAudio](../../com.aspose.slides/iaudio) instance từ bộ sưu tập Presentation.Audios để nhúng. |

**Giá trị trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của hình dạng được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Hình dạng cần tìm trong bộ sưu tập. |

**Giá trị trả về:**
int - Chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của hình dạng trong bộ sưu tập hình dạng nếu tìm thấy; nếu không, \\u20131.
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Tạo và trả về một mảng chứa tất cả các hình dạng.

**Giá trị trả về:**
com.aspose.slides.IShape[] - Một mảng các đối tượng [IShape](../../com.aspose.slides/ishape).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Tạo và trả về một mảng chứa tất cả các hình dạng trong phạm vi được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| startIndex | int | Chỉ mục của hình dạng đầu tiên cần trả về. |
| count | int | Số lượng hình dạng cần trả về. |

**Giá trị trả về:**
com.aspose.slides.IShape[] - Một mảng các đối tượng [IShape](../../com.aspose.slides/ishape).
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Di chuyển hình dạng được chỉ định đến vị trí mới trong bộ sưu tập hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục đích bắt đầu từ 0, nơi hình dạng sẽ được đặt. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) cần di chuyển trong bộ sưu tập. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Di chuyển các hình dạng được chỉ định trong bộ sưu tập, bắt đầu đặt chúng tại chỉ mục đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục đích bắt đầu từ 0, nơi hình dạng đầu tiên sẽ được đặt; các hình dạng tiếp theo sẽ được sắp xếp theo thứ tự đã cung cấp. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Một hoặc nhiều [IShape](../../com.aspose.slides/ishape) instance để di chuyển trong bộ sưu tập. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Tạo một auto shape mới với định dạng mặc định và thêm nó vào cuối bộ sưu tập hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của auto shape cần thêm. |

| x | float | Tọa độ x của khung hình, tính bằng điểm. |
| y | float | Tọa độ y của khung hình, tính bằng điểm. |
| width | float | Chiều rộng của khung hình, tính bằng điểm. |
| height | float | Chiều cao của khung hình, tính bằng điểm. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới tạo.
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một hình tự động mới và thêm nó vào cuối bộ sưu tập hình, tùy chọn khởi tạo với định dạng mẫu mặc định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của hình tự động cần thêm. |
| x | float | Tọa độ x của khung hình, tính bằng điểm. |
| y | float | Tọa độ y của khung hình, tính bằng điểm. |
| width | float | Chiều rộng của khung hình, tính bằng điểm. |
| height | float | Chiều cao của khung hình, tính bằng điểm. |
| createFromTemplate | boolean | True để áp dụng kiểu mẫu mặc định (kiểu đơn giản, văn bản căn giữa và tên không rỗng) cho hình mới; false để tạo hình với mọi thuộc tính được đặt giá trị mặc định. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới tạo.
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Tạo một hình tự động hình chữ nhật mới để chứa nội dung toán học và thêm nó vào cuối bộ sưu tập hình.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Tọa độ x của khung hình, tính bằng điểm. |
| y | float | Tọa độ y của khung hình, tính bằng điểm. |
| width | float | Chiều rộng của khung hình, tính bằng điểm. |
| height | float | Chiều cao của khung hình, tính bằng điểm. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới tạo.
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Tạo một hình tự động mới và chèn nó vào bộ sưu tập hình ở vị trí chỉ định, áp dụng định dạng mẫu mặc định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại nơi chèn hình tự động mới. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của hình tự động cần chèn. |
| x | float | Tọa độ x của khung hình, tính bằng điểm. |
| y | float | Tọa độ y của khung hình, tính bằng điểm. |
| width | float | Chiều rộng của khung hình, tính bằng điểm. |
| height | float | Chiều cao của khung hình, tính bằng điểm. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới tạo.
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một hình tự động mới và chèn nó vào bộ sưu tập hình ở vị trí chỉ định, tùy chọn khởi tạo với kiểu mẫu mặc định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại nơi chèn hình tự động. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của hình tự động cần chèn. |
| x | float | Tọa độ x của khung hình, tính bằng điểm. |
| y | float | Tọa độ y của khung hình, tính bằng điểm. |
| width | float | Chiều rộng của khung hình, tính bằng điểm. |
| height | float | Chiều cao của khung hình, tính bằng điểm. |
| createFromTemplate | boolean | True để áp dụng kiểu mẫu mặc định (bao gồm tên không rỗng, kiểu đơn giản và văn bản căn giữa); false để tạo hình với mọi thuộc tính được đặt giá trị mặc định. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới tạo.
### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Tạo một nhóm hình trống mới và thêm nó vào cuối bộ sưu tập hình. Khung của nhóm sẽ tự động điều chỉnh để vừa với bất kỳ hình nào được thêm vào.

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) mới tạo.
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Tạo một nhóm hình mới, chuyển đổi hình ảnh SVG đã chỉ định thành các hình riêng lẻ, và thêm nhóm tạo được vào cuối bộ sưu tập hình.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) chứa nội dung vector để chuyển đổi thành các hình. |
| x | float | Tọa độ x của khung nhóm, tính bằng điểm. |
| y | float | Tọa độ y của khung nhóm, tính bằng điểm. |
| width | float | Chiều rộng của khung nhóm, tính bằng điểm. |
| height | float | Chiều cao của khung nhóm, tính bằng điểm. |

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) mới tạo.
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Tạo một nhóm hình trống mới và chèn nó vào bộ sưu tập hình ở vị trí chỉ định. Khung của nhóm sẽ tự động điều chỉnh để vừa với bất kỳ hình nào được thêm vào.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại nơi chèn nhóm hình. |

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) mới tạo.
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Tạo một hình kết nối mới với kiểu mẫu mặc định và thêm nó vào cuối bộ sưu tập hình.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của hình kết nối cần thêm. |
| x | float | Tọa độ x của khung kết nối, tính bằng điểm. |
| y | float | Tọa độ y của khung kết nối, tính bằng điểm. |
| width | float | Chiều rộng của khung kết nối, tính bằng điểm. |
| height | float | Chiều cao của khung kết nối, tính bằng điểm. |

**Trả về:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) mới tạo.
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một hình kết nối mới và thêm nó vào cuối bộ sưu tập hình, tùy chọn áp dụng kiểu mẫu mặc định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của hình kết nối cần tạo. |
| x | float | Tọa độ x của khung kết nối, tính bằng điểm. |
| y | float | Tọa độ y của khung kết nối, tính bằng điểm. |
| width | float | Chiều rộng của khung kết nối, tính bằng điểm. |
| height | float | Chiều cao của khung kết nối, tính bằng điểm. |
| createFromTemplate | boolean | True để áp dụng kiểu mẫu mặc định (tên không rỗng, kiểu đơn giản); false để tạo kết nối với các thuộc tính mặc định. |

**Trả về:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) mới tạo.
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Tạo một hình kết nối mới và chèn nó vào bộ sưu tập hình ở vị trí chỉ định, áp dụng kiểu mẫu mặc định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại nơi chèn hình kết nối. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của hình kết nối cần chèn. |
| x | float | Tọa độ x của khung kết nối, tính bằng điểm. |
| y | float | Tọa độ y của khung kết nối, tính bằng điểm. |
| width | float | Chiều rộng của khung kết nối, tính bằng điểm. |
| height | float | Chiều cao của khung kết nối, tính bằng điểm. |

**Trả về:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) mới tạo.
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một hình kết nối mới và chèn nó vào bộ sưu tập hình ở vị trí chỉ định, tùy chọn áp dụng kiểu mẫu mặc định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại nơi chèn hình kết nối. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của hình kết nối cần chèn. |
| x | float | Tọa độ x của khung kết nối, tính bằng điểm. |
| y | float | Tọa độ y của khung kết nối, tính bằng điểm. |
| width | float | Chiều rộng của khung kết nối, tính bằng điểm. |
| height | float | Chiều cao của khung kết nối, tính bằng điểm. |
| createFromTemplate | boolean | True để áp dụng kiểu mẫu mặc định (tên không rỗng, kiểu đơn giản); false để tạo kết nối với các thuộc tính mặc định. |

**Trả về:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) mới tạo.
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Tạo một khung hình ảnh mới chứa hình ảnh đã chỉ định và thêm nó vào cuối bộ sưu tập hình.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Xác định loại hình chứa trong [ShapeType](../../com.aspose.slides/shapetype), ngoại trừ mọi loại đường:  

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | Tọa độ x của khung hình ảnh, tính bằng điểm. |
| y | float | Tọa độ y của khung hình ảnh, tính bằng điểm. |
| width | float | Chiều rộng của khung hình ảnh, tính bằng điểm. |
| height | float | Chiều cao của khung hình ảnh, tính bằng điểm. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) để hiển thị trong khung hình ảnh. |

**Trả về:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) mới tạo.
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Tạo một khung hình ảnh mới chứa hình ảnh đã chỉ định và chèn nó vào bộ sưu tập hình ở vị trí chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại nơi chèn khung hình ảnh. |
| shapeType | int | Xác định loại hình chứa trong [ShapeType](../../com.aspose.slides/shapetype), ngoại trừ mọi loại đường:  

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | Tọa độ x của khung hình ảnh, tính bằng điểm. |
| y | float | Tọa độ y của khung hình ảnh, tính bằng điểm. |
| width | float | Chiều rộng của khung hình ảnh, tính bằng điểm. |
| height | float | Chiều cao của khung hình ảnh, tính bằng điểm. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) để hiển thị trong khung hình ảnh. |

**Trả về:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) mới tạo.
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Tạo một bảng mới và thêm nó vào cuối bộ sưu tập hình.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Tọa độ x của bảng, tính bằng điểm. |
| y | float | Tọa độ y của bảng, tính bằng điểm. |
| columnWidths | double[] | Mảng các số double biểu thị chiều rộng của các cột trong bảng, tính bằng điểm. |
| rowHeights | double[] | Mảng các số double biểu thị chiều cao của các hàng trong bảng, tính bằng điểm. |

**Trả về:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) mới tạo.
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Tạo một bảng mới và chèn nó vào bộ sưu tập hình tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí chèn bảng. |
| x | float | Tọa độ x của bảng, tính bằng điểm. |
| y | float | Tọa độ y của bảng, tính bằng điểm. |
| columnWidths | double[] | Mảng double đại diện cho độ rộng của các cột của bảng, tính bằng điểm. |
| rowHeights | double[] | Mảng double đại diện cho độ cao của các hàng của bảng, tính bằng điểm. |

**Giá trị trả về:**
[ITable](../../com.aspose.slides/itable) - The newly created [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa hình tại chỉ mục đã chỉ định khỏi bộ sưu tập hình.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của hình cần xóa. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Xóa lần xuất hiện đầu tiên của hình đã chỉ định khỏi bộ sưu tập hình.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Đối tượng [IShape](../../com.aspose.slides/ishape) cần xóa. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các hình khỏi bộ sưu tập hình.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Tạo một bản sao của hình đã chỉ định và thêm nó vào cuối bộ sưu tập hình.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Hình cần sao chép. |
| x | float | Tọa độ x của khung hình sao chép, tính bằng điểm. |
| y | float | Tọa độ y của khung hình sao chép, tính bằng điểm. |
| width | float | Chiều rộng của khung hình sao chép, tính bằng điểm. |
| height | float | Chiều cao của khung hình sao chép, tính bằng điểm. |

**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Tạo một bản sao của hình đã chỉ định và thêm nó vào cuối bộ sưu tập hình. Hình mới giữ nguyên chiều rộng và chiều cao của sourceShape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Đối tượng [IShape](../../com.aspose.slides/ishape) cần sao chép. |
| x | float | Tọa độ x của khung hình sao chép, tính bằng điểm. |
| y | float | Tọa độ y của khung hình sao chép, tính bằng điểm. |

**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Tạo một bản sao của hình đã chỉ định và thêm nó vào cuối bộ sưu tập hình. Hình sao chép giữ nguyên vị trí và kích thước của hình gốc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Đối tượng [IShape](../../com.aspose.slides/ishape) cần sao chép. |

**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Tạo một bản sao của hình đã chỉ định và chèn nó vào bộ sưu tập hình tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí chèn hình sao chép. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Đối tượng [IShape](../../com.aspose.slides/ishape) cần sao chép. |
| x | float | Tọa độ x của khung hình sao chép, tính bằng điểm. |
| y | float | Tọa độ y của khung hình sao chép, tính bằng điểm. |
| width | float | Chiều rộng của khung hình sao chép, tính bằng điểm. |
| height | float | Chiều cao của khung hình sao chép, tính bằng điểm. |

**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Tạo một bản sao của hình đã chỉ định và chèn nó vào bộ sưu tập hình tại chỉ mục đã chỉ định. Hình mới giữ nguyên chiều rộng và chiều cao của sourceShape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí chèn hình sao chép. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Đối tượng [IShape](../../com.aspose.slides/ishape) cần sao chép. |
| x | float | Tọa độ x của khung hình sao chép, tính bằng điểm. |
| y | float | Tọa độ y của khung hình sao chép, tính bằng điểm. |

**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Tạo một bản sao của hình đã chỉ định và chèn nó vào bộ sưu tập hình tại chỉ mục đã chỉ định. Hình sao chép giữ nguyên vị trí và kích thước của hình gốc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí chèn hình sao chép. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Đối tượng [IShape](../../com.aspose.slides/ishape) cần sao chép. |

**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).