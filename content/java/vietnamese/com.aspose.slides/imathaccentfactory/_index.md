---
title: IMathAccentFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math accent
type: docs
url: /vi/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Cho phép tạo một dấu nhấn toán học

--------------------

Để tương thích với COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học được chỉ định với giá trị ký tự dấu nhấn mặc định |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học được chỉ định |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học được chỉ định với giá trị ký tự dấu nhấn mặc định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng dấu nhấn |

**Giá trị trả về:**
[IMathAccent](../../com.aspose.slides/imathaccent) - dấu nhấn toán học mới
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học được chỉ định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng dấu nhấn |
| accentCharacter | char | ký tự dấu nhấn |

**Giá trị trả về:**
[IMathAccent](../../com.aspose.slides/imathaccent) - dấu nhấn toán học mới