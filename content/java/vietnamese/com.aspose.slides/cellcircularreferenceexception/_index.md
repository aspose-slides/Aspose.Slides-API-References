---
title: CellCircularReferenceException
second_title: Tham chiếu API Aspose.Slides cho Java
description: Ngoại lệ được ném ra khi một hoặc nhiều tham chiếu vòng tròn được phát hiện, trong đó công thức tham chiếu tới ô của chính nó một cách trực tiếp hoặc gián tiếp.
type: docs
url: /vi/com.aspose.slides/cellcircularreferenceexception/
---
**Kế thừa:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

Ngoại lệ được ném ra khi một hoặc nhiều tham chiếu vòng tròn được phát hiện, trong đó công thức tham chiếu tới ô của chính nó trực tiếp hoặc gián tiếp.
## Các hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Khởi tạo một thể hiện mới của lớp [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception). |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Khởi tạo một thể hiện mới của lớp [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) với thông báo lỗi được chỉ định. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Khởi tạo một thể hiện mới của lớp [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) với thông báo lỗi được chỉ định và một tham chiếu tới ngoại lệ nội bộ là nguyên nhân của ngoại lệ này. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Khởi tạo một thể hiện mới của lớp [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) với thông báo lỗi được chỉ định và tham chiếu ô vòng tròn. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getReference()](#getReference--) | Lấy một tham chiếu ô vòng tròn. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

Khởi tạo một thể hiện mới của lớp [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception).

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

Khởi tạo một thể hiện mới của lớp [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) với thông báo lỗi được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| message | java.lang.String | Một chuỗi mô tả lỗi. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

Khởi tạo một thể hiện mới của lớp [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) với thông báo lỗi được chỉ định và một tham chiếu tới ngoại lệ nội bộ là nguyên nhân của ngoại lệ này.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| message | java.lang.String | Một chuỗi mô tả lỗi. |
| innerException | java.lang.RuntimeException | Ngoại lệ là nguyên nhân của ngoại lệ hiện tại. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Khởi tạo một thể hiện mới của lớp [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) với thông báo lỗi được chỉ định và tham chiếu ô vòng tròn.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| message | java.lang.String | Một chuỗi mô tả lỗi. |
| reference | java.lang.String | Một tham chiếu ô vòng tròn. |

### getReference() {#getReference--}
```
public final String getReference()
```

Lấy một tham chiếu ô vòng tròn.

**Trả về:**
java.lang.String