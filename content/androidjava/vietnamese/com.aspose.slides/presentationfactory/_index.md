---
title: PresentationFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo trình chiếu qua giao diện COM
type: docs
url: /vi/com.aspose.slides/presentationfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Cho phép tạo trình chiếu qua giao diện COM

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```

## Các hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getInstance()](#getInstance--) | Phiên bản tĩnh của nhà máy trình chiếu. |
| [createPresentation()](#createPresentation--) | Tạo trình chiếu mới. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Tạo trình chiếu mới với các tùy chọn tải bổ sung |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Tạo đối tượng PresentationInfo mới từ tệp và liên kết trình chiếu với nó. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Tạo đối tượng PresentationInfo mới từ luồng và liên kết trình chiếu với nó. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Đọc một trình chiếu hiện có từ mảng |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Đọc một trình chiếu hiện có từ mảng với các tùy chọn tải bổ sung |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Đọc một trình chiếu hiện có từ luồng |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Đọc một trình chiếu hiện có từ luồng với các tùy chọn tải bổ sung |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Đọc một trình chiếu hiện có từ tệp |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Đọc một trình chiếu hiện có từ luồng với các tùy chọn tải bổ sung |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Lấy văn bản thô từ các slide |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Lấy văn bản thô từ các slide |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Lấy văn bản thô từ các slide |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```


### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```


Phiên bản tĩnh của nhà máy trình chiếu. Chỉ đọc [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Trả về:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```


Tạo trình chiếu mới.

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Trình chiếu mới
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```


Tạo trình chiếu mới với các tùy chọn tải bổ sung

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Tùy chọn tải |

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Trình chiếu mới
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```


Tạo đối tượng PresentationInfo mới từ tệp và liên kết trình chiếu với nó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| file | java.lang.String | Tệp trình chiếu. |

**Trả về:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Thông tin trình chiếu được liên kết với trình chiếu.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```


Tạo đối tượng PresentationInfo mới từ luồng và liên kết trình chiếu với nó. Lấy thông tin về trình chiếu trong luồng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng trình chiếu. |

**Trả về:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Thông tin trình chiếu được liên kết với trình chiếu.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPPresentation readPresentation(byte[] data)
```


Đọc một trình chiếu hiện có từ mảng

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| data | byte[] | Mảng để đọc |

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Trình chiếu đã đọc
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```


Đọc một trình chiếu hiện có từ mảng với các tùy chọn tải bổ sung

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| data | byte[] | Mảng để đọc |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Tùy chọn tải |

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Trình chiếu đã đọc
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```


Đọc một trình chiếu hiện có từ luồng

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng đầu vào để đọc |

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Trình chiếu đã đọc
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


Đọc một trình chiếu hiện có từ luồng với các tùy chọn tải bổ sung

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng đầu vào để đọc |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Tùy chọn tải |

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Trình chiếu đã đọc
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```


Đọc một trình chiếu hiện có từ tệp

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| file | java.lang.String | Tên tệp |

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Trình chiếu đã đọc
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```


Đọc một trình chiếu hiện có từ luồng với các tùy chọn tải bổ sung

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| file | java.lang.String | Tên tệp |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Tùy chọn tải |

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Trình chiếu đã đọc
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```


Lấy văn bản thô từ các slide

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| file | java.lang.String | Tệp đầu vào |
| mode | int | Chế độ trích xuất |

**Trả về:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Thực thể PresentationText chứa mảng SlideText đại diện cho văn bản thô của các slide
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```


Lấy văn bản thô từ các slide

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng đầu vào |
| mode | int | Chế độ trích xuất |

**Trả về:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Thực thể PresentationText chứa mảng SlideText đại diện cho văn bản thô của các slide
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Lấy văn bản thô từ các slide

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng đầu vào |
| mode | int | Chế độ trích xuất |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Tùy chọn tải |

**Trả về:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Thực thể PresentationText chứa mảng SlideText đại diện cho văn bản thô của các slide