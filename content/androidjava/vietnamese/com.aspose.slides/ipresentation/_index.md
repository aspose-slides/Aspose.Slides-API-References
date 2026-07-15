---
title: IPresentation
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Tài liệu trình chiếu
type: docs
url: /vi/com.aspose.slides/ipresentation/
---
**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Presentation document
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Trả về hoặc đặt ngày và giờ sẽ thay thế nội dung của các trường datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Trả về hoặc đặt ngày và giờ sẽ thay thế nội dung của các trường datetime. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của bản trình chiếu. |
| [getProtectionManager()](#getProtectionManager--) | Lấy trình quản lý quyền cho bản trình chiếu này. |
| [getSlides()](#getSlides--) | Trả về danh sách tất cả các slide được định nghĩa trong bản trình chiếu. |
| [getSections()](#getSections--) | Trả về danh sách tất cả các phần slide được định nghĩa trong bản trình chiếu. |
| [getSlideSize()](#getSlideSize--) | Trả về đối tượng kích thước slide. |
| [getNotesSize()](#getNotesSize--) | Trả về đối tượng kích thước slide ghi chú. |
| [getLayoutSlides()](#getLayoutSlides--) | Trả về danh sách tất cả các slide bố cục được định nghĩa trong bản trình chiếu. |
| [getMasters()](#getMasters--) | Trả về danh sách tất cả các slide chủ được định nghĩa trong bản trình chiếu. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Trả về trình quản lý notes master. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Trả về trình quản lý handout master. |
| [getFontsManager()](#getFontsManager--) | Trả về trình quản lý phông chữ. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Trả về kiểu văn bản mặc định cho các hình dạng. |
| [getCommentAuthors()](#getCommentAuthors--) | Trả về bộ sưu tập các tác giả bình luận. |
| [getDocumentProperties()](#getDocumentProperties--) | Trả về đối tượng DocumentProperties chứa các thuộc tính tài liệu chuẩn và tùy chỉnh. |
| [getImages()](#getImages--) | Trả về bộ sưu tập tất cả hình ảnh trong bản trình chiếu. |
| [getAudios()](#getAudios--) | Trả về bộ sưu tập tất cả các tệp âm thanh nhúng trong bản trình chiếu. |
| [getVideos()](#getVideos--) | Trả về bộ sưu tập tất cả các tệp video nhúng trong bản trình chiếu. |
| [getCustomData()](#getCustomData--) | Trả về dữ liệu tùy chỉnh của bản trình chiếu. |
| [getVbaProject()](#getVbaProject--) | Lấy dự án VBA với macro của bản trình chiếu. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Lấy dự án VBA với macro của bản trình chiếu. |
| [getSourceFormat()](#getSourceFormat--) | Trả về thông tin về định dạng mà bản trình chiếu được tải. |
| [getMasterTheme()](#getMasterTheme--) | Trả về chủ đề master của bản trình chiếu. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Cung cấp truy cập dễ dàng tới tất cả siêu liên kết có trong các slide của bản trình chiếu (không bao gồm master, layout, slide ghi chú). |
| [getViewProperties()](#getViewProperties--) | Lấy các thuộc tính chế độ xem toàn cục của bản trình chiếu. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Biểu thị số slide đầu tiên trong bản trình chiếu. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Biểu thị số slide đầu tiên trong bản trình chiếu. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Trả về tất cả các phần dữ liệu tùy chỉnh trong bản trình chiếu. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Trả về bộ sưu tập các chữ ký được sử dụng để ký bản trình chiếu. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Trả về bộ sưu tập các nhãn độ nhạy được áp dụng cho tài liệu bản trình chiếu. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Lưu tất cả các slide của bản trình chiếu vào tệp với định dạng đã chỉ định. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Lưu tất cả các slide của bản trình chiếu vào dòng dữ liệu với định dạng đã chỉ định. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Lưu tất cả các slide của bản trình chiếu vào tệp với định dạng đã chỉ định và các tùy chọn bổ sung. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Lưu tất cả các slide của bản trình chiếu vào dòng dữ liệu với định dạng đã chỉ định và các tùy chọn bổ sung. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Lưu các slide đã chỉ định của bản trình chiếu vào tệp với định dạng đã chỉ định. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Lưu các slide đã chỉ định của bản trình chiếu vào tệp với định dạng đã chỉ định. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Lưu các slide đã chỉ định của bản trình chiếu vào dòng dữ liệu với định dạng đã chỉ định. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Lưu các slide đã chỉ định của bản trình chiếu vào dòng dữ liệu với định dạng đã chỉ định. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Lưu tất cả các slide của bản trình chiếu vào một tập hợp các tệp đại diện cho markup XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Trả về các đối tượng Thumbnail Image cho tất cả các slide của bản trình chiếu. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Trả về các đối tượng Thumbnail IImage cho các slide đã chỉ định của bản trình chiếu. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Trả về các đối tượng Thumbnail Image cho tất cả các slide của bản trình chiếu với tỷ lệ tùy chỉnh. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Trả về các đối tượng Thumbnail Image cho các slide đã chỉ định của bản trình chiếu với tỷ lệ tùy chỉnh. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Trả về các đối tượng Thumbnail Image cho tất cả các slide của bản trình chiếu với kích thước được chỉ định. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Trả về các đối tượng Thumbnail Image cho các slide đã chỉ định của bản trình chiếu với kích thước được chỉ định. |
| [getSlideById(long id)](#getSlideById-long-) | Trả về một Slide, MasterSlide hoặc LayoutSlide theo Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Ghép các run có cùng định dạng trong tất cả các đoạn văn trong tất cả các hình dạng chấp nhận được trong toàn bộ slide. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Đánh dấu tất cả các kết quả khớp của văn bản mẫu bằng màu đã chỉ định. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Đánh dấu tất cả các kết quả khớp của văn bản mẫu bằng màu đã chỉ định. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Đánh dấu tất cả các kết quả khớp của biểu thức chính quy bằng màu đã chỉ định. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Thay thế tất cả các lần xuất hiện của văn bản đã chỉ định bằng một văn bản khác đã chỉ định. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Thay thế tất cả các kết quả khớp của biểu thức chính quy bằng chuỗi đã chỉ định. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Trả về hoặc đặt ngày và giờ sẽ thay thế nội dung của các trường datetime. Thời gian tạo đối tượng Presentation này theo mặc định. **Đọc/ghi** java.util.Date.

**Trả về:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Trả về hoặc đặt ngày và giờ sẽ thay thế nội dung của các trường datetime. Thời gian tạo đối tượng Presentation này theo mặc định. **Đọc/ghi** java.util.Date.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Trả về trình quản lý HeaderFooter của bản trình chiếu. **Chỉ đọc** [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Trả về:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Lấy trình quản lý quyền cho bản trình chiếu này. **Chỉ đọc** [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Trả về:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Trả về danh sách tất cả các slide được định nghĩa trong bản trình chiếu. **Chỉ đọc** [ISlideCollection](../../com.aspose.slides/islidecollection).

**Trả về:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Trả về danh sách tất cả các phần slide được định nghĩa trong bản trình chiếu. **Chỉ đọc** [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Trả về:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Trả về đối tượng kích thước slide. **Chỉ đọc** [ISlideSize](../../com.aspose.slides/islidesize).

**Trả về:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Trả về đối tượng kích thước slide ghi chú. **Chỉ đọc** [INotesSize](../../com.aspose.slides/inotessize).

**Trả về:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Trả về danh sách tất cả các slide bố cục được định nghĩa trong bản trình chiếu. **Chỉ đọc** [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

Bạn có thể truy cập API thay thế để thêm/chèn/xóa/nhân bản slide bố cục bằng cách sử dụng thuộc tính IMasterSlide.LayoutSlides property.

**Trả về:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Trả về danh sách tất cả các slide chủ được định nghĩa trong bản trình chiếu. **Chỉ đọc** [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Trả về:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Trả về trình quản lý notes master. **Chỉ đọc** [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Trả về:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Trả về trình quản lý handout master. **Chỉ đọc** [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Trả về:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Trả về trình quản lý phông chữ. **Chỉ đọc** [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Trả về:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Trả về kiểu văn bản mặc định cho các hình dạng. **Chỉ đọc** [ITextStyle](../../com.aspose.slides/itextstyle).

**Trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Trả về bộ sưu tập các tác giả bình luận. **Chỉ đọc** [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Trả về:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Trả về đối tượng DocumentProperties chứa các thuộc tính tài liệu chuẩn và tùy chỉnh. **Chỉ đọc** [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Trả về:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Trả về bộ sưu tập tất cả hình ảnh trong bản trình chiếu. **Chỉ đọc** [IImageCollection](../../com.aspose.slides/iimagecollection).

**Trả về:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Trả về bộ sưu tập tất cả các tệp âm thanh nhúng trong bản trình chiếu. **Chỉ đọc** [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Trả về:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Trả về bộ sưu tập tất cả các tệp video nhúng trong bản trình chiếu. **Chỉ đọc** [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Trả về:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Trả về dữ liệu tùy chỉnh của bản trình chiếu. **Chỉ đọc** [ICustomData](../../com.aspose.slides/icustomdata).

**Trả về:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Lấy dự án VBA với macro của bản trình chiếu. **Đọc/ghi** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Trả về:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Lấy dự án VBA với macro của bản trình chiếu. **Đọc/ghi** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Trả về thông tin về định dạng mà bản trình chiếu được tải. **Chỉ đọc** [SourceFormat](../../com.aspose.slides/sourceformat).

**Trả về:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Trả về chủ đề master của bản trình chiếu. **Chỉ đọc** [IMasterTheme](../../com.aspose.slides/imastertheme).

**Trả về:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Cung cấp truy cập dễ dàng tới tất cả siêu liên kết có trong các slide của bản trình chiếu (không bao gồm master, layout, slide ghi chú). **Chỉ đọc** [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Trả về:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Lấy các thuộc tính chế độ xem toàn cục của bản trình chiếu. **Chỉ đọc** [IViewProperties](../../com.aspose.slides/iviewproperties).

**Trả về:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Biểu thị số slide đầu tiên trong bản trình chiếu. **Đọc/ghi** int.

**Trả về:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Biểu thị số slide đầu tiên trong bản trình chiếu. **Đọc/ghi** int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Trả về tất cả các phần dữ liệu tùy chỉnh trong bản trình chiếu. **Chỉ đọc** ICustomXmlPart[].

**Trả về:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Trả về bộ sưu tập các chữ ký được sử dụng để ký bản trình chiếu. **Chỉ đọc** [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Trả về bộ sưu tập các nhãn độ nhạy được áp dụng cho tài liệu bản trình chiếu. **Chỉ đọc** [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // In các nhãn đã áp dụng
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Thêm nhãn mới
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Lấy Id nhãn độ nhạy từ chính sách
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

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Lưu tất cả các slide của bản trình chiếu vào tệp với định dạng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | java.lang.String | Đường dẫn tới tệp được tạo. |
| format | int | Định dạng của dữ liệu xuất. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Lưu tất cả các slide của bản trình chiếu vào dòng dữ liệu với định dạng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Dòng xuất. |
| format | int | Định dạng của dữ liệu xuất. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Lưu tất cả các slide của bản trình chiếu vào tệp với định dạng đã chỉ định và các tùy chọn bổ sung.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | java.lang.String | Đường dẫn tới tệp được tạo. |
| format | int | Định dạng của dữ liệu xuất. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Các tùy chọn định dạng bổ sung. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Lưu tất cả các slide của bản trình chiếu vào dòng dữ liệu với định dạng đã chỉ định và các tùy chọn bổ sung.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Dòng xuất. |
| format | int | Định dạng của dữ liệu xuất. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Các tùy chọn định dạng bổ sung. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Lưu các slide đã chỉ định của bản trình chiếu vào tệp với định dạng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | java.lang.String | Đường dẫn tới tệp được tạo. |
| slides | int[] | Mảng vị trí slide, bắt đầu từ 1. |
| format | int | Định dạng của dữ liệu xuất. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Lưu các slide đã chỉ định của bản trình chiếu vào tệp với định dạng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | java.lang.String | Đường dẫn tới tệp được tạo. |
| slides | int[] | Mảng vị trí slide, bắt đầu từ 1. |
| format | int | Định dạng của dữ liệu xuất. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Các tùy chọn định dạng bổ sung. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Lưu các slide đã chỉ định của bản trình chiếu vào dòng dữ liệu với định dạng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Dòng xuất. |
| slides | int[] | Mảng vị trí slide, bắt đầu từ 1. |
| format | int | Định dạng của dữ liệu xuất. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Lưu các slide đã chỉ định của bản trình chiếu vào dòng dữ liệu với định dạng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Dòng xuất. |
| slides | int[] | Mảng vị trí slide, bắt đầu từ 1. |
| format | int | Định dạng của dữ liệu xuất. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Các tùy chọn định dạng bổ sung. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Lưu tất cả các slide của bản trình chiếu vào một tập hợp các tệp đại diện cho markup XAML.

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
public abstract IImage[] getImages(IRenderingOptions options)
```

Trả về các đối tượng Thumbnail Image cho tất cả các slide của bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Các tùy chọn render. |

**Trả về:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Trả về các đối tượng Thumbnail IImage cho các slide đã chỉ định của bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Các tùy chọn render. |
| slides | int[] | Mảng vị trí slide, bắt đầu từ 1. |

**Trả về:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Trả về các đối tượng Thumbnail Image cho tất cả các slide của bản trình chiếu với tỷ lệ tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Các tùy chọn render. |
| scaleX | float | Giá trị để thay đổi tỷ lệ Thumbnail theo trục x. |
| scaleY | float | Giá trị để thay đổi tỷ lệ Thumbnail theo trục y. |

**Trả về:**
com.aspose.slides.IImage[] - Bitmap objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Trả về các đối tượng Thumbnail Image cho các slide đã chỉ định của bản trình chiếu với tỷ lệ tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Các tùy chọn render. |
| slides | int[] | Mảng vị trí slide, bắt đầu từ 1. |
| scaleX | float | Giá trị để thay đổi tỷ lệ Thumbnail theo trục x. |
| scaleY | float | Giá trị để thay đổi tỷ lệ Thumbnail theo trục y. |

**Trả về:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Trả về các đối tượng Thumbnail Image cho tất cả các slide của bản trình chiếu với kích thước được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Các tùy chọn render. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Kích thước của hình ảnh cần tạo. |

**Trả về:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Trả về các đối tượng Thumbnail Image cho các slide đã chỉ định của bản trình chiếu với kích thước được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Các tùy chọn render. |
| slides | int[] | Mảng vị trí slide, bắt đầu từ 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Kích thước của hình ảnh cần tạo. |

**Trả về:**
com.aspose.slides.IImage[] - IImage objects.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Trả về một Slide, MasterSlide hoặc LayoutSlide theo Id.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| id | long | Id của một slide. |

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Ghép các run có cùng định dạng trong tất cả các đoạn văn trong tất cả các hình dạng chấp nhận được trong toàn bộ slide.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Đánh dấu tất cả các kết quả khớp của văn bản mẫu bằng màu đã chỉ định.

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // đánh dấu tất cả các lần xuất hiện riêng rẽ của 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đánh dấu. |
| highlightColor | java.lang.Integer | Màu dùng để đánh dấu văn bản. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Đánh dấu tất cả các kết quả khớp của văn bản mẫu bằng màu đã chỉ định.

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // đánh dấu tất cả các lần xuất hiện riêng rẽ của 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần đánh dấu. |
| highlightColor | java.lang.Integer | Màu dùng để đánh dấu văn bản. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Các tùy chọn tìm kiếm văn bản [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Đánh dấu tất cả các kết quả khớp của biểu thức chính quy bằng màu đã chỉ định.

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // đánh dấu tất cả các lần xuất hiện riêng rẽ của 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Biểu thức chính quy java.util.regex.Pattern để lấy các chuỗi cần đánh dấu. |
| highlightColor | java.lang.Integer | Màu dùng để đánh dấu văn bản. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Thay thế tất cả các lần xuất hiện của văn bản đã chỉ định bằng một văn bản khác đã chỉ định.

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Thay thế tất cả các lần xuất hiện riêng rẽ của 'the' bằng '***'
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
| newText | java.lang.String | Chuỗi để thay thế tất cả các lần xuất hiện của oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Các tùy chọn tìm kiếm văn bản [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Thay thế tất cả các kết quả khớp của biểu thức chính quy bằng chuỗi đã chỉ định.

> ```
> Ví dụ mã sau cho thấy cách thay thế văn bản bằng biểu thức chính quy bằng chuỗi đã chỉ định.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Thay thế tất cả các lần xuất hiện riêng rẽ của 'the' bằng '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Biểu thức chính quy java.util.regex.Pattern để lấy các chuỗi cần thay thế. |
| newText | java.lang.String | Chuỗi để thay thế tất cả các lần xuất hiện của các chuỗi cần thay thế. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |