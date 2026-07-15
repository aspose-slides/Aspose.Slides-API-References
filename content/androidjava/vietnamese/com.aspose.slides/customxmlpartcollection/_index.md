---
title: CustomXmlPartCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn tập hợp các phần xml tùy chỉnh.
type: docs
url: /vi/com.aspose.slides/customxmlpartcollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Biểu diễn tập hợp các phần xml tùy chỉnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về phần tử tại chỉ mục được chỉ định. |
| [size()](#size--) | Trả về số lượng các phần xml tùy chỉnh trong tập hợp. |
| [add(String xmlString)](#add-java.lang.String-) | Thêm phần xml tùy chỉnh mới. |
| [add(byte[] xmlData)](#add-byte---) | Thêm phần xml tùy chỉnh mới. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Thêm phần xml tùy chỉnh mới. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần xml tùy chỉnh tại chỉ mục được chỉ định. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi tập hợp. |
| [clear()](#clear--) | Xóa tất cả các mục khỏi tập hợp. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào tập hợp có được đồng bộ (an toàn đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ hoá. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ tập hợp. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```


Trả về phần tử tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần lấy. |

**Trả về:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Phần tử tại chỉ mục được chỉ định.
### size() {#size--}
```
public final int size()
```


Trả về số lượng các phần xml tùy chỉnh trong tập hợp. int chỉ đọc.

**Trả về:**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```


Thêm phần xml tùy chỉnh mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xmlString | java.lang.String | Chuỗi xml của phần mới cần thêm. |

**Trả về:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Phần xml tùy chỉnh đã tạo.
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```


Thêm phần xml tùy chỉnh mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xmlData | byte[] | Dữ liệu xml của phần mới cần thêm. |

**Trả về:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Phần xml tùy chỉnh đã tạo.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```


Thêm phần xml tùy chỉnh mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| inputStream | java.io.InputStream | Luồng đầu vào chứa dữ liệu xml của phần mới cần thêm. |

**Trả về:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Phần xml tùy chỉnh đã tạo.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Xóa phần xml tùy chỉnh tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần xóa. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```


Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Phần xml tùy chỉnh cần xóa. |

**Trả về:**
boolean - true nếu mục được xóa thành công; ngược lại, false.
### clear() {#clear--}
```
public final void clear()
```


Xóa tất cả các mục khỏi tập hợp.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Sao chép vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng để sao chép vào. |
| index | int | Chỉ mục bắt đầu sao chép. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Trả về giá trị cho biết việc truy cập vào tập hợp có được đồng bộ (an toàn đa luồng) hay không. boolean chỉ đọc.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về gốc đồng bộ hoá. Object chỉ đọc.

**Trả về:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```


Trả về một enumerator duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```


Trả về một java iterator cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - An java.util.Iterator for the entire collection.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent_Immediate. IDOMObject chỉ đọc.

**Trả về:**
com.aspose.slides.IDOMObject