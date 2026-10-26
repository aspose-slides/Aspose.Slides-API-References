---
title: ControlPropertiesCollection
second_title: Tham khảo API Java cho Aspose.Slides trên Android
description: Một tập hợp các thuộc tính AcitveX.
type: docs
url: /vi/com.aspose.slides/controlpropertiescollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Một tập hợp các thuộc tính AcitveX.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Thêm một thuộc tính vào tập hợp. |
| [remove(String name)](#remove-java.lang.String-) | Xóa một thuộc tính với tên đã chỉ định. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Trả về hoặc thiết lập thuộc tính. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Trả về hoặc thiết lập thuộc tính. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Trả về tập hợp các tên thuộc tính. |
| [clear()](#clear--) | Xóa tất cả các thuộc tính. |
| [getCount()](#getCount--) | Trả về số lượng thuộc tính trong tập hợp. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ tập hợp. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

Thêm một thuộc tính vào tập hợp.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính. |
| value | java.lang.String | Giá trị của thuộc tính. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Xóa một thuộc tính với tên đã chỉ định.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính cần xóa. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Trả về hoặc thiết lập thuộc tính.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính. |

**Trả về:**
java.lang.String - Thuộc tính.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Trả về hoặc thiết lập thuộc tính.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Trả về tập hợp các tên thuộc tính. Chỉ đọc [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Trả về:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các thuộc tính.

### getCount() {#getCount--}
```
public final int getCount()
```

Trả về số lượng thuộc tính trong tập hợp. Chỉ đọc int.

**Trả về:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Trả về một enumerator duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Trả về một java iterator cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.