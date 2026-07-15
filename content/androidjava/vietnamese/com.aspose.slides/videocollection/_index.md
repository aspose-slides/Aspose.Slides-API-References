---
title: VideoCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một bộ sưu tập các đối tượng Video.
type: docs
url: /vi/com.aspose.slides/videocollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Biểu diễn một bộ sưu tập các đối tượng Video.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Trả về số lượng tệp video trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Thêm một bản sao của tệp video từ một bản trình bày khác. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Tạo và thêm video vào bản trình bày từ luồng. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Tạo và thêm video vào bản trình bày từ mảng byte. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép video vào mảng đã chỉ định bắt đầu từ chỉ mục đã chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ hoá. |
| [iterator()](#iterator--) | Trả về một enumerator để duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ bộ sưu tập. |
### size() {#size--}
```
public final int size()
```

Trả về số lượng tệp video trong bộ sưu tập. Đọc-chỉ int.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

Lấy phần tử tại chỉ mục đã chỉ định. Đọc-chỉ [IVideo](../../com.aspose.slides/ivideo).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

Thêm một bản sao của tệp video từ một bản trình bày khác.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video nguồn. |

**Trả về:**
[IVideo](../../com.aspose.slides/ivideo) - Video đã thêm.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Tạo và thêm video vào bản trình bày từ luồng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng để thêm tệp video. |
| loadingStreamBehavior | int | Hành vi sẽ được áp dụng cho luồng. |

**Trả về:**
[IVideo](../../com.aspose.slides/ivideo) - Đã thêm [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Tạo và thêm video vào bản trình bày từ mảng byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| videoData | byte[] | Byte video. |

**Trả về:**
[IVideo](../../com.aspose.slides/ivideo) - Video đã thêm.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép video vào mảng đã chỉ định bắt đầu từ chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng. |
| index | int | Chỉ mục. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. Đọc-chỉ boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về gốc đồng bộ hoá. Đọc-chỉ Object.

**Trả về:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Trả về một enumerator để duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Trả về một iterator java cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Một java.util.Iterator cho toàn bộ bộ sưu tập.