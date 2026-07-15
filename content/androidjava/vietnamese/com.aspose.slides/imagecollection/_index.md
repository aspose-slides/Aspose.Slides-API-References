---
title: ImageCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho bộ sưu tập PPImage.
type: docs
url: /vi/com.aspose.slides/imagecollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Đại diện cho bộ sưu tập PPImage.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Trả về số lượng hình ảnh trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Thêm một bản sao của hình ảnh từ một bản trình chiếu khác. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Thêm một hình ảnh vào bản trình chiếu. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Thêm một hình ảnh vào bản trình chiếu từ luồng. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Tạo và thêm một hình ảnh vào bản trình chiếu từ luồng. |
| [addImage(byte[] buffer)](#addImage-byte---) | Thêm một hình ảnh vào bản trình chiếu từ bộ đệm được chỉ định. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Thêm một hình ảnh vào bản trình chiếu từ đối tượng Svg. |
| [iterator()](#iterator--) | Trả về một enumerator cho phép duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết liệu việc truy cập bộ sưu tập có được đồng bộ (an toàn với luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ hóa. |

### size() {#size--}
```
public final int size()
```

Trả về số lượng hình ảnh trong bộ sưu tập. Chỉ đọc  int .

**Trả về:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [IPPImage](../../com.aspose.slides/ippimage).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage)

### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

Thêm một bản sao của hình ảnh từ một bản trình chiếu khác.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Hình ảnh nguồn. |

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Hình ảnh đã thêm.

### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

Thêm một hình ảnh vào bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Hình ảnh cần thêm. |

--------------------

Phương pháp này chuyển các tệp metafile WMF/EMF thành hình ảnh PNG raster trước khi chèn vào bản trình chiếu.

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Hình ảnh đã thêm.

### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

Thêm một hình ảnh vào bản trình chiếu từ luồng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng để thêm hình ảnh. |

--------------------

Phương pháp này có thể thêm các tệp metafile WMF/EMF vào bản trình chiếu mà không chuyển chúng thành hình ảnh PNG raster.

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Hình ảnh đã thêm.

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Tạo và thêm một hình ảnh vào bản trình chiếu từ luồng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng để thêm tệp hình ảnh. |
| loadingStreamBehavior | int | Hành vi sẽ được áp dụng cho luồng. |

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Đã thêm [IPPImage](../../com.aspose.slides/ippimage).

### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

Thêm một hình ảnh vào bản trình chiếu từ bộ đệm được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| buffer | byte[] | Bộ đệm. |

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Hình ảnh đã thêm.

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Thêm một hình ảnh vào bản trình chiếu từ đối tượng Svg.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Đối tượng hình ảnh Svg [ISvgImage](../../com.aspose.slides/isvgimage) |

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Hình ảnh đã thêm.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

Trả về một enumerator cho phép duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Một IGenericEnumerator có thể được dùng để duyệt qua bộ sưu tập.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Một java.util.Iterator cho toàn bộ bộ sưu tập.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết liệu việc truy cập bộ sưu tập có được đồng bộ (an toàn với luồng) hay không. Chỉ đọc  boolean .

**Trả về:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về gốc đồng bộ hóa. Chỉ đọc  Object .

**Trả về:**
java.lang.Object