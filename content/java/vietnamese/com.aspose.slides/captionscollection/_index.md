---
title: CaptionsCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một tập hợp các phụ đề đóng.
type: docs
url: /vi/com.aspose.slides/captionscollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Đại diện cho một tập hợp các phụ đề đóng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về phụ đề đóng tại chỉ mục được chỉ định. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Thêm phụ đề đóng WebVTT vào cuối tập hợp. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Thêm phụ đề đóng WebVTT vào cuối tập hợp từ luồng. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Xóa phụ đề đóng được chỉ định khỏi tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa phụ đề đóng tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả phụ đề đóng khỏi tập hợp. |
| [getCount()](#getCount--) | Trả về số phần tử trong tập hợp. |
| [iterator()](#iterator--) | Trả về một bộ đếm (enumerator) duyệt qua tập hợp. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
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
public final ICaptions add(String label, String filePath)
```

Thêm phụ đề đóng WebVTT vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| label | java.lang.String | Nhãn của phụ đề đóng. |
| filePath | java.lang.String | Đường dẫn tới tệp WebVTT. |

**Giá trị trả về:**
[ICaptions](../../com.aspose.slides/icaptions) - Thực thể [ICaptions](../../com.aspose.slides/icaptions) được thêm.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

Thêm phụ đề đóng WebVTT vào cuối tập hợp từ luồng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| label | java.lang.String | Nhãn của phụ đề đóng. |
| stream | java.io.InputStream | Luồng nhập chứa dữ liệu ở định dạng WebVTT. |

**Giá trị trả về:**
[ICaptions](../../com.aspose.slides/icaptions) - Thực thể [ICaptions](../../com.aspose.slides/icaptions) được thêm.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

Xóa phụ đề đóng được chỉ định khỏi tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Phụ đề đóng cần xóa. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa phụ đề đóng tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phụ đề đóng cần xóa. |

### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả phụ đề đóng khỏi tập hợp.

### getCount() {#getCount--}
```
public final int getCount()
```

Trả về số phần tử trong tập hợp. Chỉ đọc  int .

**Giá trị trả về:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

Trả về một bộ đếm (enumerator) duyệt qua tập hợp.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - Một  System.Collections.Generic.IEnumerator1  có thể được sử dụng để duyệt qua tập hợp.