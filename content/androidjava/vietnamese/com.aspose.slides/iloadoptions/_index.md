---
title: ILoadOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to specify additional options such as format or default font when loading a presentation.
type: docs
url: /vi/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Cho phép chỉ định các tùy chọn bổ sung (như định dạng hoặc phông chữ mặc định) khi tải một bài thuyết trình.

## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Trả về hoặc đặt định dạng của bài thuyết trình để tải. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Trả về hoặc đặt định dạng của bài thuyết trình để tải. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Trả về hoặc đặt phông chữ Regular được sử dụng khi không tìm thấy phông chữ nguồn. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Trả về hoặc đặt phông chữ Regular được sử dụng khi không tìm thấy phông chữ nguồn. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Trả về hoặc đặt phông chữ Symbol được sử dụng khi không tìm thấy phông chữ nguồn. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Trả về hoặc đặt phông chữ Symbol được sử dụng khi không tìm thấy phông chữ nguồn. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Trả về hoặc đặt phông chữ Asian được sử dụng khi không tìm thấy phông chữ nguồn. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Trả về hoặc đặt phông chữ Asian được sử dụng khi không tìm thấy phông chữ nguồn. |
| [getPassword()](#getPassword--) | Lấy hoặc đặt mật khẩu. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Lấy hoặc đặt mật khẩu. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Thuộc tính này có ý nghĩa nếu tệp bài thuyết trình được bảo vệ bằng mật khẩu. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Thuộc tính này có ý nghĩa nếu tệp bài thuyết trình được bảo vệ bằng mật khẩu. |
| [getWarningCallback()](#getWarningCallback--) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Đại diện cho các tùy chọn có thể được sử dụng để quản lý hành vi xử lý Binary Large Objects (BLOBs), chẳng hạn như sử dụng tệp tạm thời hoặc giới hạn byte BLOBs tối đa trong bộ nhớ. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Đại diện cho các tùy chọn có thể được sử dụng để quản lý hành vi xử lý Binary Large Objects (BLOBs), chẳng hạn như sử dụng tệp tạm thời hoặc giới hạn byte BLOBs tối đa trong bộ nhớ. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Xác định nguồn cho các phông chữ bên ngoài sẽ được sử dụng bởi bài thuyết trình. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Xác định nguồn cho các phông chữ bên ngoài sẽ được sử dụng bởi bài thuyết trình. |
| [getInterruptionToken()](#getInterruptionToken--) | Token để giám sát các yêu cầu ngắt. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Token để giám sát các yêu cầu ngắt. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Trả về hoặc đặt giao diện callback quản lý việc tải tài nguyên bên ngoài. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Trả về hoặc đặt giao diện callback quản lý việc tải tài nguyên bên ngoài. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Đại diện cho các tùy chọn có thể được sử dụng để chỉ định hành vi bổ sung cho bảng tính. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Đại diện cho các tùy chọn có thể được sử dụng để chỉ định hành vi bổ sung cho bảng tính. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Trả về hoặc đặt ngôn ngữ mặc định cho văn bản trong bài thuyết trình. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Trả về hoặc đặt ngôn ngữ mặc định cho văn bản trong bài thuyết trình. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Xác định xem Aspose.Slides có xóa tất cả các đối tượng nhị phân nhúng khi tải bài thuyết trình hay không. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Xác định xem Aspose.Slides có xóa tất cả các đối tượng nhị phân nhúng khi tải bài thuyết trình hay không. |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Trả về hoặc đặt định dạng của bài thuyết trình để tải. Đọc/ghi [LoadFormat](../../com.aspose.slides/loadformat).

**Trả về:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Trả về hoặc đặt định dạng của bài thuyết trình để tải. Đọc/ghi [LoadFormat](../../com.aspose.slides/loadformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Trả về hoặc đặt phông chữ Regular được sử dụng khi không tìm thấy phông chữ nguồn. Đọc-ghi String.

**Trả về:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Trả về hoặc đặt phông chữ Regular được sử dụng khi không tìm thấy phông chữ nguồn. Đọc-ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Trả về hoặc đặt phông chữ Symbol được sử dụng khi không tìm thấy phông chữ nguồn. Đọc-ghi String.

**Trả về:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Trả về hoặc đặt phông chữ Symbol được sử dụng khi không tìm thấy phông chữ nguồn. Đọc-ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Trả về hoặc đặt phông chữ Asian được sử dụng khi không tìm thấy phông chữ nguồn. Đọc-ghi String.

**Trả về:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Trả về hoặc đặt phông chữ Asian được sử dụng khi không tìm thấy phông chữ nguồn. Đọc-ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Lấy hoặc đặt mật khẩu. Đọc-ghi String.

Giá trị: Mật khẩu.

**Trả về:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Lấy hoặc đặt mật khẩu. Đọc-ghi String.

Giá trị: Mật khẩu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Thuộc tính này có ý nghĩa nếu tệp bài thuyết trình được bảo vệ bằng mật khẩu. Giá trị true có nghĩa là chỉ tải các thuộc tính tài liệu từ tệp bài thuyết trình đã mã hoá và bỏ qua mật khẩu. Giá trị false có nghĩa là tải toàn bộ bài thuyết trình đã mã hoá bằng mật khẩu đúng. Nếu bài thuyết trình không được mã hoá thì giá trị thuộc tính luôn bị bỏ qua. Nếu các thuộc tính tài liệu của tệp đã mã hoá không công khai và giá trị thuộc tính là true thì các thuộc tính tài liệu không thể tải và sẽ ném ngoại lệ. Đọc-ghi boolean.

**Trả về:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Thuộc tính này có ý nghĩa nếu tệp bài thuyết trình được bảo vệ bằng mật khẩu. Giá trị true có nghĩa là chỉ tải các thuộc tính tài liệu từ tệp bài thuyết trình đã mã hoá và bỏ qua mật khẩu. Giá trị false có nghĩa là tải toàn bộ bài thuyết trình đã mã hoá bằng mật khẩu đúng. Nếu bài thuyết trình không được mã hoá thì giá trị thuộc tính luôn bị bỏ qua. Nếu các thuộc tính tài liệu của tệp đã mã hoá không công khai và giá trị thuộc tính là true thì các thuộc tính tài liệu không thể tải và sẽ ném ngoại lệ. Đọc-ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy. Đọc/ghi [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Trả về:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy. Đọc/ghi [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Đại diện cho các tùy chọn có thể được sử dụng để quản lý hành vi xử lý Binary Large Objects (BLOBs), chẳng hạn như sử dụng tệp tạm thời hoặc giới hạn byte BLOBs tối đa trong bộ nhớ. Các tùy chọn này nhằm thiết lập tỷ lệ hiệu năng/tiêu thụ bộ nhớ tốt nhất cho môi trường hoặc yêu cầu cụ thể.

--------------------

Binary Large Object (BLOB) là dữ liệu nhị phân được lưu dưới dạng một thực thể duy nhất – ví dụ BLOB có thể là âm thanh, video hoặc bản thuyết trình.

**Trả về:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Đại diện cho các tùy chọn có thể được sử dụng để quản lý hành vi xử lý Binary Large Objects (BLOBs), chẳng hạn như sử dụng tệp tạm thời hoặc giới hạn byte BLOBs tối đa trong bộ nhớ. Các tùy chọn này nhằm thiết lập tỷ lệ hiệu năng/tiêu thụ bộ nhớ tốt nhất cho môi trường hoặc yêu cầu cụ thể.

--------------------

Binary Large Object (BLOB) là dữ liệu nhị phân được lưu dưới dạng một thực thể duy nhất – ví dụ BLOB có thể là âm thanh, video hoặc bản thuyết trình.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Xác định nguồn cho các phông chữ bên ngoài sẽ được sử dụng bởi bài thuyết trình. Các phông chữ này có sẵn cho bài thuyết trình suốt vòng đời và không được chia sẻ với các bài thuyết trình khác.

**Trả về:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Xác định nguồn cho các phông chữ bên ngoài sẽ được sử dụng bởi bài thuyết trình. Các phông chữ này có sẵn cho bài thuyết trình suốt vòng đời và không được chia sẻ với các bài thuyết trình khác.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

Token để giám sát các yêu cầu ngắt.

--------------------

Token này quản lý toàn bộ vòng đời của thể hiện [IPresentation](../../com.aspose.slides/ipresentation). Bất kỳ thao tác dài nào, chẳng hạn tải hoặc lưu bài thuyết trình, sẽ bị ngắt bằng cách gọi phương thức [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) của [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Trả về:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

Token để giám sát các yêu cầu ngắt.

--------------------

Token này quản lý toàn bộ vòng đời của thể hiện [IPresentation](../../com.aspose.slides/ipresentation). Bất kỳ thao tác dài nào, chẳng hạn tải hoặc lưu bài thuyết trình, sẽ bị ngắt bằng cách gọi phương thức [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) của [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Trả về hoặc đặt giao diện callback quản lý việc tải tài nguyên bên ngoài. Đọc/ghi [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Trả về:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Trả về hoặc đặt giao diện callback quản lý việc tải tài nguyên bên ngoài. Đọc/ghi [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Đại diện cho các tùy chọn có thể được sử dụng để chỉ định hành vi bổ sung cho bảng tính.

**Trả về:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Đại diện cho các tùy chọn có thể được sử dụng để chỉ định hành vi bổ sung cho bảng tính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

Trả về hoặc đặt ngôn ngữ mặc định cho văn bản trong bài thuyết trình. Đọc/ghi String.

--------------------

> ```
> Example:
>   
>  // Use load options to define the default text culture
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Add new rectangle shape with text
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Check the first portion language
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

Trả về hoặc đặt ngôn ngữ mặc định cho văn bản trong bài thuyết trình. Đọc/ghi String.

--------------------

> ```
> Example:
>   
>  // Sử dụng tùy chọn tải để xác định ngôn ngữ văn bản mặc định
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
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Xác định xem Aspose.Slides có xóa tất cả các đối tượng nhị phân nhúng khi tải bài thuyết trình hay không.

Các loại đối tượng nhị phân nhúng:

 *  
 *  
 *  

Đọc/ghi boolean.

--------------------

> ```
> Ví dụ sau cho thấy cách tải bài thuyết trình mà không có bất kỳ đối tượng nhị phân nhúng nào.
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
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

Xác định xem Aspose.Slides có xóa tất cả các đối tượng nhị phân nhúng khi tải bài thuyết trình hay không.

Các loại đối tượng nhị phân nhúng:

 *  
 *  
 *  

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