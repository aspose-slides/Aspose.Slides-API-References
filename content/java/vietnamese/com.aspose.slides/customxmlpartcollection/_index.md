---
title: CustomXmlPartCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho bộ sưu tập các phần xml tùy chỉnh.
type: docs
url: /vi/com.aspose.slides/customxmlpartcollection/
---
**Kế thừa:**  
java.lang.Object

**Tất cả giao diện được triển khai:**  
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject  
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Đại diện cho bộ sưu tập các phần xml tùy chỉnh.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về phần tử tại chỉ mục đã chỉ định. |
| [size()](#size--) | Trả về số lượng các phần xml tùy chỉnh trong bộ sưu tập. |
| [add(String xmlString)](#add-java.lang.String-) | Thêm phần xml tùy chỉnh mới. |
| [add(byte[] xmlData)](#add-byte---) | Thêm phần xml tùy chỉnh mới. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Thêm phần xml tùy chỉnh mới. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần xml tùy chỉnh tại chỉ mục đã chỉ định. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các mục khỏi bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết liệu việc truy cập vào bộ sưu tập có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một đồng bộ gốc. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Trả về phần tử tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần lấy. |

**Trả về:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Phần tử tại chỉ mục đã chỉ định.

### size() {#size--}
```
public final int size()
```

Trả về số lượng các phần xml tùy chỉnh trong bộ sưu tập. Chỉ đọc int.

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
| inputStream | java.io.InputStream | Luồng nhập với dữ liệu xml của phần mới cần thêm. |

**Trả về:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Phần xml tùy chỉnh đã tạo.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa phần xml tùy chỉnh tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần xóa. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập.

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

Xóa tất cả các mục khỏi bộ sưu tập.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích để sao chép. |
| index | int | Chỉ mục bắt đầu sao chép. |

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

Trả về một đồng bộ gốc. Chỉ đọc Object.

**Trả về:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Một IGenericEnumerator có thể được dùng để duyệt qua bộ sưu tập.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Một java.util.Iterator cho toàn bộ bộ sưu tập.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject