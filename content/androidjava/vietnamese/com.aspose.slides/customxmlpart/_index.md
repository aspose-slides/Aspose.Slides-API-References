---
title: CustomXmlPart
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho phần xml tùy chỉnh.
type: docs
url: /vi/com.aspose.slides/customxmlpart/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Đại diện cho phần xml tùy chỉnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getXmlData()](#getXmlData--) | Trả về hoặc đặt dữ liệu xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Trả về hoặc đặt dữ liệu xml. |
| [getXmlAsString()](#getXmlAsString--) | Trả về hoặc đặt dữ liệu xml dưới dạng chuỗi UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Trả về hoặc đặt dữ liệu xml dưới dạng chuỗi UTF-8. |
| [getItemId()](#getItemId--) | Xác định một định danh duy nhất toàn cầu (GUID) xác định duy nhất một phần XML tùy chỉnh trong tài liệu Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Xác định một định danh duy nhất toàn cầu (GUID) xác định duy nhất một phần XML tùy chỉnh trong tài liệu Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Trả về tập hợp các sơ đồ XML được liên kết với phần XML tùy chỉnh. |
| [remove()](#remove--) | Xóa phần xml tùy chỉnh khỏi bản trình chiếu. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


Trả về hoặc đặt dữ liệu xml. Đọc/ghi byte[].

**Trả về:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


Trả về hoặc đặt dữ liệu xml. Đọc/ghi byte[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


Trả về hoặc đặt dữ liệu xml dưới dạng chuỗi UTF-8. Đọc/ghi String.

**Trả về:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


Trả về hoặc đặt dữ liệu xml dưới dạng chuỗi UTF-8. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


Xác định một định danh duy nhất toàn cầu (GUID) xác định duy nhất một phần XML tùy chỉnh trong tài liệu Office Open XML. Chỉ đọc java.util.UUID.

**Trả về:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


Xác định một định danh duy nhất toàn cầu (GUID) xác định duy nhất một phần XML tùy chỉnh trong tài liệu Office Open XML. Chỉ đọc java.util.UUID.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


Trả về tập hợp các sơ đồ XML được liên kết với phần XML tùy chỉnh. Chỉ đọc String[].

**Trả về:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


Xóa phần xml tùy chỉnh khỏi bản trình chiếu.