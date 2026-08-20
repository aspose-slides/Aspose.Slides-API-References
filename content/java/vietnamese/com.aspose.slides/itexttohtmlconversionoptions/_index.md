---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Java API Reference
description: Các tùy chọn để trích xuất HTML từ văn bản Pptx.
type: docs
url: /vi/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Các tùy chọn để trích xuất HTML từ văn bản Pptx.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Trả về hoặc đặt giá trị, cho biết liệu có nên thêm tiêu đề Clipboard hay không. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Trả về hoặc đặt giá trị, cho biết liệu có nên thêm tiêu đề Clipboard hay không. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Trả về hoặc đặt độ sâu kế thừa cho các thuộc tính văn bản. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Trả về hoặc đặt độ sâu kế thừa cho các thuộc tính văn bản. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Trả về hoặc đặt đối tượng callback kiểm soát cách lưu trữ đối tượng bên ngoài. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Trả về hoặc đặt đối tượng callback kiểm soát cách lưu trữ đối tượng bên ngoài. |
| [getEncodingName()](#getEncodingName--) | Trả về hoặc đặt tên mã hoá HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Trả về hoặc đặt tên mã hoá HTML. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```


Trả về hoặc đặt giá trị, cho biết liệu có nên thêm tiêu đề Clipboard hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```


Trả về hoặc đặt giá trị, cho biết liệu có nên thêm tiêu đề Clipboard hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```


Trả về hoặc đặt độ sâu kế thừa cho các thuộc tính văn bản. Đọc/ghi [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Trả về:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```


Trả về hoặc đặt độ sâu kế thừa cho các thuộc tính văn bản. Đọc/ghi [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```


Trả về hoặc đặt đối tượng callback kiểm soát cách lưu trữ đối tượng bên ngoài. Đọc/ghi [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Trả về:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```


Trả về hoặc đặt đối tượng callback kiểm soát cách lưu trữ đối tượng bên ngoài. Đọc/ghi [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```


Trả về hoặc đặt tên mã hoá HTML. Giá trị này sẽ được lưu vào tệp HTML được tạo, nhưng việc đảm bảo tệp được lưu với mã hoá này là trách nhiệm của người gọi. Đọc/ghi String.

**Trả về:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```


Trả về hoặc đặt tên mã hoá HTML. Giá trị này sẽ được lưu vào tệp HTML được tạo, nhưng việc đảm bảo tệp được lưu với mã hoá này là trách nhiệm của người gọi. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |