---
title: TagCollection
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Biểu diễn bộ sưu tập các thẻ là các cặp chuỗi do người dùng định nghĩa
type: docs
url: /vi/com.aspose.slides/tagcollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện được thực hiện:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Biểu diễn bộ sưu tập các thẻ (cặp chuỗi do người dùng định nghĩa)

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Trả về số lượng thẻ trong bộ sưu tập. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Thêm một thẻ mới vào bộ sưu tập. |
| [remove(String name)](#remove-java.lang.String-) | Xoá thẻ có tên được chỉ định khỏi bộ sưu tập. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Trả về chỉ mục bắt đầu từ 0 của khóa được chỉ định trong bộ sưu tập. |
| [contains(String name)](#contains-java.lang.String-) | Xác định bộ sưu tập có chứa một tên cụ thể hay không. |
| [removeAt(int index)](#removeAt-int-) | Xoá thẻ tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xoá tất cả các thẻ khỏi bộ sưu tập. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Trả về giá trị của thẻ tại chỉ mục được chỉ định. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Trả về khóa của thẻ tại chỉ mục được chỉ định. |
| [getNamesOfTags()](#getNamesOfTags--) | Trả về tên của các thẻ. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Trả về hoặc thiết lập một cặp khóa và giá trị của thẻ. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Trả về hoặc thiết lập một cặp khóa và giá trị của thẻ. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về một giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một gốc đồng bộ. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
### size() {#size--}
```
public final int size()
```

Trả về số lượng thẻ trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

Thêm một thẻ mới vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thẻ. |
| value | java.lang.String | Giá trị của thẻ. |

**Trả về:**
int - Chỉ mục của thẻ được thêm.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Xoá thẻ có tên được chỉ định khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thẻ cần xoá. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

Trả về chỉ mục bắt đầu từ 0 của khóa được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên để tìm trong bộ sưu tập. |

**Trả về:**
int - Chỉ mục bắt đầu từ 0 của khóa, nếu khóa được tìm thấy trong bộ sưu tập; nếu không, -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

Xác định bộ sưu tập có chứa một tên cụ thể hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Khóa để tìm. |

**Trả về:**
boolean - Đúng nếu bộ sưu tập chứa một thẻ có khóa được chỉ định; nếu không, sai.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xoá thẻ tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của thẻ cần xoá. |
### clear() {#clear--}
```
public final void clear()
```

Xoá tất cả các thẻ khỏi bộ sưu tập.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

Trả về giá trị của thẻ tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của thẻ cần trả về. |

**Trả về:**
java.lang.String - Giá trị của thẻ.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

Trả về khóa của thẻ tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của thẻ cần trả về. |

**Trả về:**
java.lang.String - Khóa của thẻ.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

Trả về tên của các thẻ.

**Trả về:**
java.lang.String[] - Tên của các thẻ.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Trả về hoặc thiết lập một cặp khóa và giá trị của thẻ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Khóa của thẻ. |

**Trả về:**
java.lang.String - Giá trị của thẻ.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Trả về hoặc thiết lập một cặp khóa và giá trị của thẻ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Khóa của thẻ. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng để điền. |
| index | int | Vị trí bắt đầu trong mảng đích. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về một giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (thread-safe) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một gốc đồng bộ. Chỉ đọc Object.

**Trả về:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.