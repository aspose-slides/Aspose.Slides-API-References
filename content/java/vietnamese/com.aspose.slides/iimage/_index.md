---
title: IImage
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một hình ảnh raster hoặc vector.
type: docs
url: /vi/com.aspose.slides/iimage/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Đại diện cho một hình ảnh raster hoặc vector.

--------------------

Giao diện này cung cấp một trừu tượng chung để xử lý cả hình ảnh raster và vector. Các triển khai có thể khác nhau tùy thuộc vào loại hình ảnh nền.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Lưu hình ảnh vào một tệp. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Lưu hình ảnh vào một tệp ở định dạng chỉ định. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Lưu hình ảnh vào một luồng ở định dạng chỉ định. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Lưu hình ảnh vào một tệp ở định dạng và chất lượng chỉ định. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Lưu hình ảnh vào một luồng ở định dạng và chất lượng chỉ định. |
| [getSize()](#getSize--) | Lấy kích thước của hình ảnh. |
| [getWidth()](#getWidth--) | Lấy chiều rộng của hình ảnh tính bằng pixel. |
| [getHeight()](#getHeight--) | Lấy chiều cao của hình ảnh tính bằng pixel. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Lưu hình ảnh vào một tệp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| filename | java.lang.String | Đường dẫn tới tệp nơi hình ảnh sẽ được lưu. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Lưu hình ảnh vào một tệp ở định dạng chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| filename | java.lang.String | Đường dẫn tới tệp nơi hình ảnh sẽ được lưu. |
| format | int | Định dạng hình ảnh. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Lưu hình ảnh vào một luồng ở định dạng chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng nơi hình ảnh sẽ được lưu. |
| format | int | Định dạng hình ảnh. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Lưu hình ảnh vào một tệp ở định dạng và chất lượng chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| filename | java.lang.String | Đường dẫn tới tệp nơi hình ảnh sẽ được lưu. |
| format | int | Định dạng hình ảnh. |
| quality | int | Chất lượng của hình ảnh đã lưu (0 đến 100). Tham số này chỉ ảnh hưởng tới việc lưu trong [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); với các định dạng khác, nó sẽ bị bỏ qua. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Lưu hình ảnh vào một luồng ở định dạng và chất lượng chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng nơi hình ảnh sẽ được lưu. |
| format | int | Định dạng hình ảnh. |
| quality | int | Chất lượng của hình ảnh đã lưu (0 đến 100). Tham số này chỉ ảnh hưởng tới việc lưu trong [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); với các định dạng khác, nó sẽ bị bỏ qua. |

### getSize() {#getSize--}
```
public abstract Dimension getSize()
```

Lấy kích thước của hình ảnh.

**Trả về:**
java.awt.Dimension
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Lấy chiều rộng của hình ảnh tính bằng pixel.

**Trả về:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Lấy chiều cao của hình ảnh tính bằng pixel.

**Trả về:**
int