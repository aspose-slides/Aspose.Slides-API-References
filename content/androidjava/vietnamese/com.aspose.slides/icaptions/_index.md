---
title: ICaptions
second_title: Aspose.Slides for Android via Java API Reference
description: Biểu diễn phụ đề đóng WebVTT.
type: docs
url: /vi/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Biểu diễn phụ đề đóng WebVTT.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Trả về định danh duy nhất toàn cầu (GUID) của phụ đề đóng. |
| [getLabel()](#getLabel--) | Trả về hoặc đặt nhãn của phụ đề đóng. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Trả về hoặc đặt nhãn của phụ đề đóng. |
| [getBinaryData()](#getBinaryData--) | Trả về dữ liệu nhị phân của phụ đề đóng. |
| [getDataAsString()](#getDataAsString--) | Trả về dữ liệu phụ đề đóng dưới dạng chuỗi được mã hoá UTF-8, Read-only String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

Trả về định danh duy nhất toàn cầu (GUID) của phụ đề đóng. Chỉ đọc java.util.UUID.

**Trả về:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

Trả về hoặc đặt nhãn của phụ đề đóng. Đọc/ghi String.

**Trả về:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

Trả về hoặc đặt nhãn của phụ đề đóng. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Trả về dữ liệu nhị phân của phụ đề đóng. Chỉ đọc byte[].

**Trả về:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

Trả về dữ liệu phụ đề đóng dưới dạng chuỗi mã hoá UTF-8, Read-only String.

**Trả về:**
java.lang.String