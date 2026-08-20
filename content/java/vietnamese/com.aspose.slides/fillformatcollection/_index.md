---
title: FillFormatCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn tập hợp các kiểu tô màu.
type: docs
url: /vi/com.aspose.slides/fillformatcollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)
```
public final class FillFormatCollection extends DomObject<FormatScheme> implements IFillFormatCollection
```

Biểu diễn tập hợp các kiểu tô màu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [iterator()](#iterator--) | Trả về một trình lặp duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ tập hợp. |
| [size()](#size--) | Lấy số phần tử thực sự chứa trong tập hợp. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ tập hợp vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết liệu việc truy cập vào tập hợp có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một gốc đồng bộ. |
### get_Item(int index) {#get-Item-int-}
```
public final IFillFormat get_Item(int index)
```

Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iterator()
```

Trả về một trình lặp duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iteratorJava()
```

Trả về một iterator java cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - An java.util.Iterator for the entire collection.
### size() {#size--}
```
public final int size()
```

Lấy số phần tử thực sự chứa trong tập hợp. Chỉ đọc int.

**Trả về:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ tập hợp vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết liệu việc truy cập vào tập hợp có được đồng bộ (thread-safe) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một gốc đồng bộ. Chỉ đọc Object.

**Trả về:**
java.lang.Object