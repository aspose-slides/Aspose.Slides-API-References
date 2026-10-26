---
title: MathAccentFactory
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cho phép tạo một dấu nhấn toán học
type: docs
url: /vi/com.aspose.slides/mathaccentfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
``` 
public class MathAccentFactory implements IMathAccentFactory
```

Cho phép tạo một dấu nhấn toán học

--------------------

Để tương thích COM
## Các phương thức khởi tạo

| Phương thức khởi tạo | Mô tả |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học cụ thể với giá trị ký tự dấu nhấn mặc định |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học cụ thể |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```

### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```

Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học cụ thể với giá trị ký tự dấu nhấn mặc định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng dấu nhấn |

**Trả về:**
[IMathAccent](../../com.aspose.slides/imathaccent) - dấu nhấn mới
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học cụ thể

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng dấu nhấn |
| accentCharacter | char | ký tự dấu nhấn |

**Trả về:**
[IMathAccent](../../com.aspose.slides/imathaccent) - dấu nhấn mới