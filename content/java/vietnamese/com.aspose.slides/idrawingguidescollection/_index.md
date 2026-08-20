---
title: IDrawingGuidesCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một bộ sưu tập các hướng dẫn vẽ có thể điều chỉnh.
type: docs
url: /vi/com.aspose.slides/idrawingguidescollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Biểu diễn một bộ sưu tập các hướng dẫn vẽ có thể điều chỉnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về hướng dẫn vẽ theo chỉ mục. |
| [add(byte orientation, float position)](#add-byte-float-) | Thêm hướng dẫn vẽ vào cuối bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa hướng dẫn vẽ tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
| [getCount()](#getCount--) | Lấy số lượng tất cả các phần tử trong bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


Trả về hướng dẫn vẽ theo chỉ mục. Chỉ đọc [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```


Thêm hướng dẫn vẽ vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| orientation | byte | Hướng của hướng dẫn vẽ. |
| position | float | Vị trí của hướng dẫn vẽ tính bằng điểm. |

**Giá trị trả về:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Xóa hướng dẫn vẽ tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của hướng dẫn vẽ cần xóa. |

### clear() {#clear--}
```
public abstract void clear()
```


Xóa tất cả các phần tử khỏi bộ sưu tập.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Lấy số lượng tất cả các phần tử trong bộ sưu tập. Chỉ đọc int.

**Giá trị trả về:**
int