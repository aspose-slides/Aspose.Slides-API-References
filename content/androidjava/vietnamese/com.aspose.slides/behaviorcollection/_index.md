---
title: BehaviorCollection
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho bộ sưu tập các hiệu ứng hành vi.
type: docs
url: /vi/com.aspose.slides/behaviorcollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Đại diện cho bộ sưu tập các hiệu ứng hành vi.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCount()](#getCount--) | Trả về số lượng hành vi trong bộ sưu tập. |
| [isReadOnly()](#isReadOnly--) | Lấy giá trị cho biết liệu [IGenericCollection](../../com.aspose.slides/igenericcollection) có ở chế độ chỉ đọc hay không. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Thêm hành vi mới vào bộ sưu tập. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Xác định chỉ mục của một mục cụ thể trong List. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Chèn hành vi mới vào bộ sưu tập tại chỉ mục được chỉ định. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Sao chép các phần tử của [IGenericCollection](../../com.aspose.slides/igenericcollection) vào một Mảng, bắt đầu tại một chỉ mục Mảng cụ thể. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Xóa hành vi được chỉ định khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa hành vi khỏi bộ sưu tập tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các hành vi khỏi bộ sưu tập. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa giá trị cụ thể hay không. |
| [get_Item(int index)](#get-Item-int-) | Trả về một hành vi tại chỉ mục được chỉ định. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Đặt một hành vi tại chỉ mục được chỉ định. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ bộ sưu tập. |
### getCount() {#getCount--}
```
public final int getCount()
```


Trả về số lượng hành vi trong bộ sưu tập. int chỉ đọc.

**Trả về:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Lấy giá trị cho biết liệu [IGenericCollection](../../com.aspose.slides/igenericcollection) có ở chế độ chỉ đọc hay không. boolean chỉ đọc.

**Trả về:**
boolean - true nếu [IGenericCollection](../../com.aspose.slides/igenericcollection) ở chế độ chỉ đọc; ngược lại, false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```


Thêm hành vi mới vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Hành vi cần thêm. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```


Xác định chỉ mục của một mục cụ thể trong List.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Đối tượng cần tìm trong List. |

**Trả về:**
int - Chỉ mục của mục nếu tìm thấy trong danh sách; nếu không, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```


Chèn hành vi mới vào bộ sưu tập tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục nơi hành vi mới sẽ được chèn. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Hành vi cần chèn. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```


Sao chép các phần tử của [IGenericCollection](../../com.aspose.slides/igenericcollection) vào một Mảng, bắt đầu tại một chỉ mục Mảng cụ thể.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Mảng một chiều là đích đến của các phần tử được sao chép từ [IGenericCollection](../../com.aspose.slides/igenericcollection). Mảng phải có chỉ mục bắt đầu từ 0. |
| arrayIndex | int | Chỉ mục bắt đầu từ 0 trong mảng tại vị trí sao chép bắt đầu. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```


Xóa hành vi được chỉ định khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Hành vi cần xóa. |

**Trả về:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Xóa hành vi khỏi bộ sưu tập tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của hành vi cần xóa. |

### clear() {#clear--}
```
public final void clear()
```


Xóa tất cả các hành vi khỏi bộ sưu tập.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```


Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa giá trị cụ thể hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Đối tượng cần tìm trong [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Trả về:**
boolean - true nếu mục được tìm thấy trong [IGenericCollection](../../com.aspose.slides/igenericcollection); nếu không, false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```


Trả về một hành vi tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của hành vi cần trả về. |

**Trả về:**
[IBehavior](../../com.aspose.slides/ibehavior) - Hành vi hoạt ảnh.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```


Đặt một hành vi tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của hành vi cần trả về. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```


Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```


Trả về một iterator java cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Một java.util.Iterator cho toàn bộ bộ sưu tập.