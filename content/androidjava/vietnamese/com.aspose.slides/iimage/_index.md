---
title: IImage
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một ảnh raster hoặc vector.
type: docs
url: /vi/com.aspose.slides/iimage/
---
**Tất cả các Interface đã triển khai:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Biểu diễn một ảnh raster hoặc vector.

--------------------

Giao diện này cung cấp một abstraction chung để xử lý cả ảnh raster và vector. Các triển khai có thể khác nhau tùy thuộc vào loại ảnh nền.

## Phương thức

| Method | Description |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Lưu ảnh vào tệp. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Lưu ảnh vào tệp ở định dạng được chỉ định. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Lưu ảnh vào luồng ở định dạng được chỉ định. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Lưu ảnh vào tệp ở định dạng và chất lượng được chỉ định. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Lưu ảnh vào luồng ở định dạng và chất lượng được chỉ định. |
| [getSize()](#getSize--) | Lấy kích thước của ảnh. |
| [getWidth()](#getWidth--) | Lấy độ rộng của ảnh tính bằng pixel. |
| [getHeight()](#getHeight--) | Lấy độ cao của ảnh tính bằng pixel. |

### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Lưu ảnh vào tệp.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Đường dẫn tới tệp nơi ảnh sẽ được lưu. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Lưu ảnh vào tệp ở định dạng được chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Đường dẫn tới tệp nơi ảnh sẽ được lưu. |
| format | int | Định dạng ảnh. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Lưu ảnh vào luồng ở định dạng được chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng nơi ảnh sẽ được lưu. |
| format | int | Định dạng ảnh. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Lưu ảnh vào tệp ở định dạng và chất lượng được chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Đường dẫn tới tệp nơi ảnh sẽ được lưu. |
| format | int | Định dạng ảnh. |
| quality | int | Chất lượng của ảnh đã lưu (0 tới 100). Tham số này chỉ ảnh hưởng đến việc lưu trong [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); với các định dạng khác, nó sẽ bị bỏ qua. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Lưu ảnh vào luồng ở định dạng và chất lượng được chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng nơi ảnh sẽ được lưu. |
| format | int | Định dạng ảnh. |
| quality | int | Chất lượng của ảnh đã lưu (0 tới 100). Tham số này chỉ ảnh hưởng đến việc lưu trong [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); với các định dạng khác, nó sẽ bị bỏ qua. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

Lấy kích thước của ảnh.

**Trả về:**
[Size](../../com.aspose.slides.android/size)

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Lấy độ rộng của ảnh tính bằng pixel.

**Trả về:**
int

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Lấy độ cao của ảnh tính bằng pixel.

**Trả về:**
int