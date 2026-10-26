---
title: IMasterSlideCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một tập hợp các slide master.
type: docs
url: /vi/com.aspose.slides/imasterslidecollection/
---
**Tất cả các giao diện được thực thi:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Biểu diễn một tập hợp các slide master.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục đã chỉ định của tập hợp. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Xóa các slide master không sử dụng. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Thêm một bản sao của slide master được chỉ định vào cuối tập hợp. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Chèn một bản sao của slide master được chỉ định vào vị trí chỉ định của tập hợp. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Lấy phần tử tại chỉ mục đã chỉ định. Chỉ đọc [IMasterSlide](../../com.aspose.slides/imasterslide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide master cần xóa khỏi tập hợp. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ mục đã chỉ định của tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên zero của phần tử cần xóa. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Xóa các slide master không sử dụng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| ignorePreserveField | boolean | Xác định liệu phương thức này có nên xóa các master không sử dụng ngay cả khi thuộc tính [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) của nó được đặt thành true hay không. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Thêm một bản sao của slide master được chỉ định vào cuối tập hợp. Các slide bố cục được liên kết sẽ cũng được sao chép.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide cần sao chép. |

**Trả về:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Slide được thêm.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Chèn một bản sao của slide master được chỉ định vào vị trí chỉ định của tập hợp. Các slide bố cục được liên kết sẽ cũng được sao chép.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của slide mới. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide cần sao chép. |

**Trả về:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Slide master đã chèn.