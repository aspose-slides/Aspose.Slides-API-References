---
title: MathematicalTextFactory
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cho phép tạo một phần tử MathematicalText
type: docs
url: /vi/com.aspose.slides/mathematicaltextfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

Cho phép tạo một phần tử MathematicalText

--------------------

Để tương thích COM
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Tạo phần tử mathematical text rỗng |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Tạo phần tử mathematical text với giá trị đã chỉ định |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Tạo phần tử mathematical text rỗng với giá trị đã chỉ định |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Tạo phần tử mathematical text rỗng với giá trị đã chỉ định và các thuộc tính định dạng |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```

### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```

Tạo phần tử mathematical text rỗng

**Kết quả trả về:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - Mathematical Text mới
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```

Tạo phần tử mathematical text với giá trị đã chỉ định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathSymbol | char | ký hiệu đơn để sử dụng làm giá trị văn bản |

**Kết quả trả về:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - Mathematical Text mới
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```

Tạo phần tử mathematical text rỗng với giá trị đã chỉ định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathText | java.lang.String | giá trị văn bản |

**Kết quả trả về:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - Mathematical Text mới
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Tạo phần tử mathematical text rỗng với giá trị đã chỉ định và các thuộc tính định dạng

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathText | java.lang.String | giá trị văn bản |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | cài đặt định dạng văn bản |

**Kết quả trả về:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - Mathematical Text mới