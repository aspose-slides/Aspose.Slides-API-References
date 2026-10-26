---
title: ShapeCollection
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Biểu diễn một bộ sưu tập các shape.
type: docs
url: /vi/com.aspose.slides/shapecollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Đại diện cho một bộ sưu tập các shape.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Lấy số phần tử thực sự chứa trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử ở chỉ mục đã chỉ định. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Tạo một biểu đồ mới, khởi tạo với dữ liệu series mẫu và cài đặt, và thêm vào cuối bộ sưu tập shape. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Tạo một biểu đồ mới, khởi tạo với dữ liệu series mẫu và cài đặt, và thêm vào cuối bộ sưu tập shape. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Tạo một sơ đồ SmartArt và thêm vào cuối bộ sưu tập shape. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Tạo một biểu đồ mới, khởi tạo với dữ liệu series mẫu và cài đặt, và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Tạo một biểu đồ mới, khởi tạo với dữ liệu series mẫu và cài đặt, và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Tạo một khung Zoom mới và thêm vào cuối bộ sưu tập shape. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Tạo một khung Zoom mới và thêm vào cuối bộ sưu tập shape. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Tạo một khung Zoom mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Tạo một khung Zoom mới với hình ảnh đã định trước và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Tạo một khung Section Zoom mới và thêm vào cuối bộ sưu tập shape. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Tạo một khung Section Zoom mới với hình ảnh đã định trước và thêm vào cuối bộ sưu tập shape. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Tạo một khung Section Zoom mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Tạo một khung Section Zoom mới với hình ảnh đã định trước và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Tạo một khung Summary Zoom mới và thêm vào cuối bộ sưu tập shape. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Tạo một khung Summary Zoom mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Tạo một khung đối tượng OLE mới và thêm vào cuối bộ sưu tập shape. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Tạo một khung đối tượng OLE mới và thêm vào cuối bộ sưu tập shape. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Tạo một khung đối tượng OLE mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Tạo một khung đối tượng OLE mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Tạo một khung video mới và thêm vào cuối bộ sưu tập shape. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Tạo một khung video mới và thêm vào cuối bộ sưu tập shape. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Tạo một khung video mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Tạo một khung audio mới liên kết tới một track CD và thêm vào cuối bộ sưu tập shape. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Tạo một khung audio mới liên kết tới một track CD và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Tạo một khung audio mới liên kết tới tệp audio bên ngoài và thêm vào cuối bộ sưu tập shape. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Tạo một khung audio mới liên kết tới tệp audio bên ngoài và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Tạo một khung audio mới với tệp WAV nhúng và thêm vào cuối bộ sưu tập shape. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Tạo một khung audio mới với tệp WAV nhúng và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Tạo một khung audio mới và thêm vào cuối bộ sưu tập shape bằng cách sử dụng đối tượng audio hiện có trong danh sách Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Tạo một khung audio mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định bằng cách sử dụng đối tượng audio hiện có trong danh sách Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Trả về chỉ mục dựa trên 0 của lần xuất hiện đầu tiên của shape đã chỉ định trong bộ sưu tập. |
| [toArray()](#toArray--) | Tạo và trả về một mảng chứa tất cả các shape. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tạo và trả về một mảng chứa tất cả các shape trong phạm vi đã chỉ định. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Di chuyển shape đã chỉ định tới vị trí mới trong bộ sưu tập shape. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Di chuyển các shape đã chỉ định trong bộ sưu tập shape, đặt chúng bắt đầu tại chỉ mục đã cho. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Tạo một auto shape mới với định dạng mặc định và thêm vào cuối bộ sưu tập shape. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Tạo một auto shape mới và thêm vào cuối bộ sưu tập shape, tùy chọn khởi tạo với định dạng mẫu mặc định. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Tạo một auto shape hình chữ nhật mới để chứa nội dung toán học và thêm vào cuối bộ sưu tập shape. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Tạo một auto shape mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định, áp dụng định dạng mẫu mặc định. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Tạo một auto shape mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định, tùy chọn khởi tạo với kiểu mẫu mặc định. |
| [addGroupShape()](#addGroupShape--) | Tạo một group shape trống mới và thêm vào cuối bộ sưu tập shape. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Tạo một group shape mới, chuyển đổi hình ảnh SVG đã chỉ định thành các shape riêng lẻ, và thêm group kết quả vào cuối bộ sưu tập shape. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Tạo một group shape trống mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Tạo một connector shape mới với kiểu mẫu mặc định và thêm vào cuối bộ sưu tập shape. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Tạo một connector shape mới và thêm vào cuối bộ sưu tập shape, tùy chọn áp dụng kiểu mẫu mặc định. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Tạo một connector shape mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định, áp dụng kiểu mẫu mặc định. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Tạo một connector shape mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định, tùy chọn áp dụng kiểu mẫu mặc định. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Tạo một picture frame mới chứa hình ảnh đã chỉ định và thêm vào cuối bộ sưu tập shape. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Tạo một picture frame mới chứa hình ảnh đã chỉ định và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Tạo một table mới và thêm vào cuối bộ sưu tập shape. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Tạo một table mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa shape ở chỉ mục đã chỉ định khỏi bộ sưu tập shape. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Xóa lần xuất hiện đầu tiên của shape đã chỉ định khỏi bộ sưu tập shape. |
| [clear()](#clear--) | Xóa tất cả các shape khỏi bộ sưu tập shape. |
| [iterator()](#iterator--) | Trả về một enumerator cho phép duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [getParentGroup()](#getParentGroup--) | Lấy đối tượng parent group shape cho bộ sưu tập shape. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Tạo một bản sao của shape đã chỉ định và thêm vào cuối bộ sưu tập shape. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Tạo một bản sao của shape đã chỉ định và thêm vào cuối bộ sưu tập shape. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Tạo một bản sao của shape đã chỉ định và thêm vào cuối bộ sưu tập shape. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Tạo một bản sao của shape đã chỉ định và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Tạo một bản sao của shape đã chỉ định và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Tạo một bản sao của shape đã chỉ định và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng đã chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về một giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |

### size() {#size--}
```
public final int size()
```

Lấy số phần tử thực sự chứa trong bộ sưu tập. Chỉ đọc `int`.

**Trả về:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Lấy phần tử ở chỉ mục đã chỉ định. Chỉ đọc [IShape](../../com.aspose.slides/ishape).

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

Tạo một biểu đồ mới, khởi tạo với dữ liệu series mẫu và cài đặt, và thêm vào cuối bộ sưu tập shape.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Tạo một thể hiện của lớp Presentation đại diện cho tệp PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Truy cập slide đầu tiên
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Thêm một biểu đồ với dữ liệu mặc định của nó
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Đặt tiêu đề cho biểu đồ
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Đặt series đầu tiên để hiển thị giá trị
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Đặt chỉ mục cho bảng dữ liệu biểu đồ
>      int defaultWorksheetIndex = 0;
>      // Lấy worksheet dữ liệu biểu đồ
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Xóa các series và categories được tạo mặc định
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Thêm series mới
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Thêm categories mới
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Lấy series biểu đồ đầu tiên
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Điền dữ liệu cho series
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Đặt màu nền cho series
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Lấy series biểu đồ thứ hai
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Điền dữ liệu cho series
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Đặt màu nền cho series
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Đặt nhãn đầu tiên để hiển thị tên Category
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Đặt series để hiển thị giá trị cho nhãn thứ ba
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
| type | int | Loại biểu đồ sẽ thêm. |
| x | float | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | float | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | float | Độ rộng của biểu đồ, tính bằng điểm. |
| height | float | Độ cao của biểu đồ, tính bằng điểm. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) mới tạo.

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Tạo một biểu đồ mới, khởi tạo với dữ liệu series mẫu và cài đặt, và thêm vào cuối bộ sưu tập shape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại biểu đồ sẽ thêm. |
| x | float | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | float | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | float | Độ rộng của biểu đồ, tính bằng điểm. |
| height | float | Độ cao của biểu đồ, tính bằng điểm. |
| initWithSample | boolean | `true` để khởi tạo biểu đồ mới với dữ liệu series mẫu và cài đặt; `false` để tạo biểu đồ không có series và chỉ có cài đặt tối thiểu, giúp tạo nhanh hơn. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) mới tạo.

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Tạo một sơ đồ SmartArt và thêm vào cuối bộ sưu tập shape.

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
| width | float | Độ rộng của khung sơ đồ, tính bằng điểm. |
| height | float | Độ cao của khung sơ đồ, tính bằng điểm. |
| layoutType | int | Loại bố cục SmartArt. |

**Trả về:**
[ISmartArt](../../com.aspose.slides/ismartart) - [ISmartArt](../../com.aspose.slides/ismartart) mới tạo.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Tạo một biểu đồ mới, khởi tạo với dữ liệu series mẫu và cài đặt, và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại biểu đồ sẽ tạo. |
| x | float | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | float | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | float | Độ rộng của biểu đồ mới, tính bằng điểm. |
| height | float | Độ cao của biểu đồ mới, tính bằng điểm. |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn biểu đồ mới vào bộ sưu tập shape. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) mới tạo.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Tạo một biểu đồ mới, khởi tạo với dữ liệu series mẫu và cài đặt, và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại biểu đồ sẽ tạo. |
| x | float | Tọa độ x của biểu đồ mới, tính bằng điểm. |
| y | float | Tọa độ y của biểu đồ mới, tính bằng điểm. |
| width | float | Độ rộng của biểu đồ mới, tính bằng điểm. |
| height | float | Độ cao của biểu đồ mới, tính bằng điểm. |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn biểu đồ mới vào bộ sưu tập shape. |
| initWithSample | boolean | `true` để khởi tạo biểu đồ mới với dữ liệu series mẫu và cài đặt; `false` để tạo biểu đồ không có series và chỉ có cài đặt tối thiểu, giúp tạo nhanh hơn. |

**Trả về:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) mới tạo.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Tạo một khung Zoom mới và thêm vào cuối bộ sưu tập shape.

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
| width | float | Độ rộng của khung Zoom mới, tính bằng điểm. |
| height | float | Độ cao của khung Zoom mới, tính bằng điểm. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) được tham chiếu bởi khung Zoom; phải thuộc bài thuyết trình này. |

**Trả về:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) mới tạo.

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Tạo một khung Zoom mới và thêm vào cuối bộ sưu tập shape.

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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | float | Độ rộng của khung Zoom mới, tính bằng điểm. |
| height | float | Độ cao của khung Zoom mới, tính bằng điểm. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) được tham chiếu bởi khung Zoom; phải thuộc bài thuyết trình này. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Hình ảnh cho slide được tham chiếu [IPPImage](../../com.aspose.slides/ippimage). |

**Trả về:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) mới tạo.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Tạo một khung Zoom mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

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
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn khung Zoom. |
| x | float | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | float | Độ rộng của khung Zoom mới, tính bằng điểm. |
| height | float | Độ cao của khung Zoom mới, tính bằng điểm. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) được tham chiếu bởi khung Zoom. |

**Trả về:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) mới tạo.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Tạo một khung Zoom mới với hình ảnh đã định trước và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn khung Zoom. |
| x | float | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | float | Độ rộng của khung Zoom mới, tính bằng điểm. |
| height | float | Độ cao của khung Zoom mới, tính bằng điểm. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) được tham chiếu bởi khung Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Hình ảnh cho slide được tham chiếu [IPPImage](../../com.aspose.slides/ippimage). |

**Trả về:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) mới tạo.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Tạo một khung Section Zoom mới và thêm vào cuối bộ sưu tập shape.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| width | float | Độ rộng của khung Section Zoom mới, tính bằng điểm. |
| height | float | Độ cao của khung Section Zoom mới, tính bằng điểm. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc bài thuyết trình này và chứa ít nhất một slide. |

**Trả về:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới tạo.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Tạo một khung Section Zoom mới với hình ảnh đã định trước và thêm vào cuối bộ sưu tập shape.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| width | float | Độ rộng của khung Section Zoom mới, tính bằng điểm. |
| height | float | Độ cao của khung Section Zoom mới, tính bằng điểm. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc bài thuyết trình này và chứa ít nhất một slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) sẽ hiển thị trong khung Section Zoom. |

**Trả về:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới tạo.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Tạo một khung Section Zoom mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

--------------------

> ```
> This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn khung Section Zoom. |
| x | float | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | float | Độ rộng của khung Section Zoom mới, tính bằng điểm. |
| height | float | Độ cao của khung Section Zoom mới, tính bằng điểm. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc bài thuyết trình này và chứa ít nhất một slide. |

**Trả về:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới tạo.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Tạo một khung Section Zoom mới với hình ảnh đã định trước và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

--------------------

> ```
> Ví dụ này minh họa cách tạo và chèn một đối tượng Section Zoom vào vị trí chỉ định trong một bộ sưu tập
>  (giả sử có ít nhất hai phần trong bản trình bày "Presentation.pptx"):
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
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn khung Section Zoom. |
| x | float | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | float | Độ rộng của khung Section Zoom mới, tính bằng điểm. |
| height | float | Độ cao của khung Section Zoom mới, tính bằng điểm. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc bài thuyết trình này và chứa ít nhất một slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Hình ảnh sẽ hiển thị trong khung Section Zoom. |

**Trả về:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) mới tạo.

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Tạo một khung Summary Zoom mới và thêm vào cuối bộ sưu tập shape.

--------------------

> ```
> Ví dụ này minh họa cách thêm một đối tượng Summary Zoom vào cuối một bộ sưu tập
>  (giả sử có ít nhất hai phần trong bản trình bày "Presentation.pptx"):
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
| width | float | Độ rộng của khung Summary Zoom mới, tính bằng điểm. |
| height | float | Độ cao của khung Summary Zoom mới, tính bằng điểm. |

--------------------

Phương thức này tạo một Summary Zoom mới và đặt một bộ sưu tập các đối tượng vào nó cho tất cả các phần trong bài thuyết trình này.

**Trả về:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) mới tạo.

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Tạo một khung Summary Zoom mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

--------------------

> ```
> This example demonstrates creation and inserting a Summary Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn khung Summary Zoom. |
| x | float | Tọa độ x của khung Summary Zoom mới, tính bằng điểm. |
| y | float | Tọa độ y của khung Summary Zoom mới, tính bằng điểm. |
| width | float | Độ rộng của khung Summary Zoom mới, tính bằng điểm. |
| height | float | Độ cao của khung Summary Zoom mới, tính bằng điểm. |

--------------------

Phương thức này tạo một khung Summary Zoom tổng hợp các liên kết tóm tắt cho tất cả các phần trong bài thuyết trình.

**Trả về:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) mới tạo.

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Tạo một khung đối tượng OLE mới và thêm vào cuối bộ sưu tập shape.

--------------------

> ```
> Các ví dụ sau đây minh họa cách thêm khung đối tượng OLE vào các slide của PowerPoint Presentation.
>  
>  // Tạo một thể hiện của lớp Presentation đại diện cho tệp PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Truy cập slide đầu tiên
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Tải một tệp Excel vào luồng
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
>      // Thêm một shape khung đối tượng OLE
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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | float | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | float | Độ rộng của khung OLE mới, tính bằng điểm. |
| height | float | Độ cao của khung OLE mới, tính bằng điểm. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Thông tin về dữ liệu OLE nhúng ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Trả về:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) mới tạo.

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Tạo một khung đối tượng OLE mới và thêm vào cuối bộ sưu tập shape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | float | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | float | Độ rộng của khung OLE mới, tính bằng điểm. |
| height | float | Độ cao của khung OLE mới, tính bằng điểm. |
| className | java.lang.String | Tên lớp của đối tượng OLE. |
| path | java.lang.String | Đường dẫn tới tệp được liên kết.

Đường dẫn này được lưu nguyên trong bài thuyết trình. Nếu chỉ định đường dẫn tương đối, tệp sẽ không truy cập được khi mở bài thuyết trình từ thư mục khác. |

**Trả về:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) mới tạo.

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Tạo một khung đối tượng OLE mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

--------------------

> ```
> Ví dụ này minh họa cách chèn một đối tượng OLE vào vị trí thứ hai:
>  
>  byte[] fileData = ... // "test.zip"
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn khung OLE. |
| x | float | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | float | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | float | Độ rộng của khung OLE mới, tính bằng điểm. |
| height | float | Độ cao của khung OLE mới, tính bằng điểm. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Thông tin dữ liệu OLE nhúng ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Trả về:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) mới tạo.

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Tạo một khung đối tượng OLE mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn khung OLE. |
| x | float | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | float | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | float | Độ rộng của khung OLE mới, tính bằng điểm. |
| height | float | Độ cao của khung OLE mới, tính bằng điểm. |
| className | java.lang.String | Tên lớp của đối tượng OLE. |
| path | java.lang.String | Đường dẫn tới tệp được liên kết.

Đường dẫn này được lưu nguyên trong bài thuyết trình. Nếu chỉ định đường dẫn tương đối, tệp sẽ không truy cập được khi mở bài thuyết trình từ thư mục khác. |

**Trả về:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Khung đối tượng OLE mới tạo.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Tạo một khung video mới và thêm vào cuối bộ sưu tập shape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung video mới, tính bằng điểm. |
| y | float | Tọa độ y của khung video mới, tính bằng điểm. |
| width | float | Độ rộng của khung video mới, tính bằng điểm. |
| height | float | Độ cao của khung video mới, tính bằng điểm. |
| fname | java.lang.String | Đường dẫn hoặc tên của tệp video sẽ nhúng. |

**Trả về:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) mới tạo.

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Tạo một khung video mới và thêm vào cuối bộ sưu tập shape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung video mới, tính bằng điểm. |
| y | float | Tọa độ y của khung video mới, tính bằng điểm. |
| width | float | Độ rộng của khung video mới, tính bằng điểm. |
| height | float | Độ cao của khung video mới, tính bằng điểm. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) sẽ nhúng trong khung video. |

**Trả về:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) mới tạo.

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Tạo một khung video mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn khung video. |
| x | float | Tọa độ x của khung video mới, tính bằng điểm. |
| y | float | Tọa độ y của khung video mới, tính bằng điểm. |
| width | float | Độ rộng của khung video mới, tính bằng điểm. |
| height | float | Độ cao của khung video mới, tính bằng điểm. |
| fname | java.lang.String | Đường dẫn hoặc tên của tệp video sẽ nhúng. |

**Trả về:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) mới tạo.

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Tạo một khung audio mới liên kết tới một track CD và thêm vào cuối bộ sưu tập shape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung audio mới, tính bằng điểm. |
| y | float | Tọa độ y của khung audio mới, tính bằng điểm. |
| width | float | Độ rộng của khung audio mới, tính bằng điểm. |
| height | float | Độ cao của khung audio mới, tính bằng điểm. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Tạo một khung audio mới liên kết tới một track CD và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn khung audio. |
| x | float | Tọa độ x của khung audio mới, tính bằng điểm. |
| y | float | Tọa độ y của khung audio mới, tính bằng điểm. |
| width | float | Độ rộng của khung audio mới, tính bằng điểm. |
| height | float | Độ cao của khung audio mới, tính bằng điểm. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Tạo một khung audio mới liên kết tới tệp audio bên ngoài và thêm vào cuối bộ sưu tập shape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung audio mới, tính bằng điểm. |
| y | float | Tọa độ y của khung audio mới, tính bằng điểm. |
| width | float | Độ rộng của khung audio mới, tính bằng điểm. |
| height | float | Độ cao của khung audio mới, tính bằng điểm. |
| fname | java.lang.String | Đường dẫn hoặc tên của tệp audio bên ngoài sẽ liên kết. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Tạo một khung audio mới liên kết tới tệp audio bên ngoài và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn khung audio. |
| x | float | Tọa độ x của khung audio mới, tính bằng điểm. |
| y | float | Tọa độ y của khung audio mới, tính bằng điểm. |
| width | float | Độ rộng của khung audio mới, tính bằng điểm. |
| height | float | Độ cao của khung audio mới, tính bằng điểm. |
| fname | java.lang.String | Đường dẫn hoặc tên của tệp audio bên ngoài sẽ liên kết. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Tạo một khung audio mới với tệp WAV được nhúng và thêm vào cuối bộ sưu tập shape. Audio nhúng được thêm vào bộ sưu tập Presentation.Audios.

--------------------

> ```
> The following examples shows how to create Audio Frame.
>  
>  // Tạo một thể hiện của lớp Presentation đại diện cho tệp trình chiếu
>  Presentation pres = new Presentation();
>  try {
>      // Lấy slide đầu tiên
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Tải tệp âm thanh wav vào luồng
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Thêm Audio Frame
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Đặt chế độ phát và âm lượng cho audio
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


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung audio mới, tính bằng điểm. |
| y | float | Tọa độ y của khung audio mới, tính bằng điểm. |
| width | float | Độ rộng của khung audio mới, tính bằng điểm. |
| height | float | Độ cao của khung audio mới, tính bằng điểm. |
| audio_stream | java.io.InputStream | Luồng đầu vào chứa dữ liệu audio WAV để nhúng. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Tạo một khung audio mới với tệp WAV được nhúng và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. Audio nhúng được thêm vào bộ sưu tập Presentation.Audios.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn khung audio. |
| x | float | Tọa độ x của khung audio mới, tính bằng điểm. |
| y | float | Tọa độ y của khung audio mới, tính bằng điểm. |
| width | float | Độ rộng của khung audio mới, tính bằng điểm. |
| height | float | Độ cao của khung audio mới, tính bằng điểm. |
| audio_stream | java.io.InputStream | Luồng đầu vào chứa dữ liệu audio WAV để nhúng. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Tạo một khung audio mới và thêm vào cuối bộ sưu tập shape bằng một đối tượng audio hiện có trong danh sách Presentation.Audios.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của khung audio mới, tính bằng điểm. |
| y | float | Tọa độ y của khung audio mới, tính bằng điểm. |
| width | float | Độ rộng của khung audio mới, tính bằng điểm. |
| height | float | Độ cao của khung audio mới, tính bằng điểm. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Một thực thể [IAudio](../../com.aspose.slides/iaudio) từ bộ sưu tập Presentation.Audios. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Tạo một khung audio mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định bằng một đối tượng audio hiện có trong danh sách Presentation.Audios.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn khung audio. |
| x | float | Tọa độ x của khung audio mới, tính bằng điểm. |
| y | float | Tọa độ y của khung audio mới, tính bằng điểm. |
| width | float | Độ rộng của khung audio mới, tính bằng điểm. |
| height | float | Độ cao của khung audio mới, tính bằng điểm. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Một thực thể [IAudio](../../com.aspose.slides/iaudio) từ bộ sưu tập Presentation.Audios để nhúng. |

**Trả về:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) mới tạo.

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Trả về chỉ mục dựa trên 0 của lần xuất hiện đầu tiên của shape đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape cần tìm trong bộ sưu tập. |

**Trả về:**
int - Chỉ mục dựa trên 0 của lần xuất hiện đầu tiên của shape trong bộ sưu tập shape nếu tìm thấy; nếu không, \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Tạo và trả về một mảng chứa tất cả các shape.

**Trả về:**
com.aspose.slides.IShape[] - Mảng các đối tượng [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Tạo và trả về một mảng chứa tất cả các shape trong phạm vi đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| startIndex | int | Chỉ mục của shape đầu tiên cần trả về. |
| count | int | Số shape cần trả về. |

**Trả về:**
com.aspose.slides.IShape[] - Mảng các đối tượng [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Di chuyển shape đã chỉ định tới vị trí mới trong bộ sưu tập shape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi shape sẽ được đặt. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) cần di chuyển trong bộ sưu tập. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Di chuyển các shape đã chỉ định trong bộ sưu tập shape, bắt đầu ở chỉ mục đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi shape đầu tiên sẽ được đặt; các shape tiếp theo sẽ theo thứ tự đã cung cấp. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Một hoặc nhiều thực thể [IShape](../../com.aspose.slides/ishape) cần di chuyển trong bộ sưu tập. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Tạo một auto shape mới với định dạng mặc định và thêm vào cuối bộ sưu tập shape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của auto shape sẽ thêm. |
| x | float | Tọa độ x của khung shape, tính bằng điểm. |
| y | float | Tọa độ y của khung shape, tính bằng điểm. |
| width | float | Độ rộng của khung shape, tính bằng điểm. |
| height | float | Độ cao của khung shape, tính bằng điểm. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới tạo.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một auto shape mới và thêm vào cuối bộ sưu tập shape, tùy chọn khởi tạo với định dạng mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của auto shape sẽ thêm. |
| x | float | Tọa độ x của khung shape, tính bằng điểm. |
| y | float | Tọa độ y của khung shape, tính bằng điểm. |
| width | float | Độ rộng của khung shape, tính bằng điểm. |
| height | float | Độ cao của khung shape, tính bằng điểm. |
| createFromTemplate | boolean | `true` để áp dụng kiểu mẫu mặc định (kiểu đơn giản, văn bản căn giữa, tên không trống) cho shape mới; `false` để tạo shape với tất cả thuộc tính mặc định. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới tạo.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Tạo một auto shape hình chữ nhật mới để chứa nội dung toán học và thêm vào cuối bộ sưu tập shape.

--------------------

> ```
> Ví dụ sau đây cho thấy cách thêm Phương trình Toán học vào PowerPoint Presentation.
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
| x | float | Tọa độ x của khung shape, tính bằng điểm. |
| y | float | Tọa độ y của khung shape, tính bằng điểm. |
| width | float | Độ rộng của khung shape, tính bằng điểm. |
| height | float | Độ cao của khung shape, tính bằng điểm. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới tạo.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Tạo một auto shape mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định, áp dụng định dạng mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn auto shape mới. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của auto shape sẽ chèn. |
| x | float | Tọa độ x của khung shape, tính bằng điểm. |
| y | float | Tọa độ y của khung shape, tính bằng điểm. |
| width | float | Độ rộng của khung shape, tính bằng điểm. |
| height | float | Độ cao của khung shape, tính bằng điểm. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới tạo.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một auto shape mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định, tùy chọn khởi tạo với kiểu mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn auto shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của auto shape sẽ chèn. |
| x | float | Tọa độ x của khung shape, tính bằng điểm. |
| y | float | Tọa độ y của khung shape, tính bằng điểm. |
| width | float | Độ rộng của khung shape, tính bằng điểm. |
| height | float | Độ cao của khung shape, tính bằng điểm. |
| createFromTemplate | boolean | `true` để áp dụng kiểu mẫu mặc định (bao gồm tên không trống, kiểu đơn giản, văn bản căn giữa); `false` để tạo shape với tất cả thuộc tính mặc định. |

**Trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) mới tạo.

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Tạo một group shape trống mới và thêm vào cuối bộ sưu tập shape. Khung của group sẽ tự động điều chỉnh để phù hợp với bất kỳ shape nào được thêm vào.

--------------------

> ```
> The following example shows how to add a group shape to a slide of PowerPoint Presentation.
>  
>  // Tạo một thể hiện của lớp Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Lấy slide đầu tiên
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Truy cập bộ sưu tập các shape của slide
>      IShapeCollection slideShapes = sld.getShapes();
>      // Thêm một group shape vào slide
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Thêm các shape bên trong group shape đã thêm
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Thêm khung cho group shape
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Ghi tệp PPTX ra đĩa
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) mới tạo.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Tạo một group shape mới, chuyển đổi SVG image đã chỉ định thành các shape riêng lẻ, và thêm group kết quả vào cuối bộ sưu tập shape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) chứa nội dung vector để chuyển thành shape. |
| x | float | Tọa độ x của khung group, tính bằng điểm. |
| y | float | Tọa độ y của khung group, tính bằng điểm. |
| width | float | Độ rộng của khung group, tính bằng điểm. |
| height | float | Độ cao của khung group, tính bằng điểm. |

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) mới tạo.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Tạo một group shape trống mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. Khung của group sẽ tự động điều chỉnh để phù hợp với bất kỳ shape nào được thêm vào.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn group shape. |

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) mới tạo.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Tạo một connector shape mới với kiểu mẫu mặc định và thêm vào cuối bộ sưu tập shape.

--------------------

> ```
> The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint Presentation.
>  
>  // Tạo một thể hiện của lớp Presentation đại diện cho tệp PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Truy cập bộ sưu tập shape cho một slide cụ thể
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Thêm một autoshape Hình elip
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Thêm một autoshape Hình chữ nhật
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Thêm một shape connector vào bộ sưu tập shape của slide
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Kết nối các shape bằng connector
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Gọi reroute để đặt đường ngắn nhất tự động giữa các shape
>      connector.reroute();
>      // Lưu bản trình chiếu
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của connector shape sẽ thêm. |
| x | float | Tọa độ x của khung connector, tính bằng điểm. |
| y | float | Tọa độ y của khung connector, tính bằng điểm. |
| width | float | Độ rộng của khung connector, tính bằng điểm. |
| height | float | Độ cao của khung connector, tính bằng điểm. |

**Trả về:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) mới tạo.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một connector shape mới và thêm vào cuối bộ sưu tập shape, tùy chọn áp dụng kiểu mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của connector shape sẽ tạo. |
| x | float | Tọa độ x của khung connector, tính bằng điểm. |
| y | float | Tọa độ y của khung connector, tính bằng điểm. |
| width | float | Độ rộng của khung connector, tính bằng điểm. |
| height | float | Độ cao của khung connector, tính bằng điểm. |
| createFromTemplate | boolean | `true` để áp dụng kiểu mẫu mặc định (tên không trống, kiểu đơn giản); `false` để tạo connector với các thuộc tính mặc định. |

**Trả về:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) mới tạo.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Tạo một connector shape mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định, áp dụng kiểu mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn connector shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của connector shape sẽ chèn. |
| x | float | Tọa độ x của khung connector, tính bằng điểm. |
| y | float | Tọa độ y của khung connector, tính bằng điểm. |
| width | float | Độ rộng của khung connector, tính bằng điểm. |
| height | float | Độ cao của khung connector, tính bằng điểm. |

**Trả về:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) mới tạo.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tạo một connector shape mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định, tùy chọn áp dụng kiểu mẫu mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn connector shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) của connector shape sẽ chèn. |
| x | float | Tọa độ x của khung connector, tính bằng điểm. |
| y | float | Tọa độ y của khung connector, tính bằng điểm. |
| width | float | Độ rộng của khung connector, tính bằng điểm. |
| height | float | Độ cao của khung connector, tính bằng điểm. |
| createFromTemplate | boolean | `true` để áp dụng kiểu mẫu mặc định (tên không trống, kiểu đơn giản); `false` để tạo connector với các thuộc tính mặc định. |

**Trả về:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) mới tạo.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Tạo một picture frame mới chứa hình ảnh đã chỉ định và thêm vào cuối bộ sưu tập shape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeType | int | Xác định loại shape được chứa trong [ShapeType](../../com.aspose.slides/shapetype), ngoại trừ mọi loại đường thẳng: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Tọa độ x của picture frame, tính bằng điểm. |
| y | float | Tọa độ y của picture frame, tính bằng điểm. |
| width | float | Độ rộng của picture frame, tính bằng điểm. |
| height | float | Độ cao của picture frame, tính bằng điểm. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) sẽ hiển thị trong picture frame. |

**Trả về:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) mới tạo.

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Tạo một picture frame mới chứa hình ảnh đã chỉ định và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn picture frame. |
| shapeType | int | Xác định loại shape được chứa trong [ShapeType](../../com.aspose.slides/shapetype), ngoại trừ mọi loại đường thẳng: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Tọa độ x của picture frame, tính bằng điểm. |
| y | float | Tọa độ y của picture frame, tính bằng điểm. |
| width | float | Độ rộng của picture frame, tính bằng điểm. |
| height | float | Độ cao của picture frame, tính bằng điểm. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) sẽ hiển thị trong picture frame. |

**Trả về:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) mới tạo.

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Tạo một table mới và thêm vào cuối bộ sưu tập shape.

--------------------

> ```
> The following examples shows how to add table in PowerPoint Presentation.
>  
>  // Tạo một thể hiện của lớp Presentation đại diện cho tệp PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Truy cập slide đầu tiên
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Định nghĩa các cột với độ rộng và các hàng với độ cao
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Thêm shape bảng vào slide
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Đặt định dạng viền cho từng ô
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


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ x của table, tính bằng điểm. |
| y | float | Tọa độ y của table, tính bằng điểm. |
| columnWidths | double[] | Mảng các giá trị double đại diện cho độ rộng của các cột trong table, tính bằng điểm. |
| rowHeights | double[] | Mảng các giá trị double đại diện cho độ cao của các hàng trong table, tính bằng điểm. |

**Trả về:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) mới tạo.

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Tạo một table mới và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn table. |
| x | float | Tọa độ x của table, tính bằng điểm. |
| y | float | Tọa độ y của table, tính bằng điểm. |
| columnWidths | double[] | Mảng các giá trị double đại diện cho độ rộng của các cột trong table, tính bằng điểm. |
| rowHeights | double[] | Mảng các giá trị double đại diện cho độ cao của các hàng trong table, tính bằng điểm. |

**Trả về:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) mới tạo.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa shape ở chỉ mục đã chỉ định khỏi bộ sưu tập shape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 của shape cần xóa. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Xóa lần xuất hiện đầu tiên của shape đã chỉ định khỏi bộ sưu tập shape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) cần xóa. |

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

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - IGenericEnumerator có thể dùng để duyệt qua bộ sưu tập.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - java.util.Iterator cho toàn bộ bộ sưu tập.

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Lấy đối tượng parent group shape cho bộ sưu tập shape. Chỉ đọc [IGroupShape](../../com.aspose.slides/igroupshape).

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Tạo một bản sao của shape đã chỉ định và thêm vào cuối bộ sưu tập shape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape cần sao chép. |
| x | float | Tọa độ x của khung shape mới, tính bằng điểm. |
| y | float | Tọa độ y của khung shape mới, tính bằng điểm. |
| width | float | Độ rộng của khung shape mới, tính bằng điểm. |
| height | float | Độ cao của khung shape mới, tính bằng điểm. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới tạo.

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Tạo một bản sao của shape đã chỉ định và thêm vào cuối bộ sưu tập shape. Shape mới giữ nguyên độ rộng và chiều cao của sourceShape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Shape cần sao chép. |
| x | float | Tọa độ x của khung shape mới, tính bằng điểm. |
| y | float | Tọa độ y của khung shape mới, tính bằng điểm. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới tạo.

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Tạo một bản sao của shape đã chỉ định và thêm vào cuối bộ sưu tập shape. Shape đã sao chép giữ nguyên vị trí và kích thước gốc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) cần sao chép. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới tạo.

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Tạo một bản sao của shape đã chỉ định và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn shape đã sao chép. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) cần sao chép. |
| x | float | Tọa độ x của khung shape đã sao chép, tính bằng điểm. |
| y | float | Tọa độ y của khung shape đã sao chép, tính bằng điểm. |
| width | float | Độ rộng của khung shape đã sao chép, tính bằng điểm. |
| height | float | Độ cao của khung shape đã sao chép, tính bằng điểm. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới tạo.

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Tạo một bản sao của shape đã chỉ định và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. Shape mới giữ nguyên độ rộng và chiều cao của sourceShape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn shape đã sao chép. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) cần sao chép. |
| x | float | Tọa độ x của khung shape đã sao chép, tính bằng điểm. |
| y | float | Tọa độ y của khung shape đã sao chép, tính bằng điểm. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới tạo.

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Tạo một bản sao của shape đã chỉ định và chèn vào bộ sưu tập shape ở chỉ mục đã chỉ định. Shape đã sao chép giữ nguyên vị trí và kích thước gốc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 nơi sẽ chèn shape đã sao chép. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) cần sao chép. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) mới tạo.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ bộ sưu tập vào mảng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về một giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. Chỉ đọc `boolean`.

**Trả về:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một synchronization root. Chỉ đọc `Object`.

**Trả về:**
java.lang.Object