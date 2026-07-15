---
title: MathAccentFactory
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Cho phép tạo một dấu nhấn toán học
type: docs
url: /vi/com.aspose.slides/mathaccentfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện đã triển khai:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Cho phép tạo một dấu nhấn toán học

--------------------

Để tương thích COM
## Các hàm khởi tạo

| Constructor | Description |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Các phương thức

| Method | Description |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học được chỉ định với giá trị ký tự dấu nhấn mặc định |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học được chỉ định |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học được chỉ định với giá trị ký tự dấu nhấn mặc định

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng dấu nhấn |

**Giá trị trả về:**
[IMathAccent](../../com.aspose.slides/imathaccent) - dấu nhấn toán học mới
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Tạo một dấu nhấn toán học áp dụng cho một phần tử toán học được chỉ định

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng dấu nhấn |
| accentCharacter | char | ký tự dấu nhấn |

**Giá trị trả về:**
[IMathAccent](../../com.aspose.slides/imathaccent) - dấu nhấn toán học mới