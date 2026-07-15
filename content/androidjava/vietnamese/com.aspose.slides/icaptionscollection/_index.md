---
title: ICaptionsCollection
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Biểu diễn một bộ sưu tập của phụ đề đóng.
type: docs
url: /vi/com.aspose.slides/icaptionscollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Biểu diễn một bộ sưu tập của phụ đề đóng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về phụ đề đóng tại chỉ mục được chỉ định. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Thêm phụ đề đóng WebVTT vào cuối bộ sưu tập. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Thêm phụ đề đóng WebVTT vào cuối bộ sưu tập từ một luồng. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Xóa phụ đề đóng được chỉ định khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa phụ đề đóng tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả phụ đề đóng khỏi bộ sưu tập. |
| [getCount()](#getCount--) | Trả về số lượng phần tử trong bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```

Trả về phụ đề đóng tại chỉ mục được chỉ định. Chỉ đọc [ICaptions](../../com.aspose.slides/icaptions).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```

Thêm phụ đề đóng WebVTT vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| label | java.lang.String | Nhãn của phụ đề đóng. |
| filePath | java.lang.String | Đường dẫn tới tệp WebVTT. |

**Giá trị trả về:**
[ICaptions](../../com.aspose.slides/icaptions) - Thực thể [ICaptions](../../com.aspose.slides/icaptions) đã được thêm.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```

Thêm phụ đề đóng WebVTT vào cuối bộ sưu tập từ một luồng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| label | java.lang.String | Nhãn của phụ đề đóng. |
| stream | java.io.InputStream | Luồng đầu vào chứa dữ liệu ở định dạng WebVTT. |

**Giá trị trả về:**
[ICaptions](../../com.aspose.slides/icaptions) - Thực thể [ICaptions](../../com.aspose.slides/icaptions) đã được thêm.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```

Xóa phụ đề đóng được chỉ định khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Phụ đề đóng cần xóa. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phụ đề đóng tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phụ đề đóng cần xóa. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả phụ đề đóng khỏi bộ sưu tập.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Trả về số lượng phần tử trong bộ sưu tập. Chỉ đọc int .

**Giá trị trả về:**
int