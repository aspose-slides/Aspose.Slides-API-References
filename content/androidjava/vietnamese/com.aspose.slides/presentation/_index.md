---
title: Presentation
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho một bản trình chiếu Microsoft PowerPoint.
type: docs
url: /vi/com.aspose.slides/presentation/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Đại diện cho một bản trình chiếu Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Khởi tạo đối tượng Presentation đại diện cho một tệp trình chiếu
>  Presentation pres = new Presentation();
>  try {
>      // Lấy slide đầu tiên
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Thêm một autoshape loại đường thẳng
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Lưu tệp trình chiếu.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Tải bất kỳ tệp nào được hỗ trợ trong Presentation, ví dụ ppt, pptx, odp, v.v.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Lưu tệp trình chiếu.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Các hàm khởi tạo

| Constructor | Mô tả |
| --- | --- |
| [Presentation()](#Presentation--) | Hàm khởi tạo này tạo bản trình chiếu mới từ đầu. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Hàm khởi tạo này tạo bản trình chiếu mới từ đầu. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Hàm khởi tạo này là cơ chế chính để đọc một Presentation hiện có. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Hàm khởi tạo này là cơ chế chính để đọc một Presentation hiện có. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Hàm khởi tạo này lấy đường dẫn tệp nguồn mà từ đó nội dung của Presentation được đọc. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Hàm khởi tạo này lấy đường dẫn tệp nguồn mà từ đó nội dung của Presentation được đọc. |

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Trả về hoặc đặt ngày và giờ sẽ thay thế nội dung của các trường datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Trả về hoặc đặt ngày và giờ sẽ thay thế nội dung của các trường datetime. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter thực tế. |
| [getProtectionManager()](#getProtectionManager--) | Lấy trình quản lý quyền cho bản trình chiếu này. |
| [getSlides()](#getSlides--) | Trả về danh sách tất cả các slide được định nghĩa trong bản trình chiếu. |
| [getSections()](#getSections--) | Trả về danh sách tất cả các phần slide được định nghĩa trong bản trình chiếu. |
| [getSlideSize()](#getSlideSize--) | Trả về đối tượng kích thước slide. |
| [getNotesSize()](#getNotesSize--) | Trả về đối tượng kích thước slide ghi chú. |
| [getLayoutSlides()](#getLayoutSlides--) | Trả về danh sách tất cả các layout slide được định nghĩa trong bản trình chiếu. |
| [getMasters()](#getMasters--) | Trả về danh sách tất cả các master slide được định nghĩa trong bản trình chiếu. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Trả về trình quản lý notes master. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Trả về trình quản lý handout master. |
| [getFontsManager()](#getFontsManager--) | Trả về trình quản lý phông chữ. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Trả về kiểu văn bản mặc định cho các shape. |
| [getCommentAuthors()](#getCommentAuthors--) | Trả về bộ sưu tập các tác giả bình luận. |
| [getDocumentProperties()](#getDocumentProperties--) | Trả về đối tượng DocumentProperties chứa các thuộc tính tài liệu tiêu chuẩn và tùy chỉnh. |
| [getImages()](#getImages--) | Trả về bộ sưu tập tất cả các hình ảnh trong bản trình chiếu. |
| [getAudios()](#getAudios--) | Trả về bộ sưu tập tất cả các tệp âm thanh nhúng trong bản trình chiếu. |
| [getVideos()](#getVideos--) | Trả về bộ sưu tập tất cả các tệp video nhúng trong bản trình chiếu. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Trả về cài đặt trình chiếu cho bản trình chiếu. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Trả về bộ sưu tập các chữ ký được dùng để ký bản trình chiếu. |
| [getCustomData()](#getCustomData--) | Trả về dữ liệu tùy chỉnh của bản trình chiếu. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Trả về tất cả các phần dữ liệu tùy chỉnh trong bản trình chiếu. |
| [getVbaProject()](#getVbaProject--) | Lấy hoặc đặt dự án VBA với macro của bản trình chiếu. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Lấy hoặc đặt dự án VBA với macro của bản trình chiếu. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Cung cấp truy cập dễ dàng đến tất cả các siêu liên kết có trong tất cả các slide của bản trình chiếu (không bao gồm master, layout, notes slide). |
| [getViewProperties()](#getViewProperties--) | Lấy các thuộc tính chế độ xem toàn bộ bản trình chiếu. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Đại diện cho số slide đầu tiên trong bản trình chiếu |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Đại diện cho số slide đầu tiên trong bản trình chiếu |
| [getSensitivityLabels()](#getSensitivityLabels--) | Trả về bộ sưu tập các nhãn nhạy cảm được áp dụng cho tài liệu bản trình chiếu. |
| [getSlideById(long id)](#getSlideById-long-) | Trả về một Slide, MasterSlide hoặc LayoutSlide theo Id. |
| [getSourceFormat()](#getSourceFormat--) | Trả về thông tin về định dạng mà bản trình chiếu được tải. |
| [getMasterTheme()](#getMasterTheme--) | Trả về chủ đề master. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Lưu tất cả các slide của một bản trình chiếu vào tệp với định dạng được chỉ định. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Lưu tất cả các slide của một bản trình chiếu vào stream với định dạng được chỉ định. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Lưu tất cả các slide của một bản trình chiếu vào tệp với định dạng được chỉ định và các tùy chọn bổ sung. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Lưu tất cả các slide của một bản trình chiếu vào stream với định dạng được chỉ định và các tùy chọn bổ sung. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Lưu tất cả các slide của một bản trình chiếu vào một tập hợp các tệp đại diện cho markup XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Trả về các đối tượng Image cho tất cả các slide của một bản trình chiếu. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Trả về các đối tượng Thumbnail Image cho các slide được chỉ định của một bản trình chiếu. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Trả về các đối tượng Thumbnail Image cho tất cả các slide của một bản trình chiếu với tỷ lệ tùy chỉnh. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Trả về các đối tượng Thumbnail Image cho các slide được chỉ định của một bản trình chiếu với tỷ lệ tùy chỉnh. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Trả về các đối tượng Thumbnail Image cho tất cả các slide của một bản trình chiếu với kích thước đã chỉ định. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Trả về các đối tượng Thumbnail Image cho các slide được chỉ định của một bản trình chiếu với kích thước đã chỉ định. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Lưu các slide được chỉ định của một bản trình chiếu vào tệp với định dạng được chỉ định và giữ số trang. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Lưu các slide được chỉ định của một bản trình chiếu vào tệp với định dạng được chỉ định và giữ số trang. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Lưu các slide được chỉ định của một bản trình chiếu vào stream trong định dạng được chỉ định và giữ số trang. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Lưu các slide được chỉ định của một bản trình chiếu vào stream trong định dạng được chỉ định và giữ số trang. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Nối các run có cùng định dạng trong tất cả các đoạn văn trong tất cả các shape chấp nhận được trên tất cả các slide. |
| [dispose()](#dispose--) | Giải phóng tất cả các tài nguyên được đối tượng Presentation này sử dụng. |
| [getPresentation()](#getPresentation--) | Trả về bản trình chiếu cha của một đoạn văn bản. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Tô sáng tất cả các khớp của văn bản mẫu với màu được chỉ định. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Tô sáng tất cả các khớp của văn bản mẫu với màu được chỉ định. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Tô sáng tất cả các khớp của biểu thức chính quy với màu được chỉ định. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Thay thế tất cả các xuất hiện của văn bản đã chỉ định bằng một văn bản khác đã chỉ định. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Thay thế tất cả các khớp của biểu thức chính quy bằng chuỗi được chỉ định. |

### Presentation() {#Presentation--}
```
public Presentation()
```

Hàm khởi tạo này tạo bản trình chiếu mới từ đầu. Bản trình chiếu được tạo có một slide trống.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Hàm khởi tạo này tạo bản trình chiếu mới từ đầu. Bản trình chiếu được tạo có một slide trống.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Các tùy chọn tải bổ sung. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Hàm khởi tạo này là cơ chế chính để đọc một Presentation hiện có.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng đầu vào. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Hàm khởi tạo này là cơ chế chính để đọc một Presentation hiện có.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng đầu vào. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Các tùy chọn tải bổ sung. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Hàm khởi tạo này lấy đường dẫn tệp nguồn mà từ đó nội dung của Presentation được đọc.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| file | java.lang.String | Tệp đầu vào. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Hàm khởi tạo này lấy đường dẫn tệp nguồn mà từ đó nội dung của Presentation được đọc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| file | java.lang.String | Tệp đầu vào. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Các tùy chọn tải bổ sung. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Trả về hoặc đặt ngày và giờ sẽ thay thế nội dung của các trường datetime. Thời gian tạo đối tượng Presentation này theo mặc định. Đọc/ghi java.util.Date.

**Trả về:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Trả về hoặc đặt ngày và giờ sẽ thay thế nội dung của các trường datetime. Thời gian tạo đối tượng Presentation này theo mặc định. Đọc/ghi java.util.Date.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Trả về trình quản lý HeaderFooter thực tế. Chỉ đọc [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Thuộc tính IsFooterVisible được dùng để chỉ ra rằng placeholder footer của slide không tồn tại.
>      {
>          headerFooterManager.setFooterVisibility(true); // Phương thức SetFooterVisibility được dùng để làm cho placeholder footer của slide hiển thị.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Thuộc tính IsSlideNumberVisible được dùng để chỉ ra rằng placeholder số trang của slide không tồn tại.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Phương thức SetSlideNumberVisibility được dùng để làm cho placeholder số trang của slide hiển thị.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Thuộc tính IsDateTimeVisible được dùng để chỉ ra rằng placeholder ngày-giờ của slide không tồn tại.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Phương thức SetFooterVisibility được dùng để làm cho placeholder ngày-giờ của slide hiển thị.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Phương thức SetFooterText được dùng để đặt văn bản cho placeholder footer của slide.
>      headerFooterManager.setDateTimeText("Date and time text"); // Phương thức SetDateTimeText được dùng để đặt văn bản cho placeholder ngày-giờ của slide.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Phương thức SetFooterAndChildFootersVisibility được dùng để làm cho master slide và tất cả các placeholder footer con hiển thị.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Phương thức SetSlideNumberAndChildSlideNumbersVisibility được dùng để làm cho master slide và tất cả các placeholder số trang con hiển thị.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Phương thức SetDateTimeAndChildDateTimesVisibility được dùng để làm cho master slide và tất cả các placeholder ngày-giờ con hiển thị.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Phương thức SetFooterAndChildFootersText được dùng để đặt văn bản cho master slide và tất cả các placeholder footer con.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Phương thức SetDateTimeAndChildDateTimesText được dùng để đặt văn bản cho master slide và tất cả các placeholder ngày-giờ con.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Lấy trình quản lý quyền cho bản trình chiếu này. Chỉ đọc [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Trả về:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Trả về danh sách tất cả các slide được định nghĩa trong bản trình chiếu. Chỉ đọc [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Khởi tạo lớp Presentation đại diện cho tệp trình chiếu
>  Presentation pres = new Presentation();
>  try
>  {
>      // Đặt màu nền của ISlide đầu tiên thành màu Xanh dương
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // Khởi tạo lớp Presentation đại diện cho tệp trình chiếu
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Đặt nền bằng hình ảnh
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Đặt hình ảnh
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // Thêm hình ảnh vào bộ sưu tập hình ảnh của bản trình chiếu
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      // Ghi bản trình chiếu ra đĩa
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Khởi tạo lớp Presentation để tải tệp trình chiếu nguồn
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Áp dụng hiệu ứng chuyển tiếp kiểu vòng tròn cho slide 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Áp dụng hiệu ứng chuyển tiếp kiểu lược cho slide 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Ghi bản trình chiếu ra đĩa
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Khởi tạo lớp Presentation đại diện cho một tệp trình chiếu
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Áp dụng hiệu ứng chuyển tiếp kiểu vòng tròn cho slide 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Đặt thời gian chuyển tiếp là 3 giây
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Áp dụng hiệu ứng chuyển tiếp kiểu lược cho slide 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Đặt thời gian chuyển tiếp là 5 giây
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Áp dụng hiệu ứng chuyển tiếp kiểu thu phóng cho slide 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Đặt thời gian chuyển tiếp là 7 giây
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Ghi bản trình chiếu ra đĩa
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Trả về danh sách tất cả các phần slide được định nghĩa trong bản trình chiếu. Chỉ đọc [ISectionCollection](../../com.aspose.slides/isectioncollection).

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1 sẽ kết thúc ở newSlide2 và sau đó section2 sẽ bắt đầu
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Trả về đối tượng kích thước slide. Chỉ đọc [ISlideSize](../../com.aspose.slides/islidesize).

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // Khởi tạo đối tượng Presentation đại diện cho một tệp trình chiếu
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Đặt kích thước slide của bản trình chiếu đã tạo bằng kích thước của nguồn
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Phương thức SetSize được dùng để đặt kích thước slide với việc thu phóng nội dung để đảm bảo vừa
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Phương thức SetSize được dùng để đặt kích thước slide với việc tối đa hoá kích thước nội dung
>          // Lưu Presentation ra đĩa
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // Kích thước giấy A4
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Trả về đối tượng kích thước slide ghi chú. Chỉ đọc [INotesSize](../../com.aspose.slides/inotessize).

**Trả về:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Trả về danh sách tất cả các layout slide được định nghĩa trong bản trình chiếu. Chỉ đọc [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Bạn có thể truy cập API thay thế để thêm/chèn/xóa/nhân bản layout slide bằng cách sử dụng thuộc tính IMasterSlide.LayoutSlides.

**Trả về:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Trả về danh sách tất cả các master slide được định nghĩa trong bản trình chiếu. Chỉ đọc [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Khởi tạo lớp Presentation đại diện cho tệp trình chiếu
>  Presentation pres = new Presentation();
>  try
>  {
>      // Đặt màu nền của Master ISlide thành màu Xanh rừng
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Ghi bản trình chiếu ra đĩa
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Khởi tạo lớp Presentation đại diện cho tệp trình chiếu
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Cố gắng tìm bằng kiểu layout slide
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // Trường hợp khi một bản trình chiếu không chứa một số loại layout.
>          // Tệp trình chiếu chỉ chứa các loại layout Trống và Tùy chỉnh.
>          // Tuy nhiên các layout slide kiểu Tùy chỉnh có tên slide khác nhau,
>          // chẳng hạn "Title", "Title and Content", v.v. Và có thể sử dụng chúng
>          // làm tên để lựa chọn layout slide.
>          // Ngoài ra cũng có thể dùng tập hợp các kiểu shape placeholder. Ví dụ,
>          // Slide tiêu đề chỉ nên có kiểu placeholder Title, v.v.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // Thêm slide trống với layout slide đã thêm
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Lưu bản trình chiếu
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Trả về:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Trả về trình quản lý notes master. Chỉ đọc [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Trả về:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Trả về trình quản lý handout master. Chỉ đọc [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Trả về:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Trả về trình quản lý phông chữ. Chỉ đọc [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Tải bản trình chiếu
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Tải phông chữ nguồn để thay thế
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Lưu bản trình chiếu
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Trả về kiểu văn bản mặc định cho các shape. Chỉ đọc [ITextStyle](../../com.aspose.slides/itextstyle).

**Trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Trả về bộ sưu tập các tác giả bình luận. Chỉ đọc [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Trả về:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Trả về đối tượng DocumentProperties chứa các thuộc tính tài liệu tiêu chuẩn và tùy chỉnh. Chỉ đọc [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Trả về:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Trả về bộ sưu tập tất cả các hình ảnh trong bản trình chiếu. Chỉ đọc [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // tạo một bản trình chiếu mới mà hình ảnh sẽ được thêm vào.
>  Presentation pres = new Presentation();
>  try
>  {
>      // giả sử chúng ta có tệp ảnh lớn muốn đưa vào bản trình chiếu
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Hãy thêm ảnh vào bản trình chiếu - chúng ta chọn hành vi KeepLocked vì chúng ta
>          // KHÔNG có ý định truy cập tệp "largeImage.png" file.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Lưu bản trình chiếu. Khi một bản trình chiếu lớn được xuất, mức tiêu thụ bộ nhớ
>          // vẫn thấp trong suốt vòng đời của đối tượng pres
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // Thêm hình ảnh vào bản trình chiếu
>          IPPImage image = pres.getImages().addImage(fos);
>          // Tạo khung ảnh trên slide 1 dựa trên hình ảnh đã thêm trước đó
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

Trả về bộ sưu tập tất cả các tệp âm thanh nhúng trong bản trình chiếu. Chỉ đọc [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

Trả về bộ sưu tập tất cả các tệp video nhúng trong bản trình chiếu. Chỉ đọc [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

Trả về cài đặt trình chiếu cho bản trình chiếu.

**Trả về:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)

### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

Trả về bộ sưu tập các chữ ký được dùng để ký bản trình chiếu. Chỉ đọc [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Trả về dữ liệu tùy chỉnh của bản trình chiếu. Chỉ đọc [ICustomData](../../com.aspose.slides/icustomdata).

**Trả về:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

Trả về tất cả các phần dữ liệu tùy chỉnh trong bản trình chiếu. Chỉ đọc ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Duyệt qua tất cả các phần XML tùy chỉnh
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
com.aspose.slides.ICustomXmlPart[]

### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

Lấy hoặc đặt dự án VBA với macro của bản trình chiếu. Đọc/ghi [IVbaProject](../../com.aspose.slides/ivbaproject).

**Trả về:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

Lấy hoặc đặt dự án VBA với macro của bản trình chiếu. Đọc/ghi [IVbaProject](../../com.aspose.slides/ivbaproject).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Cung cấp truy cập dễ dàng đến tất cả các siêu liên kết có trong tất cả các slide của bản trình chiếu (không bao gồm master, layout, notes slide). Chỉ đọc [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Trả về:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

Lấy các thuộc tính chế độ xem toàn bộ bản trình chiếu. Chỉ đọc [IViewProperties](../../com.aspose.slides/iviewproperties).

**Trả về:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

Đại diện cho số slide đầu tiên trong bản trình chiếu

**Trả về:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public      //       -       -        public final void setFirstSlideNumber(int value)
```



Đại diện cho số slide đầu tiên trong bản trình chiếu

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

Trả về bộ sưu tập các nhãn nhạy cảm được áp dụng cho tài liệu bản trình chiếu. Chỉ đọc [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // In ra các nhãn đã áp dụng
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Thêm nhãn mới
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Lấy Id nhãn nhạy cảm từ chính sách
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Lấy định danh site Azure AD từ chính sách
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

Trả về một Slide, MasterSlide hoặc LayoutSlide theo Id.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| id | long | Id của một slide. |

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Trả về thông tin về định dạng mà bản trình chiếu được tải. Chỉ đọc [SourceFormat](../../com.aspose.slides/sourceformat).

**Trả về:**
int

### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

Trả về chủ đề master. Chỉ đọc [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Khởi tạo đối tượng presentation đại diện cho một tệp trình chiếu
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

Lưu tất cả các slide của một bản trình chiếu vào tệp với định dạng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | java.lang.String | Đường dẫn tới tệp được tạo. |
| format | int | Định dạng của dữ liệu xuất. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

Lưu tất cả các slide của một bản trình chiếu vào stream trong định dạng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đầu ra. |
| format | int | Định dạng của dữ liệu xuất. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

Lưu tất cả các slide của một bản trình chiếu vào tệp với định dạng được chỉ định và các tùy chọn bổ sung.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | java.lang.String | Đường dẫn tới tệp được tạo. |
| format | int | Định dạng của dữ liệu xuất. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Các tùy chọn định dạng bổ sung. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

Lưu tất cả các slide của một bản trình chiếu vào stream trong định dạng được chỉ định và các tùy chọn bổ sung.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đầu ra. |
| format | int | Định dạng của dữ liệu xuất. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Các tùy chọn định dạng bổ sung. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

Lưu tất cả các slide của một bản trình chiếu vào một tập hợp các tệp đại diện cho markup XAML.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Các tùy chọn định dạng XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

Trả về các đối tượng Image cho tất cả các slide của một bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tùy chọn Tiff. |

**Trả về:**
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

Trả về các đối tượng Thumbnail Image cho các slide được chỉ định của một bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tùy chọn Tiff. |
| slides | int[] | Mảng vị trí slide, bắt đầu từ 1. |

**Trả về:**
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Trả về các đối tượng Thumbnail Image cho tất cả các slide của một bản trình chiếu với tỷ lệ tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tùy chọn Tiff. |
| scaleX | float | Giá trị tỷ lệ theo trục x. |
| scaleY | float | Giá trị tỷ lệ theo trục y. |

**Trả về:**
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Trả về các đối tượng Thumbnail Image cho các slide được chỉ định của một bản trình chiếu với tỷ lệ tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tùy chọn Tiff. |
| slides | int[] | Mảng vị trí slide, bắt đầu từ 1. |
| scaleX | float | Giá trị tỷ lệ theo trục x. |
| scaleY | float | Giá trị tỷ lệ theo trục y. |

**Trả về:**
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Trả về các đối tượng Thumbnail Image cho tất cả các slide của một bản trình chiếu với kích thước đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tùy chọn Tiff. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Kích thước của ảnh cần tạo. |

**Trả về:**
com.aspose.slides.IImage[] - Image objects.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Trả về các đối tượng Thumbnail Image cho các slide được chỉ định của một bản trình chiếu với kích thước đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tùy chọn Tiff. |
| slides | int[] | Mảng vị trí slide, bắt đầu từ 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Kích thước của ảnh cần tạo. |

**Trả về:**
com.aspose.slides.IImage[] - Image objects.

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

Lưu các slide được chỉ định của một bản trình chiếu vào tệp với định dạng được chỉ định và giữ số trang.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | java.lang.String | Đường dẫn tới tệp được tạo. |
| slides | int[] | Mảng vị trí slide, bắt đầu từ 1. |
| format | int | Định dạng của dữ liệu xuất. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

Lưu các slide được chỉ định của một bản trình chiếu vào tệp với định dạng được chỉ định và giữ số trang.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | java.lang.String | Đường dẫn tới tệp được tạo. |
| slides | int[] | Mảng vị trí slide, bắt đầu từ 1. |
| format | int | Định dạng của dữ liệu xuất. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Các tùy chọn định dạng bổ sung. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

Lưu các slide được chỉ định của một bản trình chiếu vào stream trong định dạng được chỉ định và giữ số trang.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đầu ra. |
| slides | int[] | Mảng vị trí slide, bắt đầu từ 1. |
| format | int | Định dạng của dữ liệu xuất. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Lưu các slide được chỉ định của một bản trình chiếu vào stream trong định dạng được chỉ định và giữ số trang.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(scaleX, scaleY).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      com.aspose.slides.android.Size size = new com.aspose.slides.android.Size(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(size).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đầu ra. |
| slides | int[] | Mảng vị trí slide, bắt đầu từ 1. |
| format | int | Định dạng của dữ liệu xuất. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Các tùy chọn định dạng bổ sung. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Nối các run có cùng định dạng trong tất cả các đoạn văn trong tất cả các shape chấp nhận được trên tất cả các slide.

### dispose() {#dispose--}
```
public final void dispose()
```

Giải phóng tất cả các tài nguyên được đối tượng Presentation này sử dụng.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình chiếu cha của một đoạn văn bản. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Tô sáng tất cả các khớp của văn bản mẫu với màu được chỉ định.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // tô sáng tất cả các lần xuất hiện riêng lẻ của 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần tô sáng. |
| highlightColor | java.lang.Integer | Màu dùng để tô sáng văn bản. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Tô sáng tất cả các khớp của văn bản mẫu với màu được chỉ định.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // tô sáng tất cả các lần xuất hiện riêng lẻ của 'the'
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần tô sáng. |
| highlightColor | java.lang.Integer | Màu dùng để tô sáng văn bản. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Các tùy chọn tìm kiếm văn bản [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Tô sáng tất cả các khớp của biểu thức chính quy với màu được chỉ định.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // tô sáng tất cả các từ có độ dài 10 ký tự trở lên
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Biểu thức chính quy java.util.regex.Pattern để lấy các chuỗi cần tô sáng. |
| highlightColor | java.lang.Integer | Màu dùng để tô sáng văn bản. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Thay thế tất cả các xuất hiện của văn bản đã chỉ định bằng một văn bản khác đã chỉ định.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Thay thế tất cả các lần xuất hiện riêng lẻ của 'the' bằng '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| oldText | java.lang.String | Chuỗi cần thay thế. |
| newText | java.lang.String | Chuỗi thay thế cho tất cả các xuất hiện của oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Các tùy chọn tìm kiếm văn bản [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Thay thế tất cả các khớp của biểu thức chính quy bằng chuỗi được chỉ định.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Thay thế tất cả các từ có độ dài 10 ký tự trở lên bằng '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Biểu thức chính quy java.util.regex.Pattern để lấy các chuỗi cần thay thế. |
| newText | java.lang.String | Chuỗi thay thế cho tất cả các xuất hiện của các chuỗi cần thay thế. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |