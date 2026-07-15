---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: Biểu diễn phần XML tùy chỉnh.
type: docs
url: /vi/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Biểu diễn phần XML tùy chỉnh.
## Phương thức

| Method | Description |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Trả về hoặc thiết lập dữ liệu xml dưới dạng chuỗi UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Trả về hoặc thiết lập dữ liệu xml dưới dạng chuỗi UTF-8. |
| [getXmlData()](#getXmlData--) | Trả về hoặc thiết lập dữ liệu xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Trả về hoặc thiết lập dữ liệu xml. |
| [getItemId()](#getItemId--) | Chỉ định một định danh toàn cầu duy nhất (GUID) xác định duy nhất một phần XML tùy chỉnh trong tài liệu Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Chỉ định một định danh toàn cầu duy nhất (GUID) xác định duy nhất một phần XML tùy chỉnh trong tài liệu Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Trả về bộ sưu tập các sơ đồ XML được liên kết với phần XML tùy chỉnh. |
| [remove()](#remove--) | Xóa phần XML tùy chỉnh khỏi bản trình bày. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Trả về hoặc thiết lập dữ liệu xml dưới dạng chuỗi UTF-8. Đọc/ghi String.

**Trả về:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Trả về hoặc thiết lập dữ liệu xml dưới dạng chuỗi UTF-8. Đọc/ghi String.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Trả về hoặc thiết lập dữ liệu xml. Đọc/ghi byte[].

**Trả về:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Trả về hoặc thiết lập dữ liệu xml. Đọc/ghi byte[].

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Chỉ định một định danh toàn cầu duy nhất (GUID) xác định duy nhất một phần XML tùy chỉnh trong tài liệu Office Open XML. Chỉ đọc java.util.UUID.

**Trả về:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Chỉ định một định danh toàn cầu duy nhất (GUID) xác định duy nhất một phần XML tùy chỉnh trong tài liệu Office Open XML. Chỉ đọc java.util.UUID.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Trả về bộ sưu tập các sơ đồ XML được liên kết với phần XML tùy chỉnh. Chỉ đọc String[].

**Trả về:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Xóa phần XML tùy chỉnh khỏi bản trình bày.