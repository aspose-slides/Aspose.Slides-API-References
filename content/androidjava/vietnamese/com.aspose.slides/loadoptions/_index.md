---
title: LoadOptions
second_title: Aspose.Slides for Android qua Tham chiếu API Java
description: Cho phép chỉ định các tùy chọn bổ sung như định dạng hoặc phông chữ mặc định khi tải một bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/loadoptions/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Cho phép chỉ định các tùy chọn bổ sung (như định dạng hoặc phông chữ mặc định) khi tải bản trình chiếu.
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Tạo các tùy chọn tải mặc định mới. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Tạo các tùy chọn tải mới. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Trả về hoặc đặt định dạng của bản trình chiếu cần tải. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Trả về hoặc đặt định dạng của bản trình chiếu cần tải. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Trả về hoặc đặt phông Regular được sử dụng khi không tìm thấy phông nguồn. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Trả về hoặc đặt phông Regular được sử dụng khi không tìm thấy phông nguồn. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Trả về hoặc đặt phông Symbol được sử dụng khi không tìm thấy phông nguồn. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Trả về hoặc đặt phông Symbol được sử dụng khi không tìm thấy phông nguồn. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Trả về hoặc đặt phông Asian được sử dụng khi không tìm thấy phông nguồn. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Trả về hoặc đặt phông Asian được sử dụng khi không tìm thấy phông nguồn. |
| [getPassword()](#getPassword--) | Lấy hoặc đặt mật khẩu. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Lấy hoặc đặt mật khẩu. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo vệ bằng mật khẩu. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo vệ bằng mật khẩu. |
| [getWarningCallback()](#getWarningCallback--) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy bỏ. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy bỏ. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Biểu diễn các tùy chọn có thể dùng để quản lý hành vi xử lý Binary Large Objects (BLOBs), chẳng hạn như sử dụng tập tin tạm thời hoặc số byte BLOBs tối đa trong bộ nhớ. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Biểu diễn các tùy chọn có thể dùng để quản lý hành vi xử lý Binary Large Objects (BLOBs), chẳng hạn như sử dụng tập tin tạm thời hoặc số byte BLOBs tối đa trong bộ nhớ. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Chỉ định nguồn cho phông chữ bên ngoài sẽ được sử dụng bởi bản trình chiếu. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Chỉ định nguồn cho phông chữ bên ngoài sẽ được sử dụng bởi bản trình chiếu. |
| [getInterruptionToken()](#getInterruptionToken--) | Mã thông báo để giám sát các yêu cầu ngắt. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Mã thông báo để giám sát các yêu cầu ngắt. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Trả về hoặc đặt giao diện callback quản lý việc tải nguồn tài nguyên bên ngoài. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Trả về hoặc đặt giao diện callback quản lý việc tải nguồn tài nguyên bên ngoài. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Lấy các tùy chọn cho bảng tính. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Lấy các tùy chọn cho bảng tính. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Trả về hoặc đặt ngôn ngữ mặc định cho văn bản bản trình chiếu. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Trả về hoặc đặt ngôn ngữ mặc định cho văn bản bản trình chiếu. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Xác định xem Aspose.Slides có sẽ xóa tất cả các đối tượng nhị phân nhúng khi tải bản trình chiếu hay không. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Xác định xem Aspose.Slides có sẽ xóa tất cả các đối tượng nhị phân nhúng khi tải bản trình chiếu hay không. |
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

Trả về hoặc đặt định dạng của bản trình chiếu cần tải. Đọc/ghi [LoadFormat](../../com.aspose.slides/loadformat).

**Giá trị trả về:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Trả về hoặc đặt định dạng của bản trình chiếu cần tải. Đọc/ghi [LoadFormat](../../com.aspose.slides/loadformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Trả về hoặc đặt phông Regular được sử dụng khi không tìm thấy phông nguồn. Đọc/ghi String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Sử dụng các tùy chọn tải để xác định phông chữ regular và asian mặc định
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Tải bản trình chiếu
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Tạo hình thu nhỏ cho slide
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Tạo PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Tạo XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Giá trị trả về:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Trả về hoặc đặt phông Regular được sử dụng khi không tìm thấy phông nguồn. Đọc/ghi String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Sử dụng các tùy chọn tải để xác định phông chữ regular và asian mặc định
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Tải bản trình chiếu
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Tạo hình thu nhỏ cho slide
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
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

Trả về hoặc đặt phông Symbol được sử dụng khi không tìm thấy phông nguồn. Đọc/ghi String.

**Giá trị trả về:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Trả về hoặc đặt phông Symbol được sử dụng khi không tìm thấy phông nguồn. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Trả về hoặc đặt phông Asian được sử dụng khi không tìm thấy phông nguồn. Đọc/ghi String.

**Giá trị trả về:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Trả về hoặc đặt phông Asian được sử dụng khi không tìm thấy phông nguồn. Đọc/ghi String.

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
> The following sample code shows how to open password protected PowerPoint Presentation.
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

**Giá trị trả về:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Lấy hoặc đặt mật khẩu. Đọc/ghi String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
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

Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo vệ bằng mật khẩu. Giá trị true có nghĩa là chỉ cần tải các thuộc tính tài liệu từ tệp bản trình chiếu đã mã hoá và bỏ qua mật khẩu. Giá trị false có nghĩa là toàn bộ bản trình chiếu đã mã hoá sẽ được tải với mật khẩu đúng. Nếu bản trình chiếu không được mã hoá thì giá trị thuộc tính luôn bị bỏ qua. Nếu các thuộc tính tài liệu của tệp đã mã hoá không công khai và giá trị thuộc tính là true thì các thuộc tính tài liệu không thể tải và sẽ ném ngoại lệ. Đọc/ghi boolean.

**Giá trị trả về:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo vệ bằng mật khẩu. Giá trị true có nghĩa là chỉ cần tải các thuộc tính tài liệu từ tệp bản trình chiếu đã mã hoá và bỏ qua mật khẩu. Giá trị false có nghĩa là toàn bộ bản trình chiếu đã mã hoá sẽ được tải với mật khẩu đúng. Nếu bản trình chiếu không được mã hoá thì giá trị thuộc tính luôn bị bỏ qua. Nếu các thuộc tính tài liệu của tệp đã mã hoá không công khai và giá trị thuộc tính là true thì các thuộc tính tài liệu không thể tải và sẽ ném ngoại lệ. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy bỏ. Đọc/ghi [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Giá trị trả về:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hoặc bị hủy bỏ. Đọc/ghi [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Biểu diễn các tùy chọn có thể dùng để quản lý hành vi xử lý Binary Large Objects (BLOBs), chẳng hạn như sử dụng tập tin tạm thời hoặc số byte BLOBs tối đa trong bộ nhớ. Những tùy chọn này nhằm thiết lập tỷ lệ hiệu năng/tiêu thụ bộ nhớ tốt nhất cho môi trường hoặc yêu cầu cụ thể.

--------------------

Một Binary Large Object (BLOB) là dữ liệu nhị phân được lưu dưới dạng một thực thể duy nhất - tức là BLOB có thể là âm thanh, video hoặc bản trình chiếu tự nó.

**Giá trị trả về:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Biểu diễn các tùy chọn có thể dùng để quản lý hành vi xử lý Binary Large Objects (BLOBs), chẳng hạn như sử dụng tập tin tạm thời hoặc số byte BLOBs tối đa trong bộ nhớ. Những tùy chọn này nhằm thiết lập tỷ lệ hiệu năng/tiêu thụ bộ nhớ tốt nhất cho môi trường hoặc yêu cầu cụ thể.

--------------------

Một Binary Large Object (BLOB) là dữ liệu nhị phân được lưu dưới dạng một thực thể duy nhất - tức là BLOB có thể là âm thanh, video hoặc bản trình chiếu tự nó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Chỉ định nguồn cho phông chữ bên ngoài sẽ được sử dụng bởi bản trình chiếu. Những phông chữ này có sẵn cho bản trình chiếu trong suốt vòng đời và không được chia sẻ với các bản trình chiếu khác

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //làm việc với bản trình chiếu
>  //CustomFont1, CustomFont2 cùng với các phông chữ từ thư mục assets\fonts & global\fonts và các thư mục con của chúng đều khả dụng cho bản trình chiếu
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Giá trị trả về:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Chỉ định nguồn cho phông chữ bên ngoài sẽ được sử dụng bởi bản trình chiếu. Những phông chữ này có sẵn cho bản trình chiếu trong suốt vòng đời và không được chia sẻ với các bản trình chiếu khác

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //làm việc với bản trình chiếu
>  //CustomFont1, CustomFont2 cùng với các phông chữ từ thư mục assets\fonts & global\fonts và các thư mục con của chúng đều khả dụng cho bản trình chiếu
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

Mã thông báo để giám sát các yêu cầu ngắt.

--------------------

Mã thông báo này quản lý toàn bộ vòng đời của thực thể [IPresentation](../../com.aspose.slides/ipresentation). Bất kỳ hoạt động nào kéo dài, chẳng hạn như tải hoặc lưu bản trình chiếu, sẽ bị ngắt thông qua việc gọi phương thức [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) của [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Giá trị trả về:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Mã thông báo để giám sát các yêu cầu ngắt.

--------------------

Mã thông báo này quản lý toàn bộ vòng đời của thực thể [IPresentation](../../com.aspose.slides/ipresentation). Bất kỳ hoạt động nào kéo dài, chẳng hạn như tải hoặc lưu bản trình chiếu, sẽ bị ngắt thông qua việc gọi phương thức [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) của [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Trả về hoặc đặt giao diện callback quản lý việc tải nguồn tài nguyên bên ngoài. Đọc/ghi [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Giá trị trả về:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Trả về hoặc đặt giao diện callback quản lý việc tải nguồn tài nguyên bên ngoài. Đọc/ghi [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Lấy các tùy chọn cho bảng tính. Ví dụ, các tùy chọn này ảnh hưởng tới việc tính toán công thức cho biểu đồ.

**Giá trị trả về:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Lấy các tùy chọn cho bảng tính. Ví dụ, các tùy chọn này ảnh hưởng tới việc tính toán công thức cho biểu đồ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | |
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
>  // Sử dụng các tùy chọn tải để xác định văn hoá văn bản mặc định
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Thêm hình chữ nhật mới với văn bản
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Kiểm tra ngôn ngữ phần đầu tiên
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Giá trị trả về:**
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
>  // Sử dụng các tùy chọn tải để xác định văn hoá văn bản mặc định
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Thêm hình chữ nhật mới với văn bản
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Kiểm tra ngôn ngữ phần đầu tiên
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

Xác định xem Aspose.Slides có sẽ xóa tất cả các đối tượng nhị phân nhúng khi tải bản trình chiếu hay không.

Các loại đối tượng nhị phân nhúng:

Đọc/ghi boolean .

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

Mặc định là **false** .

**Giá trị trả về:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Xác định xem Aspose.Slides có sẽ xóa tất cả các đối tượng nhị phân nhúng khi tải bản trình chiếu hay không.

Các loại đối tượng nhị phân nhúng:

Đọc/ghi boolean .

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

Mặc định là **false** .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | |
| value | boolean |  |