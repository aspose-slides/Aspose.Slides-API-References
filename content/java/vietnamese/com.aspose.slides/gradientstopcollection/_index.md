---
title: GradientStopCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một bộ sưu tập các điểm dừng gradient.
type: docs
url: /vi/com.aspose.slides/gradientstopcollection/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Biểu diễn một bộ sưu tập các điểm dừng gradient.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Trả về số lượng điểm dừng gradient trong một bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Trả về điểm dừng gradient theo chỉ số. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Tạo điểm dừng gradient mới và thêm nó vào cuối bộ sưu tập. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Tạo điểm dừng gradient mới và thêm nó vào cuối bộ sưu tập. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Tạo điểm dừng gradient mới và thêm nó vào cuối bộ sưu tập. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Tạo điểm dừng gradient mới và chèn nó vào vị trí chỉ định trong bộ sưu tập. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Tạo điểm dừng gradient mới và chèn nó vào vị trí chỉ định trong bộ sưu tập. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Tạo điểm dừng gradient mới và chèn nó vào vị trí chỉ định trong bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa một điểm dừng gradient tại chỉ số được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các điểm dừng gradient khỏi bộ sưu tập. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập tới mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Chỉ đọc long.

**Trả về:**
long
### size() {#size--}
```
public final int size()
```

Trả về số lượng điểm dừng gradient trong một bộ sưu tập. Chỉ đọc  int .

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

Trả về điểm dừng gradient theo chỉ số.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public final IGradientStop add(float position, Color color)
```

Tạo điểm dừng gradient mới và thêm nó vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | float | Vị trí của điểm dừng gradient mới. |
| color | java.awt.Color | Màu của điểm dừng gradient mới. |

**Trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Chỉ mục của điểm dừng gradient mới trong bộ sưu tập.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

Tạo điểm dừng gradient mới và thêm nó vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | float | Vị trí của điểm dừng gradient mới. |
| presetColor | int | Màu đã định sẵn của điểm dừng gradient mới. |

**Trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Chỉ mục của điểm dừng gradient mới trong bộ sưu tập.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

Tạo điểm dừng gradient mới và thêm nó vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | float | Vị trí của điểm dừng gradient mới. |
| schemeColor | int | Màu trong scheme của điểm dừng gradient mới. |

**Trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Chỉ mục của điểm dừng gradient mới trong bộ sưu tập.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public final void insert(int index, float position, Color color)
```

Tạo điểm dừng gradient mới và chèn nó vào vị trí chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục trong bộ sưu tập nơi điểm dừng gradient mới sẽ được chèn. |
| position | float | Vị trí của điểm dừng gradient mới. |
| color | java.awt.Color | Màu của điểm dừng gradient mới. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

Tạo điểm dừng gradient mới và chèn nó vào vị trí chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục trong bộ sưu tập nơi điểm dừng gradient mới sẽ được chèn. |
| position | float | Vị trí của điểm dừng gradient mới. |
| presetColor | int | Màu đã định sẵn của điểm dừng gradient mới. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

Tạo điểm dừng gradient mới và chèn nó vào vị trí chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục trong bộ sưu tập nơi điểm dừng gradient mới sẽ được chèn. |
| position | float | Vị trí của điểm dừng gradient mới. |
| schemeColor | int | Màu trong scheme của điểm dừng gradient mới. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa một điểm dừng gradient tại chỉ số được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của điểm dừng gradient cần xóa. |
### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các điểm dừng gradient khỏi bộ sưu tập.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Một IGenericEnumerator có thể được dùng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

Trả về một iterator java cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ bộ sưu tập tới mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (thread-safe) hay không. Chỉ đọc  boolean .

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một synchronization root. Chỉ đọc Object.

**Trả về:**
java.lang.Object