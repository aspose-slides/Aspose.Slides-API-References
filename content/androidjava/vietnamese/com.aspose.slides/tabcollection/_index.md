---
title: TabCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một tập hợp các tab.
type: docs
url: /vi/com.aspose.slides/tabcollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Đại diện cho một tập hợp các tab.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Lấy số phần tử thực tế có trong tập hợp. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ số đã chỉ định. |
| [add(double position, int align)](#add-double-int-) | Thêm một Tab vào tập hợp. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Thêm một Tab vào tập hợp. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ số đã chỉ định của tập hợp. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem hai thể hiện TabsEx có bằng nhau không. |
| [iterator()](#iterator--) | Trả về một enumerator để lặp lại qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ tập hợp. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ tập hợp vào mảng đã chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị chỉ ra liệu việc truy cập vào tập hợp có được đồng bộ (an toàn với luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ. |
### size() {#size--}
```
public final int size()
```


Lấy số phần tử thực tế có trong tập hợp. int chỉ đọc.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```


Lấy phần tử tại chỉ số đã chỉ định. Chỉ đọc [Tab](../../com.aspose.slides/tab).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```


Thêm một Tab vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Trả về:**
[ITab](../../com.aspose.slides/itab) - Tab đã thêm.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```


Thêm một Tab vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Đối tượng Tab sẽ được thêm vào cuối tập hợp. |

**Trả về:**
int - Chỉ mục mà Tab được thêm vào.
### clear() {#clear--}
```
public final void clear()
```


Xóa tất cả các phần tử khỏi tập hợp.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Xóa phần tử tại chỉ số đã chỉ định của tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên không của phần tử sẽ bị xóa. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent_Immediate. IDOMObject chỉ đọc.

**Trả về:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Xác định xem hai thể hiện TabsEx có bằng nhau không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | TabsEx sẽ so sánh với TabsEx hiện tại. |

**Trả về:**
boolean - **true** nếu TabsEx được chỉ định bằng với TabsEx hiện tại; ngược lại, **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```


Trả về một enumerator để lặp lại qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Một IGenericEnumerator có thể được dùng để lặp lại qua tập hợp.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```


Trả về một java iterator cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Một java.util.Iterator cho toàn bộ tập hợp.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Sao chép tất cả các phần tử từ tập hợp vào mảng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Trả về giá trị chỉ ra liệu việc truy cập vào tập hợp có được đồng bộ (an toàn với luồng) hay không. boolean chỉ đọc.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về gốc đồng bộ. Object chỉ đọc.

**Trả về:**
java.lang.Object