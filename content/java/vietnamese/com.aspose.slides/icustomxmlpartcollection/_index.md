---
title: ICustomXmlPartCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn tập hợp các phần xml tùy chỉnh.
type: docs
url: /vi/com.aspose.slides/icustomxmlpartcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Biểu diễn tập hợp các phần xml tùy chỉnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về phần tử tại chỉ mục đã cho. |
| [add(byte[] xmlData)](#add-byte---) | Thêm phần xml tùy chỉnh mới. |
| [add(String xmlString)](#add-java.lang.String-) | Thêm phần xml tùy chỉnh mới. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Thêm phần xml tùy chỉnh mới. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần xml tùy chỉnh tại chỉ mục đã cho. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể trong tập hợp. |
| [clear()](#clear--) | Xóa tất cả các mục trong tập hợp. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```


Trả về phần tử tại chỉ mục đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần lấy. |

**Trả về:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Phần tử tại chỉ mục đã cho.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```


Thêm phần xml tùy chỉnh mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xmlData | byte[] | Dữ liệu xml của phần mới cần thêm. |

**Trả về:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Phần xml tùy chỉnh đã tạo.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```


Thêm phần xml tùy chỉnh mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xmlString | java.lang.String | Chuỗi xml của phần mới cần thêm. |

**Trả về:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Phần xml tùy chỉnh đã tạo.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```


Thêm phần xml tùy chỉnh mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| inputStream | java.io.InputStream | Luồng inputStream chứa dữ liệu xml của phần mới cần thêm. |

**Trả về:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Phần xml tùy chỉnh đã tạo.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Xóa phần xml tùy chỉnh tại chỉ mục đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần xóa. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```


Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể trong tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Phần xml tùy chỉnh cần xóa. |

**Trả về:**
boolean - true nếu mục được xóa thành công; nếu không, false.
### clear() {#clear--}
```
public abstract void clear()
```


Xóa tất cả các mục trong tập hợp.