---
title: CellInvalidFormulaException
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Ngoại lệ được ném khi công thức tính toán không đúng hoặc không được phân tích cú pháp.
type: docs
url: /vi/com.aspose.slides/cellinvalidformulaexception/
---
**Kế thừa:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

Ngoại lệ được ném khi công thức tính toán không đúng hoặc không được phân tích cú pháp.
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Khởi tạo một thể hiện mới của lớp [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception). |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Khởi tạo một thể hiện mới của lớp [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) với thông báo lỗi được chỉ định. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Khởi tạo một thể hiện mới của lớp [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) với thông báo lỗi được chỉ định và một tham chiếu đến ngoại lệ nội bộ là nguyên nhân của ngoại lệ này. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Khởi tạo một thể hiện mới của lớp [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) với thông báo lỗi được chỉ định và một tham chiếu ô chứa công thức không hợp lệ. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getReference()](#getReference--) | Lấy một tham chiếu ô chứa công thức không hợp lệ. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

Khởi tạo một thể hiện mới của lớp [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception).

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

Khởi tạo một thể hiện mới của lớp [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) với thông báo lỗi được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| message | java.lang.String | Một chuỗi mô tả lỗi. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

Khởi tạo một thể hiện mới của lớp [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) với thông báo lỗi được chỉ định và một tham chiếu đến ngoại lệ nội bộ là nguyên nhân của ngoại lệ này.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| message | java.lang.String | Một chuỗi mô tả lỗi. |
| innerException | java.lang.RuntimeException | Ngoại lệ là nguyên nhân của ngoại lệ hiện tại. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

Khởi tạo một thể hiện mới của lớp [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) với thông báo lỗi được chỉ định và một tham chiếu ô chứa công thức không hợp lệ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| message | java.lang.String | Một chuỗi mô tả lỗi. |
| reference | java.lang.String | Một chuỗi mô tả một tham chiếu đến ngoại lệ nội bộ |

### getReference() {#getReference--}
```
public final String getReference()
```

Lấy một tham chiếu ô chứa công thức không hợp lệ.

**Giá trị trả về:**
java.lang.String