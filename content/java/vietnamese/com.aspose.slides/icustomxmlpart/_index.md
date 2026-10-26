---
title: ICustomXmlPart
second_title: Aspose.Slides for Java API Reference
description: Đại diện cho phần xml tùy chỉnh.
type: docs
url: /vi/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Đại diện cho phần xml tùy chỉnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Trả về hoặc đặt dữ liệu xml dưới dạng chuỗi UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Trả về hoặc đặt dữ liệu xml dưới dạng chuỗi UTF-8. |
| [getXmlData()](#getXmlData--) | Trả về hoặc đặt dữ liệu xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Trả về hoặc đặt dữ liệu xml. |
| [getItemId()](#getItemId--) | Xác định một định danh duy nhất toàn cục (GUID) xác định duy nhất một phần XML tùy chỉnh trong tài liệu Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Xác định một định danh duy nhất toàn cục (GUID) xác định duy nhất một phần XML tùy chỉnh trong tài liệu Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Trả về tập hợp các sơ đồ XML liên quan đến phần XML tùy chỉnh. |
| [remove()](#remove--) | Xóa phần xml tùy chỉnh khỏi bản trình bày. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Trả về hoặc đặt dữ liệu xml dưới dạng chuỗi UTF-8. Đọc/ghi String.

**Trả về:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Trả về hoặc đặt dữ liệu xml dưới dạng chuỗi UTF-8. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Trả về hoặc đặt dữ liệu xml. Đọc/ghi byte[].

**Trả về:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Trả về hoặc đặt dữ liệu xml. Đọc/ghi byte[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Xác định một định danh duy nhất toàn cục (GUID) xác định duy nhất một phần XML tùy chỉnh trong tài liệu Office Open XML. Chỉ đọc java.util.UUID.

**Trả về:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Xác định một định danh duy nhất toàn cục (GUID) xác định duy nhất một phần XML tùy chỉnh trong tài liệu Office Open XML. Chỉ đọc java.util.UUID.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Trả về tập hợp các sơ đồ XML liên quan đến phần XML tùy chỉnh. Chỉ đọc String[].

**Trả về:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Xóa phần xml tùy chỉnh khỏi bản trình bày.