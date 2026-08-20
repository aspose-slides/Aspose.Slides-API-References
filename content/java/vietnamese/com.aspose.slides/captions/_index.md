---
title: Captions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho phụ đề đóng WebVTT.
type: docs
url: /vi/com.aspose.slides/captions/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

Đại diện cho phụ đề đóng WebVTT.
## Phương thức

| Method | Description |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Trả về định danh duy nhất toàn cầu (GUID) của phụ đề đóng. |
| [getLabel()](#getLabel--) | Trả về hoặc đặt nhãn của phụ đề đóng. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Trả về hoặc đặt nhãn của phụ đề đóng. |
| [getBinaryData()](#getBinaryData--) | Trả về dữ liệu nhị phân của phụ đề đóng. |
| [getDataAsString()](#getDataAsString--) | Trả về dữ liệu phụ đề đóng dưới dạng chuỗi mã hoá UTF-8 Chỉ đọc String. |

### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```

Trả về định danh duy nhất toàn cầu (GUID) của phụ đề đóng. Chỉ đọc java.util.UUID.

**Trả về:**
java.util.UUID

### getLabel() {#getLabel--}
```
public final String getLabel()
```

Trả về hoặc đặt nhãn của phụ đề đóng. Đọc/ghi String.

**Trả về:**
java.lang.String

### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```

Trả về hoặc đặt nhãn của phụ đề đóng. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Trả về dữ liệu nhị phân của phụ đề đóng. Chỉ đọc byte[] .

**Trả về:**
byte[]

### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```

Trả về dữ liệu phụ đề đóng dưới dạng chuỗi mã hoá UTF-8 Chỉ đọc String.

**Trả về:**
java.lang.String