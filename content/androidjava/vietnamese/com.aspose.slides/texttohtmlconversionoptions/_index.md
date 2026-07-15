---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Các tùy chọn để trích xuất HTML từ văn bản Pptx.
type: docs
url: /vi/com.aspose.slides/texttohtmlconversionoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Các tùy chọn để trích xuất HTML từ văn bản Pptx.
## Hàm khởi tạo

| Constructor | Description |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Phương thức

| Method | Description |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Trả về hoặc đặt giá trị, chỉ ra liệu tiêu đề Clipboard có nên được thêm vào hay không. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Trả về hoặc đặt giá trị, chỉ ra liệu tiêu đề Clipboard có nên được thêm vào hay không. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Trả về hoặc đặt độ sâu kế thừa cho các thuộc tính văn bản. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Trả về hoặc đặt độ sâu kế thừa cho các thuộc tính văn bản. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Trả về hoặc đặt một đối tượng callback kiểm soát cách đối tượng bên ngoài sẽ được lưu trữ. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Trả về hoặc đặt một đối tượng callback kiểm soát cách đối tượng bên ngoài sẽ được lưu trữ. |
| [getEncodingName()](#getEncodingName--) | Trả về hoặc đặt tên mã hoá html. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Trả về hoặc đặt tên mã hoá html. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Trả về hoặc đặt giá trị, chỉ ra liệu tiêu đề Clipboard có nên được thêm vào hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Trả về hoặc đặt giá trị, chỉ ra liệu tiêu đề Clipboard có nên được thêm vào hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Trả về hoặc đặt độ sâu kế thừa cho các thuộc tính văn bản. Đọc/ghi [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Trả về:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Trả về hoặc đặt độ sâu kế thừa cho các thuộc tính văn bản. Đọc/ghi [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Trả về hoặc đặt một đối tượng callback kiểm soát cách đối tượng bên ngoài sẽ được lưu trữ. Đọc/ghi [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Trả về:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Trả về hoặc đặt một đối tượng callback kiểm soát cách đối tượng bên ngoài sẽ được lưu trữ. Đọc/ghi [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Trả về hoặc đặt tên mã hoá html. Giá trị này sẽ được lưu vào tệp HTML được tạo, nhưng việc đảm bảo tệp được lưu với mã hoá này là trách nhiệm của người gọi. Đọc/ghi String.

**Trả về:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Trả về hoặc đặt tên mã hoá html. Giá trị này sẽ được lưu vào tệp HTML được tạo, nhưng việc đảm bảo tệp được lưu với mã hoá này là trách nhiệm của người gọi. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |