---
title: IPresentationFactory
second_title: Aspose.Slides cho Java Tham chiếu API
description: Cho phép tạo bản trình bày qua giao diện COM
type: docs
url: /vi/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Cho phép tạo bản trình bày qua giao diện COM
## Phương thức

| Method | Description |
| --- | --- |
| [createPresentation()](#createPresentation--) | Tạo bản trình bày mới. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Tạo bản trình bày mới với các tùy chọn tải bổ sung |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Lấy thông tin về bản trình bày trong tệp được chỉ định. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Lấy thông tin về bản trình bày trong luồng được chỉ định. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Đọc một bản trình bày hiện có từ mảng |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Đọc một bản trình bày hiện có từ mảng với các tùy chọn tải bổ sung |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Đọc một bản trình bày hiện có từ luồng |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Đọc một bản trình bày hiện có từ luồng với các tùy chọn tải bổ sung |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Đọc một bản trình bày hiện có từ tệp |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Đọc một bản trình bày hiện có từ luồng với các tùy chọn tải bổ sung |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Lấy văn bản thô từ các slide |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Lấy văn bản thô từ các slide |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Lấy văn bản thô từ các slide |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```


Tạo bản trình bày mới.

**Giá trị trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình bày mới
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```


Tạo bản trình bày mới với các tùy chọn tải bổ sung

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Tùy chọn tải |

**Giá trị trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình bày mới
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```


Lấy thông tin về bản trình bày trong tệp được chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Tệp bản trình bày. |

**Giá trị trả về:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Thông tin bản trình bày
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```


Lấy thông tin về bản trình bày trong luồng được chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng bản trình bày. |

**Giá trị trả về:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Thông tin bản trình bày.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```


Đọc một bản trình bày hiện có từ mảng

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Mảng để đọc |

**Giá trị trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình bày đã đọc
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```


Đọc một bản trình bày hiện có từ mảng với các tùy chọn tải bổ sung

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Mảng để đọc |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Tùy chọn tải |

**Giá trị trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình bày đã đọc
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```


Đọc một bản trình bày hiện có từ luồng

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng đầu vào để đọc |

**Giá trị trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình bày đã đọc
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


Đọc một bản trình bày hiện có từ luồng với các tùy chọn tải bổ sung

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng đầu vào để đọc |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Tùy chọn tải |

**Giá trị trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình bày đã đọc
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```


Đọc một bản trình bày hiện có từ tệp

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Tên tệp |

**Giá trị trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình bày đã đọc
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```


Đọc một bản trình bày hiện có từ luồng với các tùy chọn tải bổ sung

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Tên tệp |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Tùy chọn tải |

**Giá trị trả về:**
[IPresentation](../../com.aspose.slides/ipresentation) - Bản trình bày đã đọc
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```


Lấy văn bản thô từ các slide

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Tệp đầu vào |
| mode | int | Chế độ trích xuất |

**Giá trị trả về:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Đối tượng PresentationText chứa mảng SlideText đại diện cho văn bản thô của các slide
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```


Lấy văn bản thô từ các slide

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng đầu vào |
| mode | int | Chế độ trích xuất |

**Giá trị trả về:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Đối tượng PresentationText chứa mảng SlideText đại diện cho văn bản thô của các slide
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Lấy văn bản thô từ các slide

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng đầu vào |
| mode | int | Chế độ trích xuất |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Tùy chọn tải |

**Giá trị trả về:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Đối tượng PresentationText chứa mảng SlideText đại diện cho văn bản thô của các slide