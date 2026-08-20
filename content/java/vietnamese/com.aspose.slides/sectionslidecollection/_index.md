---
title: SectionSlideCollection
second_title: Aspose.Slides cho Tham khảo API Java
description: Đại diện cho một bộ sưu tập các slide trong phần.
type: docs
url: /vi/com.aspose.slides/sectionslidecollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

Đại diện cho một bộ sưu tập các slide trong phần.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ số được chỉ định. |
| [size()](#size--) | Lấy số lượng phần tử thực sự có trong bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép toàn bộ bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết liệu việc truy cập vào bộ sưu tập có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Lấy phần tử tại chỉ số được chỉ định. Chỉ đọc [ISlide](../../com.aspose.slides/islide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ISlide](../../com.aspose.slides/islide)
### size() {#size--}
```
public final int size()
```

Lấy số lượng phần tử thực sự có trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép toàn bộ bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích |
| index | int | Chỉ mục trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết liệu việc truy cập vào bộ sưu tập có được đồng bộ (thread-safe) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về gốc đồng bộ. Chỉ đọc Object.

**Trả về:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Một java.util.Iterator cho toàn bộ bộ sưu tập.