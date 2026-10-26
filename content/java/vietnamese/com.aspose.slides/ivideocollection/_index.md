---
title: IVideoCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một bộ sưu tập các đối tượng Video.
type: docs
url: /vi/com.aspose.slides/ivideocollection/
---
**Tất cả các giao diện đã triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Biểu diễn một bộ sưu tập các đối tượng Video.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Thêm một bản sao của tệp video từ một bản trình chiếu khác. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Tạo và thêm một video vào bản trình chiếu từ luồng. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Tạo và thêm một video vào bản trình chiếu từ mảng byte. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```


Lấy phần tử tại chỉ mục được chỉ định. Chỉ-đọc [IVideo](../../com.aspose.slides/ivideo).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```


Thêm một bản sao của tệp video từ một bản trình chiếu khác.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video nguồn. |

**Trả về:**
[IVideo](../../com.aspose.slides/ivideo) - Video đã thêm.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Tạo và thêm một video vào bản trình chiếu từ luồng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng để thêm tệp video từ. |
| loadingStreamBehavior | int | Hành vi sẽ được áp dụng cho luồng. |

**Trả về:**
[IVideo](../../com.aspose.slides/ivideo) - Đã thêm [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


Tạo và thêm một video vào bản trình chiếu từ mảng byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| videoData | byte[] | Các byte video. |

**Trả về:**
[IVideo](../../com.aspose.slides/ivideo) - Video đã thêm.