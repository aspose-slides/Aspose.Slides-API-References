---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Các tùy chọn để trích xuất HTML từ văn bản Pptx.
type: docs
url: /vi/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Các tùy chọn để trích xuất HTML từ văn bản Pptx.
## Phương thức

| Method | Description |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Trả về hoặc đặt giá trị, cho biết có nên thêm tiêu đề Clipboard hay không. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Trả về hoặc đặt giá trị, cho biết có nên thêm tiêu đề Clipboard hay không. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Trả về hoặc đặt độ sâu kế thừa cho các thuộc tính văn bản. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Trả về hoặc đặt độ sâu kế thừa cho các thuộc tính văn bản. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Trả về hoặc đặt một đối tượng callback điều khiển cách đối tượng bên ngoài sẽ được lưu trữ. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Trả về hoặc đặt một đối tượng callback điều khiển cách đối tượng bên ngoài sẽ được lưu trữ. |
| [getEncodingName()](#getEncodingName--) | Trả về hoặc đặt tên mã hoá html. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Trả về hoặc đặt tên mã hoá html. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

Trả về hoặc đặt giá trị, cho biết có nên thêm tiêu đề Clipboard hay không. Đọc/ghi boolean.

**Returns:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

Trả về hoặc đặt giá trị, cho biết có nên thêm tiêu đề Clipboard hay không. Đọc/ghi boolean.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

Trả về hoặc đặt độ sâu kế thừa cho các thuộc tính văn bản. Đọc/ghi [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Returns:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

Trả về hoặc đặt độ sâu kế thừa cho các thuộc tính văn bản. Đọc/ghi [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

Trả về hoặc đặt một đối tượng callback điều khiển cách đối tượng bên ngoài sẽ được lưu trữ. Đọc/ghi [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Returns:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

Trả về hoặc đặt một đối tượng callback điều khiển cách đối tượng bên ngoài sẽ được lưu trữ. Đọc/ghi [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

Trả về hoặc đặt tên mã hoá html. Giá trị này sẽ được lưu vào tệp HTML được tạo, nhưng việc đảm bảo tệp được lưu với mã hoá này là trách nhiệm của người gọi. Đọc/ghi String.

**Returns:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

Trả về hoặc đặt tên mã hoá html. Giá trị này sẽ được lưu vào tệp HTML được tạo, nhưng việc đảm bảo tệp được lưu với mã hoá này là trách nhiệm của người gọi. Đọc/ghi String.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |