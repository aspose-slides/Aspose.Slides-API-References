---
title: DrawingGuidesCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một bộ sưu tập các hướng dẫn vẽ có thể điều chỉnh.
type: docs
url: /vi/com.aspose.slides/drawingguidescollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Đại diện cho một bộ sưu tập các hướng dẫn vẽ có thể điều chỉnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về hướng dẫn vẽ theo chỉ mục. |
| [add(byte orientation, float position)](#add-byte-float-) | Thêm hướng dẫn vẽ vào cuối bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa hướng dẫn vẽ ở chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần tử trong bộ sưu tập. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [getCount()](#getCount--) | Trả về số lượng phần tử trong bộ sưu tập. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

Trả về hướng dẫn vẽ theo chỉ mục. Chỉ đọc [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```

Thêm hướng dẫn vẽ vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| orientation | byte | Hướng của hướng dẫn vẽ. |
| position | float | Vị trí của hướng dẫn vẽ tính bằng điểm. |

**Trả về:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa hướng dẫn vẽ ở chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của hướng dẫn vẽ sẽ bị xóa. |

### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các phần tử trong bộ sưu tập.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### getCount() {#getCount--}
```
public final int getCount()
```

Trả về số lượng phần tử trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |