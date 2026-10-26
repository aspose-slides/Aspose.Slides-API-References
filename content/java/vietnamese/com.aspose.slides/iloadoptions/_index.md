---
title: ILoadOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cho phép chỉ định các tùy chọn bổ sung (như định dạng hoặc phông chữ mặc định) khi tải một bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Cho phép chỉ định các tùy chọn bổ sung (như định dạng hoặc phông chữ mặc định) khi tải một bản trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Trả về hoặc đặt định dạng của bản trình chiếu để tải. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Trả về hoặc đặt định dạng của bản trình chiếu để tải. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Trả về hoặc đặt phông chữ Regular được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Trả về hoặc đặt phông chữ Regular được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Trả về hoặc đặt phông chữ Symbol được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Trả về hoặc đặt phông chữ Symbol được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Trả về hoặc đặt phông chữ Asian được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Trả về hoặc đặt phông chữ Asian được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. |
| [getPassword()](#getPassword--) | Lấy hoặc đặt mật khẩu. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Lấy hoặc đặt mật khẩu. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo vệ bằng mật khẩu. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo vệ bằng mật khẩu. |
| [getWarningCallback()](#getWarningCallback--) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Mô tả các tùy chọn có thể được sử dụng để quản lý hành vi xử lý Binary Large Objects (BLOBs), chẳng hạn như sử dụng tệp tạm thời hoặc tối đa byte BLOBs trong bộ nhớ. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Mô tả các tùy chọn có thể được sử dụng để quản lý hành vi xử lý Binary Large Objects (BLOBs), chẳng hạn như sử dụng tệp tạm thời hoặc tối đa byte BLOBs trong bộ nhớ. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Xác định nguồn cho phông chữ bên ngoài sẽ được sử dụng bởi bản trình chiếu. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Xác định nguồn cho phông chữ bên ngoài sẽ được sử dụng bởi bản trình chiếu. |
| [getInterruptionToken()](#getInterruptionToken--) | Mã thông báo để giám sát yêu cầu ngắt. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Mã thông báo để giám sát yêu cầu ngắt. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Trả về hoặc đặt giao diện callback quản lý việc tải tài nguyên bên ngoài. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Trả về hoặc đặt giao diện callback quản lý việc tải tài nguyên bên ngoài. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Mô tả các tùy chọn có thể được sử dụng để chỉ định hành vi bảng tính bổ sung. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Mô tả các tùy chọn có thể được sử dụng để chỉ định hành vi bảng tính bổ sung. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Trả về hoặc đặt ngôn ngữ mặc định cho văn bản bản trình chiếu. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Trả về hoặc đặt ngôn ngữ mặc định cho văn bản bản trình chiếu. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Xác định nếu Aspose.Slides sẽ xóa tất cả các đối tượng nhị phân nhúng khi tải bản trình chiếu. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Xác định nếu Aspose.Slides sẽ xóa tất cả các đối tượng nhị phân nhúng khi tải bản trình chiếu. |
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Trả về hoặc đặt định dạng của bản trình chiếu để tải. Đọc/ghi [LoadFormat](../../com.aspose.slides/loadformat).

**Trả về:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Trả về hoặc đặt định dạng của bản trình chiếu để tải. Đọc/ghi [LoadFormat](../../com.aspose.slides/loadformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Trả về hoặc đặt phông chữ Regular được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. Đọc/ghi String.

**Trả về:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Trả về hoặc đặt phông chữ Regular được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Trả về hoặc đặt phông chữ Symbol được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. Đọc/ghi String.

**Trả về:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Trả về hoặc đặt phông chữ Symbol được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Trả về hoặc đặt phông chữ Asian được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. Đọc/ghi String.

**Trả về:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Trả về hoặc đặt phông chữ Asian được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Lấy hoặc đặt mật khẩu. Đọc/ghi String.

Giá trị: Mật khẩu.

**Trả về:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Lấy hoặc đặt mật khẩu. Đọc/ghi String.

Giá trị: Mật khẩu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo vệ bằng mật khẩu. Giá trị true có nghĩa là chỉ các thuộc tính tài liệu phải được tải từ tệp bản trình chiếu được mã hoá và mật khẩu sẽ bị bỏ qua. Giá trị false có nghĩa là toàn bộ bản trình chiếu đã mã hoá phải được tải bằng mật khẩu đúng. Nếu bản trình chiếu không được mã hoá thì giá trị thuộc tính luôn bị bỏ qua. Nếu các thuộc tính tài liệu của tệp đã mã hoá không công khai và giá trị thuộc tính là true thì các thuộc tính tài liệu không thể được tải và sẽ ném ngoại lệ. Đọc/ghi boolean.

**Trả về:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo vệ bằng mật khẩu. Giá trị true có nghĩa là chỉ các thuộc tính tài liệu phải được tải từ tệp bản trình chiếu được mã hoá và mật khẩu sẽ bị bỏ qua. Giá trị false có nghĩa là toàn bộ bản trình chiếu đã mã hoá phải được tải bằng mật khẩu đúng. Nếu bản trình chiếu không được mã hoá thì giá trị thuộc tính luôn bị bỏ qua. Nếu các thuộc tính tài liệu của tệp đã mã hoá không công khai và giá trị thuộc tính là true thì các thuộc tính tài liệu không thể được tải và sẽ ném ngoại lệ. Đọc/ghi boolean.

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

Mô tả các tùy chọn có thể được sử dụng để quản lý hành vi xử lý Binary Large Objects (BLOBs), chẳng hạn như sử dụng tệp tạm thời hoặc tối đa byte BLOBs trong bộ nhớ. Các tùy chọn này nhằm thiết lập tỷ lệ hiệu suất/bộ nhớ tốt nhất cho môi trường hoặc yêu cầu cụ thể.

--------------------

Binary Large Object (BLOB) là dữ liệu nhị phân được lưu trữ dưới dạng một thực thể duy nhất - tức là BLOB có thể là âm thanh, video hoặc bản trình chiếu.

**Trả về:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Mô tả các tùy chọn có thể được sử dụng để quản lý hành vi xử lý Binary Large Objects (BLOBs), chẳng hạn như sử dụng tệp tạm thời hoặc tối đa byte BLOBs trong bộ nhớ. Các tùy chọn này nhằm thiết lập tỷ lệ hiệu suất/bộ nhớ tốt nhất cho môi trường hoặc yêu cầu cụ thể.

--------------------

Binary Large Object (BLOB) là dữ liệu nhị phân được lưu trữ dưới dạng một thực thể duy nhất - tức là BLOB có thể là âm thanh, video hoặc bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |
### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Xác định nguồn cho phông chữ bên ngoài sẽ được sử dụng bởi bản trình chiếu. Các phông chữ này có sẵn cho bản trình chiếu trong suốt vòng đời và không được chia sẻ với các bản trình chiếu khác

**Trả về:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Xác định nguồn cho phông chữ bên ngoài sẽ được sử dụng bởi bản trình chiếu. Các phông chữ này có sẵn cho bản trình chiếu trong suốt vòng đời và không được chia sẻ với các bản trình chiếu khác

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |
### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

Mã thông báo để giám sát yêu cầu ngắt.

--------------------

Mã thông báo này quản lý toàn bộ vòng đời của thể hiện [IPresentation](../../com.aspose.slides/ipresentation). Bất kỳ hoạt động kéo dài nào, chẳng hạn tải hoặc lưu bản trình chiếu, sẽ bị ngắt bằng cách gọi phương thức [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) của [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Trả về:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

Mã thông báo để giám sát yêu cầu ngắt.

--------------------

Mã thông báo này quản lý toàn bộ vòng đời của thể hiện [IPresentation](../../com.aspose.slides/ipresentation). Bất kỳ hoạt động kéo dài nào, chẳng hạn tải hoặc lưu bản trình chiếu, sẽ bị ngắt bằng cách gọi phương thức [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) của [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

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

Mô tả các tùy chọn có thể được sử dụng để chỉ định hành vi bảng tính bổ sung.

**Trả về:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Mô tả các tùy chọn có thể được sử dụng để chỉ định hành vi bảng tính bổ sung.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |
### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

Trả về hoặc đặt ngôn ngữ mặc định cho văn bản bản trình chiếu. Đọc/ghi String.

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

Trả về hoặc đặt ngôn ngữ mặc định cho văn bản bản trình chiếu. Đọc/ghi String.

--------------------

> ```
> Example:
>   
>  // Sử dụng tùy chọn tải để xác định văn hoá văn bản mặc định
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Thêm hình chữ nhật mới với văn bản
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

Xác định nếu Aspose.Slides sẽ xóa tất cả các đối tượng nhị phân nhúng khi tải bản trình chiếu.

Các loại đối tượng nhị phân nhúng:

 *  
 *  
 *  

Đọc/ghi boolean.

--------------------

> ```
> Ví dụ sau cho thấy cách tải bản trình chiếu mà không có bất kỳ đối tượng nhị phân nhúng nào.
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

**Trả về:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

Xác định nếu Aspose.Slides sẽ xóa tất cả các đối tượng nhị phân nhúng khi tải bản trình chiếu.

Các loại đối tượng nhị phân nhúng:

 *  
 *  
 *  

Đọc/ghi boolean.

--------------------

> ```
> Ví dụ sau cho thấy cách tải bản trình chiếu mà không có bất kỳ đối tượng nhị phân nhúng nào.
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
| --- | --- | --- |
| value | boolean |  |