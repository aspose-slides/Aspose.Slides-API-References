---
title: WebDocument
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn dạng chuyển đổi của bản trình chiếu để lưu thành định dạng web.
type: docs
url: /vi/com.aspose.slides/webdocument/
---
**Kế thừa:**
java.lang.Object
```
public class WebDocument
```

Biểu diễn dạng chuyển đổi của bản trình chiếu để lưu thành định dạng web.

## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) hàm tạo. |

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [save()](#save--) | Lưu đầu ra tài liệu. |
| [getInput()](#getInput--) | Trả về bộ sưu tập các phần tử đầu vào (mẫu) của tài liệu. |
| [getOutput()](#getOutput--) | Trả về bộ sưu tập các phần tử đầu ra của tài liệu. |
| [getGlobal()](#getGlobal--) | Trả về kho lưu trữ toàn cục của tài liệu. |

### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```

[WebDocument](../../com.aspose.slides/webdocument) hàm tạo.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Các tùy chọn được thiết lập cho tài liệu. |

### save() {#save--}
```
public final void save()
```

Lưu đầu ra tài liệu.

### getInput() {#getInput--}
```
public final Input getInput()
```

Trả về bộ sưu tập các phần tử đầu vào (mẫu) của tài liệu. Chỉ đọc [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Trả về:**
[Input](../../com.aspose.slides/input)

### getOutput() {#getOutput--}
```
public final Output getOutput()
```

Trả về bộ sưu tập các phần tử đầu ra của tài liệu. Chỉ đọc [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // đặt thuộc tính "slideMargin" để sử dụng từ các mẫu
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... thiết lập các tùy chọn khác của tài liệu và sau đó lưu tài liệu
>   document.save();
> ```

**Trả về:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Trả về kho lưu trữ toàn cục của tài liệu. Chỉ đọc [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // đặt thuộc tính "slideMargin" để sử dụng từ các mẫu
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... thiết lập các tùy chọn khác của tài liệu và sau đó lưu tài liệu
>   document.save();
> ```

**Trả về:**
[Storage](../../com.aspose.slides/storage)