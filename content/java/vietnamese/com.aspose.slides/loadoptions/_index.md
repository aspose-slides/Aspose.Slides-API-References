---
title: LoadOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cho phép chỉ định các tùy chọn bổ sung như định dạng hoặc phông chữ mặc định khi tải một bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/loadoptions/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Cho phép chỉ định các tùy chọn bổ sung (như định dạng hoặc phông chữ mặc định) khi tải bản trình chiếu.
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Tạo các tùy chọn tải mặc định mới. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Tạo các tùy chọn tải mới. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Trả về hoặc đặt định dạng của bản trình chiếu để tải. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Trả về hoặc đặt định dạng của bản trình chiếu để tải. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Trả về hoặc đặt phông Regular được sử dụng nếu không tìm thấy phông nguồn. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Trả về hoặc đặt phông Regular được sử dụng nếu không tìm thấy phông nguồn. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Trả về hoặc đặt phông Symbol được sử dụng nếu không tìm thấy phông nguồn. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Trả về hoặc đặt phông Symbol được sử dụng nếu không tìm thấy phông nguồn. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Trả về hoặc đặt phông Asian được sử dụng nếu không tìm thấy phông nguồn. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Trả về hoặc đặt phông Asian được sử dụng nếu không tìm thấy phông nguồn. |
| [getPassword()](#getPassword--) | Lấy hoặc đặt mật khẩu. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Lấy hoặc đặt mật khẩu. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo mật bằng mật khẩu. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo mật bằng mật khẩu. |
| [getWarningCallback()](#getWarningCallback--) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Biểu thị các tùy chọn có thể được sử dụng để quản lý hành vi xử lý Các Đối tượng Nhị phân Lớn (BLOBs), chẳng hạn như sử dụng tệp tạm thời hoặc số byte BLOB tối đa trong bộ nhớ. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Biểu thị các tùy chọn có thể được sử dụng để quản lý hành vi xử lý Các Đối tượng Nhị phân Lớn (BLOBs), chẳng hạn như sử dụng tệp tạm thời hoặc số byte BLOB tối đa trong bộ nhớ. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Xác định nguồn cho các phông chữ bên ngoài sẽ được sử dụng bởi bản trình chiếu. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Xác định nguồn cho các phông chữ bên ngoài sẽ được sử dụng bởi bản trình chiếu. |
| [getInterruptionToken()](#getInterruptionToken--) | Mã token để giám sát các yêu cầu ngắt. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Mã token để giám sát các yêu cầu ngắt. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Trả về hoặc đặt giao diện callback quản lý việc tải tài nguyên bên ngoài. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Trả về hoặc đặt giao diện callback quản lý việc tải tài nguyên bên ngoài. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Lấy các tùy chọn cho bảng tính. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Lấy các tùy chọn cho bảng tính. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Trả về hoặc đặt ngôn ngữ mặc định cho văn bản bản trình chiếu. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Trả về hoặc đặt ngôn ngữ mặc định cho văn bản bản trình chiếu. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Xác định xem Aspose.Slides có xóa tất cả các đối tượng nhị phân nhúng khi tải bản trình chiếu hay không. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Xác định xem Aspose.Slides có xóa tất cả các đối tượng nhị phân nhúng khi tải bản trình chiếu hay không. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Tạo các tùy chọn tải mặc định mới.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Tạo các tùy chọn tải mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| loadFormat | int | Định dạng của bản trình chiếu cần tải. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Trả về hoặc đặt định dạng của bản trình chiếu để tải. Đọc/ghi [LoadFormat](../../com.aspose.slides/loadformat).

**Trả về:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Trả về hoặc đặt định dạng của bản trình chiếu để tải. Đọc/ghi [LoadFormat](../../com.aspose.slides/loadformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Trả về hoặc đặt phông Regular được sử dụng nếu không tìm thấy phông nguồn. Đọc/ghi String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Sử dụng các tùy chọn tải để định nghĩa phông chữ regular và asian mặc định
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Tải bản trình chiếu
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Tạo hình thu nhỏ của slide
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Tạo PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Tạo XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Trả về hoặc đặt phông Regular được sử dụng nếu không tìm thấy phông nguồn. Đọc/ghi String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Sử dụng các tùy chọn tải để xác định các phông chữ regular và asian mặc định
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Tải bản trình chiếu
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Tạo hình thu nhỏ cho slide
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Tạo PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Tạo XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Trả về hoặc đặt phông Symbol được sử dụng nếu không tìm thấy phông nguồn. Đọc/ghi String.

**Trả về:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Trả về hoặc đặt phông Symbol được sử dụng nếu không tìm thấy phông nguồn. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Trả về hoặc đặt phông Asian được sử dụng nếu không tìm thấy phông nguồn. Đọc/ghi String.

**Trả về:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Trả về hoặc đặt phông Asian được sử dụng nếu không tìm thấy phông nguồn. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Lấy hoặc đặt mật khẩu. Đọc/ghi String.

--------------------

> ```
> Ví dụ mã sau minh họa cách mở bản trình chiếu PowerPoint được bảo vệ bằng mật khẩu.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // làm việc với bản trình chiếu đã giải mã
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Giá trị: Mật khẩu.

**Trả về:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Lấy hoặc đặt mật khẩu. Đọc/ghi String.

--------------------

> ```
> Mã mẫu sau đây minh họa cách mở bản trình chiếu PowerPoint được bảo vệ bằng mật khẩu.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // làm việc với bản trình chiếu đã giải mã
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Giá trị: Mật khẩu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo mật bằng mật khẩu. Giá trị true có nghĩa là chỉ các thuộc tính tài liệu phải được tải từ tệp bản trình chiếu đã mã hoá và mật khẩu sẽ bị bỏ qua. Giá trị false có nghĩa là toàn bộ bản trình chiếu đã mã hoá phải được tải bằng mật khẩu đúng. Nếu bản trình chiếu không được mã hoá thì giá trị thuộc tính luôn bị bỏ qua. Nếu các thuộc tính tài liệu của tệp đã mã hoá không công khai và giá trị thuộc tính là true thì các thuộc tính tài liệu không thể được tải và sẽ ném ra ngoại lệ. Đọc/ghi boolean.

**Trả về:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo mật bằng mật khẩu. Giá trị true có nghĩa là chỉ các thuộc tính tài liệu phải được tải từ tệp bản trình chiếu đã mã hoá và mật khẩu sẽ bị bỏ qua. Giá trị false có nghĩa là toàn bộ bản trình chiếu đã mã hoá phải được tải bằng mật khẩu đúng. Nếu bản trình chiếu không được mã hoá thì giá trị thuộc tính luôn bị bỏ qua. Nếu các thuộc tính tài liệu của tệp đã mã hoá không công khai và giá trị thuộc tính là true thì các thuộc tính tài liệu không thể được tải và sẽ ném ra ngoại lệ. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy. Đọc/ghi [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Trả về:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy. Đọc/ghi [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Biểu thị các tùy chọn có thể được sử dụng để quản lý hành vi xử lý Các Đối tượng Nhị phân Lớn (BLOBs), chẳng hạn như sử dụng tệp tạm thời hoặc số byte BLOB tối đa trong bộ nhớ. Các tùy chọn này nhằm thiết lập tỷ lệ hiệu năng/tiêu thụ bộ nhớ tốt nhất cho môi trường hoặc yêu cầu cụ thể.

--------------------

Một Đối tượng Nhị phân Lớn (BLOB) là dữ liệu nhị phân được lưu trữ dưới dạng một thực thể duy nhất - tức là BLOB có thể là âm thanh, video hoặc chính bản trình chiếu.

**Trả về:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Biểu thị các tùy chọn có thể được sử dụng để quản lý hành vi xử lý Các Đối tượng Nhị phân Lớn (BLOBs), chẳng hạn như sử dụng tệp tạm thời hoặc số byte BLOB tối đa trong bộ nhớ. Các tùy chọn này nhằm thiết lập tỷ lệ hiệu năng/tiêu thụ bộ nhớ tốt nhất cho môi trường hoặc yêu cầu cụ thể.

--------------------

Một Đối tượng Nhị phân Lớn (BLOB) là dữ liệu nhị phân được lưu trữ dưới dạng một thực thể duy nhất - tức là BLOB có thể là âm thanh, video hoặc chính bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Xác định nguồn cho các phông chữ bên ngoài sẽ được sử dụng bởi bản trình chiếu. Các phông chữ này có sẵn cho bản trình chiếu trong suốt thời gian tồn tại và không được chia sẻ với các bản trình chiếu khác

--------------------

> ```
> Ví dụ sau cho thấy cách chỉ định các phông chữ tùy chỉnh được sử dụng với PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //làm việc với bản trình chiếu
>  //CustomFont1, CustomFont2 cũng như các phông chữ từ thư mục assets\fonts & global\fonts và các thư mục con của chúng có sẵn cho bản trình chiếu
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Trả về:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Xác định nguồn cho các phông chữ bên ngoài sẽ được sử dụng bởi bản trình chiếu. Các phông chữ này có sẵn cho bản trình chiếu trong suốt thời gian tồn tại và không được chia sẻ với các bản trình chiếu khác

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //làm việc với bản trình chiếu
>  //CustomFont1, CustomFont2 cũng như các phông chữ từ thư mục assets\fonts & global\fonts và các thư mục con của chúng có sẵn cho bản trình chiếu
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

Mã token để giám sát các yêu cầu ngắt.

--------------------

Mã token này quản lý toàn bộ vòng đời của thể hiện [IPresentation](../../com.aspose.slides/ipresentation). Bất kỳ hoạt động nào chạy lâu, chẳng hạn như tải hoặc lưu bản trình chiếu, sẽ bị ngắt thông qua việc gọi phương thức [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) của [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Trả về:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Mã token để giám sát các yêu cầu ngắt.

--------------------

Mã token này quản lý toàn bộ vòng đời của thể hiện [IPresentation](../../com.aspose.slides/ipresentation). Bất kỳ hoạt động nào chạy lâu, chẳng hạn như tải hoặc lưu bản trình chiếu, sẽ bị ngắt thông qua việc gọi phương thức [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) của [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Trả về hoặc đặt giao diện callback quản lý việc tải tài nguyên bên ngoài. Đọc/ghi [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Trả về:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Trả về hoặc đặt giao diện callback quản lý việc tải tài nguyên bên ngoài. Đọc/ghi [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Lấy các tùy chọn cho bảng tính. Ví dụ, các tùy chọn này ảnh hưởng đến việc tính công thức cho biểu đồ.

**Trả về:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Lấy các tùy chọn cho bảng tính. Ví dụ, các tùy chọn này ảnh hưởng đến việc tính công thức cho biểu đồ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Trả về hoặc đặt ngôn ngữ mặc định cho văn bản bản trình chiếu. Đọc/ghi String.

--------------------

> ```
> Example:
>   
>  // Sử dụng các tùy chọn tải để định nghĩa văn hoá văn bản mặc định
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Thêm hình chữ nhật mới có văn bản
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Kiểm tra ngôn ngữ của phần đầu tiên
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

Trả về hoặc đặt ngôn ngữ mặc định cho văn bản bản trình chiếu. Đọc/ghi String.

--------------------

> ```
> Example:
>   
>  // Sử dụng các tùy chọn tải để định nghĩa văn hoá văn bản mặc định
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Thêm hình chữ nhật mới có văn bản
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Kiểm tra ngôn ngữ của phần đầu tiên
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

Xác định xem Aspose.Slides có xóa tất cả các đối tượng nhị phân nhúng khi tải bản trình chiếu hay không.

Các loại đối tượng nhị phân nhúng:

Đọc/ghi boolean.

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Mặc định là **false**.

**Trả về:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Xác định xem Aspose.Slides có xóa tất cả các đối tượng nhị phân nhúng khi tải bản trình chiếu hay không.

Các loại đối tượng nhị phân nhúng:

Đọc/ghi boolean.

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Mặc định là **false**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |