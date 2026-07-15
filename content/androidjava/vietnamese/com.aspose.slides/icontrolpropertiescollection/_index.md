---
title: IControlPropertiesCollection
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Một bộ sưu tập các điều khiển ActiveX.
type: docs
url: /vi/com.aspose.slides/icontrolpropertiescollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

Một bộ sưu tập các điều khiển ActiveX.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCount()](#getCount--) | Trả về số lượng thuộc tính trong bộ sưu tập. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Thêm một thuộc tính vào bộ sưu tập. |
| [remove(String name)](#remove-java.lang.String-) | Xóa một thuộc tính có tên được chỉ định. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Trả về hoặc đặt thuộc tính. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Trả về hoặc đặt thuộc tính. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Trả về số lượng thuộc tính trong bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các thuộc tính. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Trả về số lượng thuộc tính trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```


Thêm một thuộc tính vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính. |
| value | java.lang.String | Giá trị của thuộc tính. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Xóa một thuộc tính có tên được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính cần xóa. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Trả về hoặc đặt thuộc tính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính. |

**Trả về:**
java.lang.String - Thuộc tính.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Trả về hoặc đặt thuộc tính.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của thuộc tính. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


Trả về số lượng thuộc tính trong bộ sưu tập. Chỉ đọc [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Trả về:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```


Xóa tất cả các thuộc tính.