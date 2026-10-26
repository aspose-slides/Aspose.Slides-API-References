---
title: GradientStopCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một bộ sưu tập các dừng gradient.
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

Đại diện cho một bộ sưu tập các dừng gradient.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Trả về số lượng các dừng gradient trong một bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Trả về dừng gradient theo chỉ số. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Tạo dừng gradient mới và thêm nó vào cuối bộ sưu tập. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Tạo dừng gradient mới và thêm nó vào cuối bộ sưu tập. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Tạo dừng gradient mới và thêm nó vào cuối bộ sưu tập. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Tạo dừng gradient mới và chèn nó vào chỉ số đã chỉ định trong bộ sưu tập. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Tạo dừng gradient mới và chèn nó vào chỉ số đã chỉ định trong bộ sưu tập. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Tạo dừng gradient mới và chèn nó vào chỉ số đã chỉ định trong bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa dừng gradient tại chỉ số đã chỉ định. |
| [clear()](#clear--) | Xóa tất cả các dừng gradient khỏi bộ sưu tập. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập sang mảng đã chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về một giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (an toàn với đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một gốc đồng bộ. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Phiên bản. Chỉ đọc, kiểu long.

**Trả về:**
long

### size() {#size--}
```
public final int size()
```


Trả về số lượng các dừng gradient trong một bộ sưu tập. Chỉ đọc, kiểu int.

**Trả về:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```


Trả về dừng gradient theo chỉ số.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```


Tạo dừng gradient mới và thêm nó vào cuối bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | Vị trí của dừng gradient mới. |
| color | java.lang.Integer | Màu của dừng gradient mới. |

**Trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Chỉ số của dừng gradient mới trong bộ sưu tập.

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```


Tạo dừng gradient mới và thêm nó vào cuối bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | Vị trí của dừng gradient mới. |
| presetColor | int | Màu của dừng gradient mới. |

**Trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Chỉ số của dừng gradient mới trong bộ sưu tập.

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```


Tạo dừng gradient mới và thêm nó vào cuối bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | Vị trí của dừng gradient mới. |
| schemeColor | int | Màu của dừng gradient mới. |

**Trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Chỉ số của dừng gradient mới trong bộ sưu tập.

### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```


Tạo dừng gradient mới và chèn nó vào chỉ số đã chỉ định trong bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ số trong bộ sưu tập nơi dừng gradient mới sẽ được chèn. |
| position | float | Vị trí của dừng gradient mới. |
| color | java.lang.Integer | Màu của dừng gradient mới. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```


Tạo dừng gradient mới và chèn nó vào chỉ số đã chỉ định trong bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ số trong bộ sưu tập nơi dừng gradient mới sẽ được chèn. |
| position | float | Vị trí của dừng gradient mới. |
| presetColor | int | Màu của dừng gradient mới. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```


Tạo dừng gradient mới và chèn nó vào chỉ số đã chỉ định trong bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ số trong bộ sưu tập nơi dừng gradient mới sẽ được chèn. |
| position | float | Vị trí của dừng gradient mới. |
| schemeColor | int | Màu của dừng gradient mới. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Xóa dừng gradient tại chỉ số đã chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ số của dừng gradient cần được xóa. |

### clear() {#clear--}
```
public final void clear()
```


Xóa tất cả các dừng gradient khỏi bộ sưu tập.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```


Trả về một enumerator để duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```


Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Một java.util.Iterator cho toàn bộ bộ sưu tập.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Sao chép tất cả các phần tử từ bộ sưu tập sang mảng đã chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ số bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Trả về một giá trị cho biết liệu việc truy cập bộ sưu tập có được đồng bộ (an toàn với đa luồng) hay không. Chỉ đọc, kiểu boolean.

**Trả về:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về một gốc đồng bộ. Chỉ đọc, kiểu Object.

**Trả về:**
java.lang.Object