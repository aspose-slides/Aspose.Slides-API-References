---
title: ICustomXmlPartCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho bộ sưu tập các phần xml tùy chỉnh.
type: docs
url: /vi/com.aspose.slides/icustomxmlpartcollection/
---
**Tất cả các giao diện đã triển khai:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Đại diện cho bộ sưu tập các phần xml tùy chỉnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về phần tử tại chỉ số đã chỉ định. |
| [add(byte[] xmlData)](#add-byte---) | Thêm phần xml tùy chỉnh mới. |
| [add(String xmlString)](#add-java.lang.String-) | Thêm phần xml tùy chỉnh mới. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Thêm phần xml tùy chỉnh mới. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần xml tùy chỉnh tại chỉ số đã chỉ định. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các mục khỏi bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Trả về phần tử tại chỉ số đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số dựa trên 0 của phần tử cần lấy. |

**Giá trị trả về:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Phần tử tại chỉ số đã chỉ định.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Thêm phần xml tùy chỉnh mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xmlData | byte[] | Dữ liệu xml của phần mới sẽ được thêm. |

**Giá trị trả về:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Phần xml tùy chỉnh đã tạo.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Thêm phần xml tùy chỉnh mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xmlString | java.lang.String | Chuỗi xml của phần mới sẽ được thêm. |

**Giá trị trả về:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Phần xml tùy chỉnh đã tạo.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

Thêm phần xml tùy chỉnh mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| inputStream | java.io.InputStream | Luồng đầu vào chứa dữ liệu xml của phần mới sẽ được thêm. |

**Giá trị trả về:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Phần xml tùy chỉnh đã tạo.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần xml tùy chỉnh tại chỉ số đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số dựa trên 0 của phần tử cần xóa. |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Phần xml tùy chỉnh cần xóa. |

**Giá trị trả về:**
boolean - true nếu mục được xóa thành công; ngược lại, false.
### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các mục khỏi bộ sưu tập.