---
title: CellInvalidReferenceException
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Ngoại lệ được ném khi gặp tham chiếu ô không hợp lệ.
type: docs
url: /vi/com.aspose.slides/cellinvalidreferenceexception/
---
**Kế thừa:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

Ngoại lệ được ném khi gặp tham chiếu ô không hợp lệ.
## Hàm khởi tạo

| Constructor | Description |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Khởi tạo một thể hiện mới của lớp [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception). |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Khởi tạo một thể hiện mới của lớp [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) với một thông báo lỗi được chỉ định. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Khởi tạo một thể hiện mới của lớp [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) với một thông báo lỗi được chỉ định và một tham chiếu đến ngoại lệ bên trong là nguyên nhân gây ra ngoại lệ này. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Khởi tạo một thể hiện mới của lớp [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) với một thông báo lỗi được chỉ định và một tham chiếu ô không hợp lệ. |
## Phương thức

| Method | Description |
| --- | --- |
| [getReference()](#getReference--) | Lấy một tham chiếu ô không hợp lệ. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

Khởi tạo một thể hiện mới của lớp [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception).

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

Khởi tạo một thể hiện mới của lớp [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) với một thông báo lỗi được chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Một chuỗi mô tả lỗi. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

Khởi tạo một thể hiện mới của lớp [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) với một thông báo lỗi được chỉ định và một tham chiếu đến ngoại lệ bên trong là nguyên nhân gây ra ngoại lệ này.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Một chuỗi mô tả lỗi. |
| innerException | java.lang.RuntimeException | Ngoại lệ là nguyên nhân gây ra ngoại lệ hiện tại. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

Khởi tạo một thể hiện mới của lớp [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) với một thông báo lỗi được chỉ định và một tham chiếu ô không hợp lệ.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Một chuỗi mô tả lỗi. |
| reference | java.lang.String | Một tham chiếu ô không hợp lệ. |

### getReference() {#getReference--}
```
public final String getReference()
```

Lấy một tham chiếu ô không hợp lệ.

**Trả về:**
java.lang.String