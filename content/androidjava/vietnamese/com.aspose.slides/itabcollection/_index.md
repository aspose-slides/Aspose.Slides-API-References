---
title: ITabCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một tập hợp các tab.
type: docs
url: /vi/com.aspose.slides/itabcollection/
---
**Tất cả các giao diện đã triển khai:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Biểu diễn một tập hợp các tab.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [add(double position, int align)](#add-double-int-) | Thêm một Tab vào tập hợp. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Thêm một Tab vào tập hợp. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục được chỉ định của tập hợp. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [ITab](../../com.aspose.slides/itab).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

Thêm một Tab vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | double | Vị trí Tab. |
| align | int | Căn chỉnh Tab. |

**Giá trị trả về:**
[ITab](../../com.aspose.slides/itab) - Tab đã thêm.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

Thêm một Tab vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Đối tượng Tab sẽ được thêm vào cuối tập hợp. |

**Giá trị trả về:**
int - Chỉ mục nơi tab được thêm.
### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các phần tử khỏi tập hợp.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ mục được chỉ định của tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần xóa. |