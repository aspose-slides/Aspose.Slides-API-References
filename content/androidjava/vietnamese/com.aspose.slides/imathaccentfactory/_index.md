---
title: IMathAccentFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo một dấu accent toán học
type: docs
url: /vi/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Cho phép tạo một dấu accent toán học

--------------------

Đối với khả năng tương thích COM
## Methods

| Phương thức | Mô tả |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Tạo một dấu accent toán học áp dụng cho một phần tử toán học được chỉ định với giá trị ký tự accent mặc định |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Tạo một dấu accent toán học áp dụng cho một phần tử toán học được chỉ định |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```


Tạo một dấu accent toán học áp dụng cho một phần tử toán học được chỉ định với giá trị ký tự accent mặc định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng dấu accent |

**Giá trị trả về:**
[IMathAccent](../../com.aspose.slides/imathaccent) - dấu accent toán học mới
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Tạo một dấu accent toán học áp dụng cho một phần tử toán học được chỉ định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | phần tử toán học để áp dụng dấu accent |
| accentCharacter | char | ký tự accent |

**Giá trị trả về:**
[IMathAccent](../../com.aspose.slides/imathaccent) - dấu accent toán học mới