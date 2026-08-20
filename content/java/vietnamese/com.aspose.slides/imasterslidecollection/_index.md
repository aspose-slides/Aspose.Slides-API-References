---
title: IMasterSlideCollection
second_title: Aspose.Slides cho Tham chiếu API Java
description: Biểu thị một tập hợp các slide mẫu.
type: docs
url: /vi/com.aspose.slides/imasterslidecollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Biểu thị một tập hợp các slide mẫu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại vị trí chỉ định. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại vị trí chỉ định trong bộ sưu tập. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Xóa các slide mẫu không dùng. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Thêm một bản sao của slide mẫu được chỉ định vào cuối bộ sưu tập. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Chèn một bản sao của slide mẫu được chỉ định vào vị trí xác định trong bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```


Lấy phần tử tại vị trí chỉ định. Chỉ đọc [IMasterSlide](../../com.aspose.slides/imasterslide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```


Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide mẫu cần xóa khỏi bộ sưu tập. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Xóa phần tử tại vị trí chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số bắt đầu từ 0 của phần tử cần xóa. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```


Xóa các slide mẫu không dùng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| ignorePreserveField | boolean | Xác định liệu phương thức này có nên xóa slide mẫu không dùng ngay cả khi thuộc tính [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) của nó được đặt thành true hay không. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```


Thêm một bản sao của slide mẫu được chỉ định vào cuối bộ sưu tập. Các slide bố cục liên kết cũng sẽ được sao chép.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide cần sao chép. |

**Giá trị trả về:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Slide đã thêm.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


Chèn một bản sao của slide mẫu được chỉ định vào vị trí xác định trong bộ sưu tập. Các slide bố cục liên kết cũng sẽ được sao chép.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của slide mới. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide cần sao chép. |

**Giá trị trả về:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Slide mẫu đã chèn.