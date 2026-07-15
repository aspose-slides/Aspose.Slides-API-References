---
title: AdjustValueCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một bộ sưu tập các điều chỉnh của hình dạng.
type: docs
url: /vi/com.aspose.slides/adjustvaluecollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

Biểu diễn một bộ sưu tập các điều chỉnh của hình dạng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Trả về số lượng các điều chỉnh. |
| [get_Item(int index)](#get-Item-int-) | Trả về điều chỉnh theo chỉ mục. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập sang mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ. |
| [iterator()](#iterator--) | Trả về một enumerator cho toàn bộ bộ sưu tập. |
### size() {#size--}
```
public final int size()
```

Trả về số lượng các điều chỉnh. int chỉ đọc.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```

Trả về điều chỉnh theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | chỉ mục của điều chỉnh. |

**Trả về:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ bộ sưu tập sang mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. boolean chỉ đọc.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về gốc đồng bộ. Object chỉ đọc.

**Trả về:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```

Trả về một enumerator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.IEnumerator