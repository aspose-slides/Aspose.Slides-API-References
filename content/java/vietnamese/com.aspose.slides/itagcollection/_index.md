---
title: ITagCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho bộ sưu tập các thẻ là các cặp chuỗi do người dùng định nghĩa
type: docs
url: /vi/com.aspose.slides/itagcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Đại diện cho bộ sưu tập các thẻ (cặp chuỗi do người dùng định nghĩa)
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Thêm một thẻ mới vào bộ sưu tập. |
| [remove(String name)](#remove-java.lang.String-) | Xóa thẻ có tên được chỉ định khỏi bộ sưu tập. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Trả về chỉ số bắt đầu từ 0 của khóa được chỉ định trong bộ sưu tập. |
| [contains(String name)](#contains-java.lang.String-) | Xác định xem bộ sưu tập có chứa một tên cụ thể hay không. |
| [removeAt(int index)](#removeAt-int-) | Xóa thẻ tại chỉ số được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các thẻ khỏi bộ sưu tập. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Trả về giá trị của một thẻ tại chỉ số được chỉ định. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Trả về khóa của một thẻ tại chỉ số được chỉ định. |
| [getNamesOfTags()](#getNamesOfTags--) | Trả về tên các thẻ. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Trả về hoặc đặt cặp khóa và giá trị của một thẻ. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Trả về hoặc đặt cặp khóa và giá trị của một thẻ. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

Thêm một thẻ mới vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thẻ. |
| value | java.lang.String | Giá trị của thẻ. |

**Trả về:**
int - Chỉ số của thẻ đã thêm.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Xóa thẻ có tên được chỉ định khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thẻ cần xóa. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

Trả về chỉ số bắt đầu từ 0 của khóa được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên để tìm trong bộ sưu tập. |

**Trả về:**
int - Chỉ số bắt đầu từ 0 của khóa, nếu khóa được tìm thấy trong bộ sưu tập; nếu không, -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

Xác định xem bộ sưu tập có chứa một tên cụ thể hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Khóa để tìm. |

**Trả về:**
boolean - true nếu bộ sưu tập chứa một thẻ với khóa được chỉ định; nếu không, false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa thẻ tại chỉ số được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số bắt đầu từ 0 của thẻ cần xóa. |
### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các thẻ khỏi bộ sưu tập.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

Trả về giá trị của một thẻ tại chỉ số được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của thẻ cần trả về. |

**Trả về:**
java.lang.String - Giá trị của thẻ.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

Trả về khóa của một thẻ tại chỉ số được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của thẻ cần trả về. |

**Trả về:**
java.lang.String - Khóa của thẻ.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

Trả về tên các thẻ.

**Trả về:**
java.lang.String[] - Tên các thẻ.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Trả về hoặc đặt cặp khóa và giá trị của một thẻ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Khóa của thẻ. |

**Trả về:**
java.lang.String - Giá trị của thẻ.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Trả về hoặc đặt cặp khóa và giá trị của một thẻ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Khóa của thẻ. |
| value | java.lang.String |  |