---
title: IPresentationFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo bản trình chiếu qua giao diện COM
type: docs
url: /vi/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Cho phép tạo bản trình chiếu qua giao diện COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createPresentation()](#createPresentation--) | Tạo bản trình chiếu mới. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Tạo bản trình chiếu mới với các tùy chọn tải bổ sung |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Lấy thông tin về bản trình chiếu trong tệp được chỉ định. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Lấy thông tin về bản trình chiếu trong luồng được chỉ định. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Đọc một bản trình chiếu hiện có từ mảng |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Đọc một bản trình chiếu hiện có từ mảng với các tùy chọn tải bổ sung |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Đọc một bản trình chiếu hiện có từ luồng |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Đọc một bản trình chiếu hiện có từ luồng với các tùy chọn tải bổ sung |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Đọc một bản trình chiếu hiện có từ tệp |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Đọc một bản trình chiếu hiện có từ luồng với các tùy chọn tải bổ sung |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Trích xuất văn bản thô từ các slide |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Trích xuất văn bản thô từ các slide |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Trích xuất văn bản thô từ các slide |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```


Tạo bản trình chiếu mới.

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình chiếu mới
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```


Tạo bản trình chiếu mới với các tùy chọn tải bổ sung

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Các tùy chọn tải |

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình chiếu mới
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```


Lấy thông tin về bản trình chiếu trong tệp được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| file | java.lang.String | Tệp bản trình chiếu. |

**Trả về:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Thông tin bản trình chiếu
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```


Lấy thông tin về bản trình chiếu trong luồng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng bản trình chiếu. |

**Trả về:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Thông tin bản trình chiếu.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```


Đọc một bản trình chiếu hiện có từ mảng

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| data | byte[] | Mảng để đọc |

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình chiếu đã đọc
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```


Đọc một bản trình chiếu hiện có từ mảng với các tùy chọn tải bổ sung

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| data | byte[] | Mảng để đọc |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Các tùy chọn tải |

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình chiếu đã đọc
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```


Đọc một bản trình chiếu hiện có từ luồng

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng đầu vào để đọc |

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình chiếu đã đọc
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


Đọc một bản trình chiếu hiện có từ luồng với các tùy chọn tải bổ sung

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng đầu vào để đọc |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Các tùy chọn tải |

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình chiếu đã đọc
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```


Đọc một bản trình chiếu hiện có từ tệp

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| file | java.lang.String | Tên tệp |

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình chiếu đã đọc
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```


Đọc một bản trình chiếu hiện có từ luồng với các tùy chọn tải bổ sung

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| file | java.lang.String | Tên tệp |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Các tùy chọn tải |

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình chiếu đã đọc
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```


Trích xuất văn bản thô từ các slide

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| file | java.lang.String | Tệp đầu vào |
| mode | int | Chế độ trích xuất |

**Trả về:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Thể hiện PresentationText chứa mảng SlideText đại diện cho văn bản thô của các slide
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```


Trích xuất văn bản thô từ các slide

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng đầu vào |
| mode | int | Chế độ trích xuất |

**Trả về:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Thể hiện PresentationText chứa mảng SlideText đại diện cho văn bản thô của các slide
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Trích xuất văn bản thô từ các slide

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng đầu vào |
| mode | int | Chế độ trích xuất |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Các tùy chọn tải |

**Trả về:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Thể hiện PresentationText chứa mảng SlideText đại diện cho văn bản thô của các slide