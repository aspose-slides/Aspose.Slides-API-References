---
title: FillFormatCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn tập hợp các kiểu fill.
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

Biểu diễn tập hợp các kiểu fill.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua collection. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ collection. |
| [size()](#size--) | Lấy số lượng phần tử thực sự chứa trong collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ collection vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về một giá trị cho biết việc truy cập vào collection có được đồng bộ hoá (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |
### get_Item(int index) {#get-Item-int-}
```
public final IFillFormat get_Item(int index)
```


Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iterator()
```


Trả về một enumerator duyệt qua collection.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iteratorJava()
```


Trả về một java iterator cho toàn bộ collection.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - An java.util.Iterator for the entire collection.
### size() {#size--}
```
public final int size()
```


Lấy số lượng phần tử thực sự chứa trong collection. Chỉ đọc int.

**Giá trị trả về:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Sao chép tất cả các phần tử từ collection vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng mục tiêu. |
| index | int | Chỉ mục bắt đầu trong mảng mục tiêu. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Trả về một giá trị cho biết việc truy cập vào collection có được đồng bộ hoá (thread-safe) hay không. Chỉ đọc boolean.

**Giá trị trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về một synchronization root. Chỉ đọc Object.

**Giá trị trả về:**
java.lang.Object