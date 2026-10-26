---
title: ShapeCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một tập hợp các hình dạng.
type: docs
url: /vi/com.aspose.slides/shapecollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Biểu thị một bộ sưu tập các hình dạng.
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Lấy số phần tử thực tế chứa trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và thêm nó vào cuối bộ sưu tập hình dạng. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và thêm nó vào cuối bộ sưu tập hình dạng. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Tạo một sơ đồ SmartArt và thêm nó vào cuối bộ sưu tập hình dạng. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Tạo một khung Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Tạo một khung Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Tạo một khung Zoom mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Tạo một khung Zoom mới với hình ảnh được xác định trước và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Tạo một khung Zoom Section mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Tạo một khung Zoom Section mới với hình ảnh được xác định trước và thêm nó vào cuối bộ sưu tập hình dạng. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Tạo một khung Zoom Section mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Tạo một khung Zoom Section mới với hình ảnh được xác định trước và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Tạo một khung Zoom Summary mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Tạo một khung Zoom Summary mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Tạo một khung đối tượng OLE mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Tạo một khung đối tượng OLE mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Tạo một khung video mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Tạo một khung video mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Tạo một khung video mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Tạo một khung âm thanh mới liên kết tới một track CD và thêm nó vào cuối bộ sưu tập hình dạng. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Tạo một khung âm thanh mới liên kết tới một track CD và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Tạo một khung âm thanh mới liên kết tới một tệp âm thanh bên ngoài và thêm nó vào cuối bộ sưu tập hình dạng. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Tạo một khung âm thanh mới liên kết tới một tệp âm thanh bên ngoài và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Tạo một khung âm thanh mới với tệp WAV nhúng và thêm nó vào cuối bộ sưu tập hình dạng. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Tạo một khung âm thanh mới với tệp WAV nhúng và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Tạo một khung âm thanh mới và thêm nó vào cuối bộ sưu tập hình dạng bằng cách sử dụng một đối tượng âm thanh hiện có từ danh sách Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Tạo một khung âm thanh mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định bằng cách sử dụng một đối tượng âm thanh hiện có từ danh sách Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của hình dạng đã chỉ định trong bộ sưu tập. |
| [toArray()](#toArray--) | Tạo và trả về một mảng chứa tất cả các hình dạng. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tạo và trả về một mảng chứa tất cả các hình dạng trong phạm vi đã chỉ định. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Di chuyển hình dạng đã chỉ định đến vị trí mới trong bộ sưu tập hình dạng. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Di chuyển các hình dạng đã chỉ định trong bộ sưu tập hình dạng, đặt chúng bắt đầu tại chỉ mục đã cho. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Tạo một hình tự động mới với định dạng mặc định và thêm nó vào cuối bộ sưu tập hình dạng. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Tạo một hình tự động mới và thêm nó vào cuối bộ sưu tập hình dạng, tùy chọn khởi tạo nó với định dạng mẫu mặc định. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Tạo một hình tự động hình chữ nhật mới để chứa nội dung toán học và thêm nó vào cuối bộ sưu tập hình dạng. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Tạo một hình tự động mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định, áp dụng định dạng mẫu mặc định. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Tạo một hình tự động mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định, tùy chọn khởi tạo nó với kiểu mẫu mặc định. |
| [addGroupShape()](#addGroupShape--) | Tạo một nhóm hình dạng trống mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Tạo một nhóm hình dạng mới, chuyển đổi ảnh SVG đã chỉ định thành các hình dạng riêng lẻ, và thêm nhóm kết quả vào cuối bộ sưu tập hình dạng. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Tạo một nhóm hình dạng trống mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Tạo một hình kết nối mới với kiểu mẫu mặc định và thêm nó vào cuối bộ sưu tập hình dạng. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Tạo một hình kết nối mới và thêm nó vào cuối bộ sưu tập hình dạng, tùy chọn áp dụng kiểu mẫu mặc định. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Tạo một hình kết nối mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định, áp dụng kiểu mẫu mặc định. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Tạo một hình kết nối mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định, tùy chọn áp dụng kiểu mẫu mặc định. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Tạo một khung ảnh mới chứa hình ảnh đã chỉ định và thêm nó vào cuối bộ sưu tập hình dạng. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Tạo một khung ảnh mới chứa hình ảnh đã chỉ định và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Tạo một bảng mới và thêm nó vào cuối bộ sưu tập hình dạng. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Tạo một bảng mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa hình dạng tại chỉ mục đã chỉ định khỏi bộ sưu tập hình dạng. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Xóa lần xuất hiện đầu tiên của hình dạng đã chỉ định khỏi bộ sưu tập hình dạng. |
| [clear()](#clear--) | Xóa tất cả các hình dạng khỏi bộ sưu tập hình dạng. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ bộ sưu tập. |
| [getParentGroup()](#getParentGroup--) | Lấy đối tượng nhóm hình dạng cha cho bộ sưu tập các hình dạng. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Tạo một bản sao của hình dạng đã chỉ định và thêm nó vào cuối bộ sưu tập hình dạng. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Tạo một bản sao của hình dạng đã chỉ định và thêm nó vào cuối bộ sưu tập hình dạng. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Tạo một bản sao của hình dạng đã chỉ định và thêm nó vào cuối bộ sưu tập hình dạng. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Tạo một bản sao của hình dạng đã chỉ định và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Tạo một bản sao của hình dạng đã chỉ định và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Tạo một bản sao của hình dạng đã chỉ định và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng đã chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào bộ sưu tập có đồng bộ (an toàn với đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ. |

### size() {#size--}
```
public final int size()
```

Lấy số phần tử thực tế chứa trong bộ sưu tập. Chỉ đọc  int .

**Trả về:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Lấy phần tử tại chỉ mục đã chỉ định. Chỉ đọc [IShape](../../com.aspose.slides/ishape).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IShape](../../com.aspose.slides/ishape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và thêm nó vào cuối bộ sưu tập hình dạng.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Khởi tạo lớp Presentation đại diện cho tệp PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Truy cập slide đầu tiên
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Thêm biểu đồ với dữ liệu mặc định
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Đặt tiêu đề biểu đồ
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Đặt series đầu tiên hiển thị giá trị
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Đặt chỉ mục cho bảng dữ liệu biểu đồ
>      int defaultWorksheetIndex = 0;
>      // Lấy worksheet dữ liệu biểu đồ
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Xóa series và danh mục được tạo mặc định
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Thêm series mới
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Thêm danh mục mới
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Lấy series biểu đồ đầu tiên
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Điền dữ liệu vào series
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Đặt màu nền cho series
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Lấy series biểu đồ thứ hai
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Điền dữ liệu vào series
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Đặt màu nền cho series
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Đặt nhãn đầu tiên hiển thị tên danh mục
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Đặt series hiển thị giá trị cho nhãn thứ ba
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Lưu tệp PPTX vào đĩa
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Kiểu biểu đồ để thêm. |
| x | float | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | float | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | float | Chiều rộng của biểu đồ, tính bằng điểm. |
| height | float | Chiều cao của biểu đồ, tính bằng điểm. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - Đối tượng [IChart](../../com.aspose.slides/ichart) mới tạo.

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và thêm nó vào cuối bộ sưu tập hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Kiểu biểu đồ để thêm. |
| x | float | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | float | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | float | Chiều rộng của biểu đồ, tính bằng điểm. |
| height | float | Chiều cao của biểu đồ, tính bằng điểm. |
| initWithSample | boolean | True để khởi tạo biểu đồ mới với dữ liệu và cài đặt mẫu; false để tạo biểu đồ không có series và chỉ có cài đặt tối thiểu, giúp việc tạo nhanh hơn. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - Đối tượng [IChart](../../com.aspose.slides/ichart) mới tạo.

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Tạo một sơ đồ SmartArt và thêm nó vào cuối bộ sưu tập hình dạng.

--------------------

> ```
> The following example shows how to add smart shape in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
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
| layoutType | int | Kiểu bố cục SmartArt. |

**Trả về:**
[ISmartArt](../../com.aspose.slides/ismartart) - Đối tượng [ISmartArt](../../com.aspose.slides/ismartart) mới tạo.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Kiểu biểu đồ để tạo. |
| x | float | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | float | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | float | Chiều rộng của biểu đồ mới, tính bằng điểm. |
| height | float | Chiều cao của biểu đồ mới, tính bằng điểm. |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí chèn biểu đồ mới trong bộ sưu tập hình dạng. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - Đối tượng [IChart](../../com.aspose.slides/ichart) mới tạo.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Tạo một biểu đồ mới, khởi tạo nó với dữ liệu và cài đặt mẫu, và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Kiểu biểu đồ để tạo. |
| x | float | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | float | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | float | Chiều rộng của biểu đồ mới, tính bằng điểm. |
| height | float | Chiều cao của biểu đồ mới, tính bằng điểm. |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí chèn biểu đồ mới trong bộ sưu tập hình dạng. |
| initWithSample | boolean | True để khởi tạo biểu đồ mới với dữ liệu và cài đặt mẫu; false để tạo biểu đồ không có series và chỉ có cài đặt tối thiểu, giúp việc tạo nhanh hơn. |
| x | float | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | float | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | float | Chiều rộng của biểu đồ mới, tính bằng điểm. |
| height | float | Chiều cao của biểu đồ mới, tính bằng điểm. |
| index | int | Chỉ mục bắt đầu từ 0, vị trí sẽ chèn biểu đồ mới vào bộ sưu tập hình dạng. |
| initWithSample | boolean | True để khởi tạo biểu đồ mới với dữ liệu và cài đặt mẫu; false để tạo biểu đồ không có chuỗi dữ liệu và chỉ có các cài đặt tối thiểu, giúp tạo nhanh hơn. |

**Trả về:**  
[IChart](../../com.aspose.slides/ichart) - Đối tượng [IChart](../../com.aspose.slides/ichart) mới được tạo.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Zoom mới, tính bằng điểm. |
| slide | [ISlide](../../com.aspose.slides/islide) | Đối tượng [ISlide](../../com.aspose.slides/islide) được tham chiếu bởi khung Zoom; phải thuộc về bản trình bày này. |

**Trả về:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Đối tượng [IZoomFrame](../../com.aspose.slides/izoomframe) mới được tạo.

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
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
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Zoom mới, tính bằng điểm. |
| slide | [ISlide](../../com.aspose.slides/islide) | Đối tượng [ISlide](../../com.aspose.slides/islide) được tham chiếu bởi khung Zoom; phải thuộc về bản trình bày này. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Hình ảnh cho slide được tham chiếu [IPPImage](../../com.aspose.slides/ippimage). |

**Trả về:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Đối tượng [IZoomFrame](../../com.aspose.slides/izoomframe) mới được tạo.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Tạo một khung Zoom mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.

--------------------

> ```
> Ví dụ này minh họa việc tạo và chèn một đối tượng Zoom vào vị trí chỉ định trong một bộ sưu tập
>  (giả sử rằng có ít nhất hai slide trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, vị trí sẽ chèn khung Zoom. |
| x | float | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Zoom mới, tính bằng điểm. |
| slide | [ISlide](../../com.aspose.slides/islide) | Đối tượng [ISlide](../../com.aspose.slides/islide) được tham chiếu bởi khung Zoom. |

**Trả về:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Đối tượng [IZoomFrame](../../com.aspose.slides/izoomframe) mới được tạo.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Tạo một khung Zoom mới với hình ảnh đã định trước và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, vị trí sẽ chèn khung Zoom. |
| x | float | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Zoom mới, tính bằng điểm. |
| slide | [ISlide](../../com.aspose.slides/islide) | Đối tượng [ISlide](../../com.aspose.slides/islide) được tham chiếu bởi khung Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Hình ảnh cho slide được tham chiếu [IPPImage](../../com.aspose.slides/ippimage). |

**Trả về:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Đối tượng [IZoomFrame](../../com.aspose.slides/izoomframe) mới được tạo.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Tạo một khung Section Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng.

--------------------

> ```
> Ví dụ này minh họa việc thêm một đối tượng Section Zoom vào cuối một bộ sưu tập
>  (giả sử rằng có ít nhất hai phần trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Section Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Section Zoom mới, tính bằng điểm. |
| section | [ISection](../../com.aspose.slides/isection) | Đối tượng [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc về bản trình bày này và chứa ít nhất một slide. |

**Trả về:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Đối tượng [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới được tạo.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Tạo một khung Section Zoom mới với hình ảnh đã định trước và thêm nó vào cuối bộ sưu tập hình dạng.

--------------------

> ```
> Ví dụ này minh họa việc thêm một đối tượng Section Zoom vào cuối một bộ sưu tập
>  (giả sử rằng có ít nhất hai phần trong bản trình chiếu "Presentation.pptx"):
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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Section Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Section Zoom mới, tính bằng điểm. |
| section | [ISection](../../com.aspose.slides/isection) | Đối tượng [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc về bản trình bày này và chứa ít nhất một slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) để hiển thị trong khung Section Zoom. |

**Trả về:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Đối tượng [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới được tạo.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Tạo một khung Section Zoom mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.

--------------------

> ```
> Ví dụ này minh họa việc tạo và chèn một đối tượng Section Zoom vào vị trí chỉ định trong một bộ sưu tập
>  (giả sử rằng có ít nhất hai phần trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, vị trí sẽ chèn khung Section Zoom. |
| x | float | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Section Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Section Zoom mới, tính bằng điểm. |
| section | [ISection](../../com.aspose.slides/isection) | Đối tượng [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc về bản trình bày này và chứa ít nhất một slide. |

**Trả về:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Đối tượng [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới được tạo.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Tạo một khung Section Zoom mới với hình ảnh đã định trước và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.

--------------------

> ```
> Ví dụ này minh họa việc tạo và chèn một đối tượng Section Zoom vào vị trí chỉ định trong một bộ sưu tập
>  (giả sử rằng có ít nhất hai phần trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, vị trí sẽ chèn khung Section Zoom. |
| x | float | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Section Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Section Zoom mới, tính bằng điểm. |
| section | [ISection](../../com.aspose.slides/isection) | Đối tượng [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc về bản trình bày này và chứa ít nhất một slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Hình ảnh để hiển thị trong khung Section Zoom. |

**Trả về:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Đối tượng [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới được tạo.

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Tạo một khung Summary Zoom mới và thêm nó vào cuối bộ sưu tập hình dạng.

--------------------

> ```
> Ví dụ này minh họa việc thêm một đối tượng Summary Zoom vào cuối một bộ sưu tập
>  (giả sử rằng có ít nhất hai phần trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Tọa độ x của khung Summary Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Summary Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Summary Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Summary Zoom mới, tính bằng điểm. |

--------------------

Phương thức này tạo một Summary Zoom mới và đưa một bộ sưu tập các đối tượng vào đó cho tất cả các phần trong bản trình bày này.  

**Trả về:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Đối tượng [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) mới được tạo.

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Tạo một khung Summary Zoom mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.

--------------------

> ```
> Ví dụ này minh họa việc tạo và chèn một đối tượng Summary Zoom vào vị trí chỉ định trong một bộ sưu tập
>  (giả sử rằng có ít nhất hai phần trong bản trình chiếu "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, vị trí sẽ chèn khung Summary Zoom. |
| x | float | Tọa độ x của khung Summary Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Summary Zoom mới, tính bằng điểm. |
| width | float | Chiều rộng của khung Summary Zoom mới, tính bằng điểm. |
| height | float | Chiều cao của khung Summary Zoom mới, tính bằng điểm. |

--------------------

Phương thức này tạo một khung Summary Zoom tổng hợp các liên kết tóm tắt cho tất cả các phần trong bản trình bày.  

**Trả về:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Đối tượng [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) mới được tạo.

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Tạo một khung OLE object mới và thêm nó vào cuối bộ sưu tập hình dạng.

--------------------

> ```
> Các ví dụ sau đây minh họa cách thêm khung OLE Object vào các slide của bản trình chiếu PowerPoint.
>  
>  // Khởi tạo lớp Presentation đại diện cho tệp PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Truy cập slide đầu tiên
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Tải một tệp cel vào luồng
>      FileInputStream fs = new FileInputStream("book1.xlsx");
>      ByteArrayOutputStream mstream = new ByteArrayOutputStream();
>      byte[] buf = new byte[4096];
> 
>      while (true)
>      {
>          int bytesRead = fs.read(buf, 0, buf.length);
>          if (bytesRead <= 0)
>              break;
>          mstream.write(buf, 0, bytesRead);
>      }
>      // Tạo đối tượng dữ liệu để nhúng
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Thêm một hình khung Ole Object
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // Ghi tệp PPTX ra đĩa
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | float | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | float | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | float | Chiều cao của khung OLE mới, tính bằng điểm. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Thông tin về dữ liệu OLE được nhúng ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Trả về:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Đối tượng [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) mới được tạo.

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Tạo một khung OLE object mới và thêm nó vào cuối bộ sưu tập hình dạng.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | float | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | float | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | float | Chiều cao của khung OLE mới, tính bằng điểm. |
| className | java.lang.String | Tên lớp của đối tượng OLE. |
| path | java.lang.String | Đường dẫn tới tệp được liên kết.

Đường dẫn này được lưu nguyên văn trong bản trình bày. Nếu chỉ định đường dẫn tương đối, tệp sẽ không thể truy cập được khi mở bản trình bày từ một thư mục khác. |

**Trả về:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Đối tượng [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) mới được tạo.

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Tạo một khung OLE object mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.

--------------------

> ```
> Ví dụ này minh họa việc chèn một đối tượng OLE vào vị trí chỉ số thứ hai:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, vị trí sẽ chèn khung OLE object. |
| x | float | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | float | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | float | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | float | Chiều cao của khung OLE mới, tính bằng điểm. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Thông tin dữ liệu OLE được nhúng ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Đối tượng [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) mới được tạo.

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, nơi sẽ chèn khung đối tượng OLE. |
| x | float | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | float | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | float | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | float | Chiều cao của khung OLE mới, tính bằng điểm. |
| className | java.lang.String | Tên lớp của đối tượng OLE. |
| path | java.lang.String | Đường dẫn tới tệp liên kết.<br><br>Đường dẫn này được lưu nguyên trong bản trình chiếu. Nếu chỉ định đường dẫn tương đối, tệp sẽ không thể truy cập được khi mở bản trình chiếu từ thư mục khác. |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Khung đối tượng OLE mới được tạo.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Tạo một khung video mới và thêm nó vào cuối bộ sưu tập hình dạng.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung video mới, tính bằng điểm. |
| y | float | Tọa độ y của khung video mới, tính bằng điểm. |
| width | float | Chiều rộng của khung video mới, tính bằng điểm. |
| height | float | Chiều cao của khung video mới, tính bằng điểm. |
| fname | java.lang.String | Đường dẫn hoặc tên của tệp video để nhúng. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Đối tượng [IVideoFrame](../../com.aspose.slides/ivideoframe) mới được tạo.

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Tạo một khung video mới và thêm nó vào cuối bộ sưu tập hình dạng.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung video mới, tính bằng điểm. |
| y | float | Tọa độ y của khung video mới, tính bằng điểm. |
| width | float | Chiều rộng của khung video mới, tính bằng điểm. |
| height | float | Chiều cao của khung video mới, tính bằng điểm. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Đối tượng [IVideo](../../com.aspose.slides/ivideo) để nhúng vào khung video. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Đối tượng [IVideoFrame](../../com.aspose.slides/ivideoframe) mới được tạo.

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Tạo một khung video mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, nơi sẽ chèn khung video. |
| x | float | Tọa độ x của khung video mới, tính bằng điểm. |
| y | float | Tọa độ y của khung video mới, tính bằng điểm. |
| width | float | Chiều rộng của khung video mới, tính bằng điểm. |
| height | float | Chiều cao của khung video mới, tính bằng điểm. |
| fname | java.lang.String | Đường dẫn hoặc tên của tệp video để nhúng. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Đối tượng [IVideoFrame](../../com.aspose.slides/ivideoframe) mới được tạo.

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Tạo một khung âm thanh mới liên kết với một bản ghi CD và thêm nó vào cuối bộ sưu tập hình dạng.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Đối tượng [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Tạo một khung âm thanh mới liên kết với một bản ghi CD và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, nơi sẽ chèn khung âm thanh. |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Đối tượng [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Tạo một khung âm thanh mới liên kết với một tệp âm thanh bên ngoài và thêm nó vào cuối bộ sưu tập hình dạng.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |
| fname | java.lang.String | Đường dẫn hoặc tên của tệp âm thanh bên ngoài để liên kết. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Đối tượng [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Tạo một khung âm thanh mới liên kết với một tệp âm thanh bên ngoài và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, nơi sẽ chèn khung âm thanh. |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |
| fname | java.lang.String | Đường dẫn hoặc tên của tệp âm thanh bên ngoài để liên kết. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Đối tượng [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Tạo một khung âm thanh mới với tệp WAV được nhúng và thêm nó vào cuối bộ sưu tập hình dạng. Âm thanh được nhúng sẽ được thêm vào bộ sưu tập Presentation.Audios.

--------------------

> ```
> Các ví dụ sau đây cho thấy cách tạo Audio Frame.
>  
>  // Khởi tạo lớp Presentation đại diện cho tệp trình chiếu
>  Presentation pres = new Presentation();
>  try {
>      // Lấy slide đầu tiên
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Tải tệp âm thanh wav vào luồng
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Thêm Audio Frame
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Đặt chế độ phát và âm lượng của Audio
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Ghi tệp PowerPoint ra đĩa
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |
| audio_stream | java.io.InputStream | Luồng nhập chứa dữ liệu âm thanh WAV để nhúng. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Đối tượng [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Tạo một khung âm thanh mới với tệp WAV được nhúng và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định. Âm thanh được nhúng sẽ được thêm vào bộ sưu tập Presentation.Audios.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, nơi sẽ chèn khung âm thanh. |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |
| audio_stream | java.io.InputStream | Luồng nhập chứa dữ liệu âm thanh WAV để nhúng. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Đối tượng [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Tạo một khung âm thanh mới và thêm nó vào cuối bộ sưu tập hình dạng bằng cách sử dụng một đối tượng âm thanh hiện có trong danh sách Presentation.Audios.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Một thể hiện [IAudio](../../com.aspose.slides/iaudio) từ bộ sưu tập Presentation.Audios. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Đối tượng [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Tạo một khung âm thanh mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục đã chỉ định bằng cách sử dụng một đối tượng âm thanh hiện có trong danh sách Presentation.Audios.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0, nơi sẽ chèn khung âm thanh. |
| x | float | Tọa độ x của khung âm thanh mới, tính bằng điểm. |
| y | float | Tọa độ y của khung âm thanh mới, tính bằng điểm. |
| width | float | Chiều rộng của khung âm thanh mới, tính bằng điểm. |
| height | float | Chiều cao của khung âm thanh mới, tính bằng điểm. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Một thể hiện [IAudio](../../com.aspose.slides/iaudio) từ bộ sưu tập Presentation.Audios để nhúng. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Đối tượng [IAudioFrame](../../com.aspose.slides/iaudioframe) mới được tạo.

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của hình dạng trong bộ sưu tập hình dạng nếu tìm thấy; nếu không, \\u20131.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Hình dạng cần tìm trong bộ sưu tập. |

**Returns:**
int - Chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên của hình dạng trong bộ sưu tập hình dạng nếu tìm thấy; nếu không, \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Tạo và trả về một mảng chứa tất cả các hình dạng.

**Returns:**
com.aspose.slides.IShape[] - Một mảng các đối tượng [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Tạo và trả về một mảng chứa tất cả các hình dạng trong khoảng đã chỉ định.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| startIndex | int | Chỉ mục của hình dạng đầu tiên cần trả về. |
| count | int | Số lượng hình dạng cần trả về. |

**Returns:**
com.aspose.slides.IShape[] - Một mảng các đối tượng [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Di chuyển hình dạng đã chỉ định đến vị trí mới trong bộ sưu tập hình dạng.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục mục tiêu bắt đầu từ 0, nơi hình dạng sẽ được đặt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Đối tượng [IShape](../../com.aspose.slides/ishape) cần di chuyển trong bộ sưu tập. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Di chuyển các hình dạng đã chỉ định trong bộ sưu tập hình dạng, đặt chúng bắt đầu tại chỉ mục đã cho.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục mục tiêu bắt đầu từ 0, nơi hình dạng đầu tiên được chỉ định sẽ được đặt; các hình dạng tiếp theo sẽ được sắp xếp theo thứ tự đã cung cấp. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Một hoặc nhiều thể hiện [IShape](../../com.aspose.slides/ishape) để di chuyển trong bộ sưu tập. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Tạo một auto shape mới với định dạng mặc định và thêm nó vào cuối bộ sưu tập hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của auto shape cần thêm. |
| x | float | Tọa độ x của khung hình dạng, tính bằng điểm. |
| y | float | Tọa độ y của khung hình dạng, tính bằng điểm. |
| width | float | Chiều rộng của khung hình dạng, tính bằng điểm. |
| height | float | Chiều cao của khung hình dạng, tính bằng điểm. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đối tượng [IAutoShape](../../com.aspose.slides/iautoshape) mới được tạo.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một auto shape mới và thêm nó vào cuối bộ sưu tập hình dạng, tùy chọn khởi tạo với định dạng mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của auto shape cần thêm. |
| x | float | Tọa độ x của khung hình dạng, tính bằng điểm. |
| y | float | Tọa độ y của khung hình dạng, tính bằng điểm. |
| width | float | Chiều rộng của khung hình dạng, tính bằng điểm. |
| height | float | Chiều cao của khung hình dạng, tính bằng điểm. |
| createFromTemplate | boolean | Đúng để áp dụng kiểu mẫu mặc định (kiểu đơn giản, văn bản căn giữa và tên không rỗng) cho shape mới; sai để tạo shape với tất cả thuộc tính được đặt thành giá trị mặc định. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đối tượng [IAutoShape](../../com.aspose.slides/iautoshape) mới được tạo.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Tạo một auto shape hình chữ nhật mới để chứa nội dung toán học và thêm nó vào cuối bộ sưu tập hình dạng.

> ```
> Ví dụ sau đây minh họa cách thêm Phương trình toán học vào bản trình chiếu PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape mathShape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 720, 150);
>      IMathParagraph mathParagraph = ((MathPortion)mathShape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      IMathFraction fraction = new MathematicalText("x").divide("y");
>      mathParagraph.add(new MathBlock(fraction));
>      IMathBlock mathBlock = new MathematicalText("c")
>          .setSuperscript("2")
>          .join("=")
>          .join(new MathematicalText("a").setSuperscript("2"))
>          .join("+")
>          .join(new MathematicalText("b").setSuperscript("2"));
>      mathParagraph.add(mathBlock);
>      pres.save("math.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung hình dạng, tính bằng điểm. |
| y | float | Tọa độ y của khung hình dạng, tính bằng điểm. |
| width | float | Chiều rộng của khung hình dạng, tính bằng điểm. |
| height | float | Chiều cao của khung hình dạng, tính bằng điểm. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đối tượng [IAutoShape](../../com.aspose.slides/iautoshape) mới được tạo.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Tạo một auto shape mới và chèn nó vào bộ sưu tập hình dạng tại vị trí chỉ định, áp dụng định dạng mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí chèn auto shape mới. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của auto shape cần chèn. |
| x | float | Tọa độ x của khung hình dạng, tính bằng điểm. |
| y | float | Tọa độ y của khung hình dạng, tính bằng điểm. |
| width | float | Chiều rộng của khung hình dạng, tính bằng điểm. |
| height | float | Chiều cao của khung hình dạng, tính bằng điểm. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đối tượng [IAutoShape](../../com.aspose.slides/iautoshape) mới được tạo.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một auto shape mới và chèn nó vào bộ sưu tập hình dạng tại vị trí chỉ định, tùy chọn khởi tạo với kiểu mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí chèn auto shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của auto shape cần chèn. |
| x | float | Tọa độ x của khung hình dạng, tính bằng điểm. |
| y | float | Tọa độ y của khung hình dạng, tính bằng điểm. |
| width | float | Chiều rộng của khung hình dạng, tính bằng điểm. |
| height | float | Chiều cao của khung hình dạng, tính bằng điểm. |
| createFromTemplate | boolean | Đúng để áp dụng kiểu mẫu mặc định (bao gồm tên không rỗng, kiểu đơn giản và văn bản căn giữa); sai để tạo shape với tất cả thuộc tính được đặt thành giá trị mặc định. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đối tượng [IAutoShape](../../com.aspose.slides/iautoshape) mới được tạo.

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Tạo một group shape mới rỗng và thêm nó vào cuối bộ sưu tập hình dạng. Khung của nhóm sẽ tự động điều chỉnh để phù hợp với bất kỳ hình dạng nào được thêm vào.

> ```
> Ví dụ sau đây cho thấy cách thêm một nhóm hình dạng vào slide của bản trình chiếu PowerPoint.
>  
>  // Khởi tạo lớp Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Lấy slide đầu tiên
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Truy cập bộ sưu tập hình dạng của slide
>      IShapeCollection slideShapes = sld.getShapes();
>      // Thêm một nhóm hình dạng vào slide
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Thêm các hình dạng vào nhóm đã thêm
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Thêm khung cho nhóm hình dạng
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Ghi tệp PPTX ra đĩa
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Giá trị trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Đối tượng [IGroupShape](../../com.aspose.slides/igroupshape) mới được tạo.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Tạo một group shape mới, chuyển đổi ảnh SVG đã chỉ định thành các shape riêng lẻ, và thêm nhóm kết quả vào cuối bộ sưu tập hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) chứa nội dung vector để chuyển đổi thành các shape. |
| x | float | Tọa độ x của khung nhóm, tính bằng điểm. |
| y | float | Tọa độ y của khung nhóm, tính bằng điểm. |
| width | float | Chiều rộng của khung nhóm, tính bằng điểm. |
| height | float | Chiều cao của khung nhóm, tính bằng điểm. |

**Giá trị trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Đối tượng [IGroupShape](../../com.aspose.slides/igroupshape) mới được tạo.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Tạo một group shape mới rỗng và chèn nó vào bộ sưu tập hình dạng tại vị trí chỉ định. Khung của nhóm sẽ tự động điều chỉnh để phù hợp với bất kỳ hình dạng nào được thêm vào.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí chèn group shape. |

**Giá trị trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Đối tượng [IGroupShape](../../com.aspose.slides/igroupshape) mới được tạo.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Tạo một connector shape mới với kiểu mẫu mặc định và thêm nó vào cuối bộ sưu tập hình dạng.

> ```
> The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint Presentation.
>  
>  // Instantiates a presentation class that represents a PPTX file
>  Presentation pres = new Presentation();
>  try {
>      // Accesses the shapes collection for a specific slide
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Adds an Ellipse autoshape
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Adds a Rectangle autoshape
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Adds a connector shape to the slide shape collection
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Connects the shapes using the connector
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Calls reroute that sets the automatic shortest path between shapes
>      connector.reroute();
>      // Saves the presentation
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của connector shape cần thêm. |
| x | float | Tọa độ x của khung connector, tính bằng điểm. |
| y | float | Tọa độ y của khung connector, tính bằng điểm. |
| width | float | Chiều rộng của khung connector, tính bằng điểm. |
| height | float | Chiều cao của khung connector, tính bằng điểm. |

**Giá trị trả về:**
[IConnector](../../com.aspose.slides/iconnector) - Đối tượng [IConnector](../../com.aspose.slides/iconnector) mới được tạo.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một connector shape mới và thêm nó vào cuối bộ sưu tập hình dạng, tùy chọn áp dụng kiểu mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của connector shape cần tạo. |
| x | float | Tọa độ x của khung connector, tính bằng điểm. |
| y | float | Tọa độ y của khung connector, tính bằng điểm. |
| width | float | Chiều rộng của khung connector, tính bằng điểm. |
| height | float | Chiều cao của khung connector, tính bằng điểm. |
| createFromTemplate | boolean | Đúng để áp dụng kiểu mẫu mặc định (tên không rỗng, kiểu đơn giản); sai để tạo connector với các giá trị thuộc tính mặc định. |

**Giá trị trả về:**
[IConnector](../../com.aspose.slides/iconnector) - Đối tượng [IConnector](../../com.aspose.slides/iconnector) mới được tạo.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Tạo một connector shape mới và chèn nó vào bộ sưu tập hình dạng tại vị trí chỉ định, áp dụng kiểu mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí chèn connector shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của connector shape cần chèn. |
| x | float | Tọa độ x của khung connector, tính bằng điểm. |
| y | float | Tọa độ y của khung connector, tính bằng điểm. |
| width | float | Chiều rộng của khung connector, tính bằng điểm. |
| height | float | Chiều cao của khung connector, tính bằng điểm. |

**Giá trị trả về:**
[IConnector](../../com.aspose.slides/iconnector) - Đối tượng [IConnector](../../com.aspose.slides/iconnector) mới được tạo.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một connector shape mới và chèn nó vào bộ sưu tập hình dạng tại vị trí chỉ định, tùy chọn áp dụng kiểu mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí chèn connector shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của connector shape cần chèn. |
| x | float | Tọa độ x của khung connector, tính bằng điểm. |
| y | float | Tọa độ y của khung connector, tính bằng điểm. |
| width | float | Chiều rộng của khung connector, tính bằng điểm. |
| height | float | Chiều cao của khung connector, tính bằng điểm. |
| createFromTemplate | boolean | Đúng để áp dụng kiểu mẫu mặc định (tên không rỗng, kiểu đơn giản); sai để tạo connector với các giá trị thuộc tính mặc định. |

**Giá trị trả về:**
[IConnector](../../com.aspose.slides/iconnector) - Đối tượng [IConnector](../../com.aspose.slides/iconnector) mới được tạo.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Tạo một picture frame mới chứa hình ảnh đã chỉ định và thêm nó vào cuối bộ sưu tập hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | Chỉ định loại shape chứa trong [ShapeType](../../com.aspose.slides/shapetype), ngoại trừ mọi loại đường:<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5. |
| x | float | Tọa độ x của picture frame, tính bằng điểm. |
| y | float | Tọa độ y của picture frame, tính bằng điểm. |
| width | float | Chiều rộng của picture frame, tính bằng điểm. |
| height | float | Chiều cao của picture frame, tính bằng điểm. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) để hiển thị trong picture frame. |

**Giá trị trả về:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Đối tượng [IPictureFrame](../../com.aspose.slides/ipictureframe) mới được tạo.

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Tạo một picture frame mới chứa hình ảnh đã chỉ định và chèn nó vào bộ sưu tập hình dạng tại vị trí chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí chèn picture frame. |
| shapeType | int | Chỉ định loại shape chứa trong [ShapeType](../../com.aspose.slides/shapetype), ngoại trừ mọi loại đường:<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5. |
| x | float | Tọa độ x của picture frame, tính bằng điểm. |
| y | float | Tọa độ y của picture frame, tính bằng điểm. |
| width | float | Chiều rộng của picture frame, tính bằng điểm. |
| height | float | Chiều cao của picture frame, tính bằng điểm. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) để hiển thị trong picture frame. |

**Giá trị trả về:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Đối tượng [IPictureFrame](../../com.aspose.slides/ipictureframe) mới được tạo.

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Tạo một bảng mới và thêm nó vào cuối bộ sưu tập hình dạng.

> ```
> Các ví dụ sau đây minh họa cách thêm bảng vào bản trình chiếu PowerPoint.
>  
>  // Khởi tạo lớp Presentation đại diện cho tệp PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Truy cập slide đầu tiên
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Định nghĩa các cột với độ rộng và các hàng với chiều cao
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Thêm hình dạng bảng vào slide
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Đặt định dạng đường viền cho mỗi ô
>      for (int row = 0; row < tbl.getRows().size(); row++)
>      {
>          for (int cell = 0; cell < tbl.getRows().get_Item(row).size(); cell++)
>          {
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().setFillType((FillType.Solid));
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().setWidth(5);
>          }
>      }
>      // Gộp các ô 1 và 2 của hàng 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Thêm văn bản vào ô đã gộp
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Lưu PPTX vào đĩa
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Các tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Tọa độ x của bảng, tính bằng điểm. |
| y | float | Tọa độ y của bảng, tính bằng điểm. |
| columnWidths | double[] | Mảng các số double biểu thị độ rộng của các cột trong bảng, tính bằng điểm. |
| rowHeights | double[] | Mảng các số double biểu thị độ cao của các hàng trong bảng, tính bằng điểm. |

**Giá trị trả về:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) mới được tạo.
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Tạo một bảng mới và chèn nó vào bộ sưu tập shape tại chỉ mục được chỉ định.

**Các tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí sẽ chèn bảng. |
| x | float | Tọa độ x của bảng, tính bằng điểm. |
| y | float | Tọa độ y của bảng, tính bằng điểm. |
| columnWidths | double[] | Mảng các số double biểu thị độ rộng của các cột trong bảng, tính bằng điểm. |
| rowHeights | double[] | Mảng các số double biểu thị độ cao của các hàng trong bảng, tính bằng điểm. |

**Giá trị trả về:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) mới được tạo.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa shape tại chỉ mục được chỉ định khỏi bộ sưu tập shape.

**Các tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của shape sẽ bị xóa. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Xóa lần xuất hiện đầu tiên của shape được chỉ định khỏi bộ sưu tập shape.

**Các tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Đối tượng [IShape](../../com.aspose.slides/ishape) cần xóa. |

### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các shape khỏi bộ sưu tập shape.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Trả về một iterator java cho toàn bộ bộ sưu tập.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - java.util.Iterator cho toàn bộ bộ sưu tập.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Lấy đối tượng shape nhóm cha cho bộ sưu tập shapes. Chỉ đọc [IGroupShape](../../com.aspose.slides/igroupshape).

**Giá trị trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Tạo một bản sao của shape được chỉ định và thêm nó vào cuối bộ sưu tập shape.

**Các tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape sẽ được sao chép. |
| x | float | Tọa độ x của khung shape mới, tính bằng điểm. |
| y | float | Tọa độ y của khung shape mới, tính bằng điểm. |
| width | float | Độ rộng của khung shape mới, tính bằng điểm. |
| height | float | Độ cao của khung shape mới, tính bằng điểm. |

**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới được tạo.
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Tạo một bản sao của shape được chỉ định và thêm nó vào cuối bộ sưu tập shape. Shape mới giữ nguyên độ rộng và độ cao của sourceShape.

**Các tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape sẽ được sao chép. |
| x | float | Tọa độ x của khung shape mới, tính bằng điểm. |
| y | float | Tọa độ y của khung shape mới, tính bằng điểm. |

**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới được tạo.
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Tạo một bản sao của shape được chỉ định và thêm nó vào cuối bộ sưu tập shape. Shape được sao chép giữ nguyên vị trí và kích thước của shape gốc.

**Các tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Đối tượng [IShape](../../com.aspose.slides/ishape) sẽ được sao chép. |

**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới được tạo.
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Tạo một bản sao của shape được chỉ định và chèn nó vào bộ sưu tập shape tại chỉ mục được chỉ định.

**Các tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí sẽ chèn shape sao chép. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Đối tượng [IShape](../../com.aspose.slides/ishape) sẽ được sao chép. |
| x | float | Tọa độ x của khung shape sao chép, tính bằng điểm. |
| y | float | Tọa độ y của khung shape sao chép, tính bằng điểm. |
| width | float | Độ rộng của khung shape sao chép, tính bằng điểm. |
| height | float | Độ cao của khung shape sao chép, tính bằng điểm. |

**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới được tạo.
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Tạo một bản sao của shape được chỉ định và chèn nó vào bộ sưu tập shape tại chỉ mục được chỉ định. Shape mới giữ nguyên độ rộng và độ cao của sourceShape.

**Các tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí sẽ chèn shape sao chép. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Đối tượng [IShape](../../com.aspose.slides/ishape) sẽ được sao chép. |
| x | float | Tọa độ x của khung shape sao chép, tính bằng điểm. |
| y | float | Tọa độ y của khung shape sao chép, tính bằng điểm. |

**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới được tạo.
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Tạo một bản sao của shape được chỉ định và chèn nó vào bộ sưu tập shape tại chỉ mục được chỉ định. Shape được sao chép giữ nguyên vị trí và kích thước của shape gốc.

**Các tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí sẽ chèn shape sao chép. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Đối tượng [IShape](../../com.aspose.slides/ishape) sẽ được sao chép. |

**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới được tạo.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định.

**Các tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (an toàn với đa luồng) hay không. Chỉ đọc boolean.

**Giá trị trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về gốc đồng bộ. Chỉ đọc Object.

**Giá trị trả về:**
java.lang.Object