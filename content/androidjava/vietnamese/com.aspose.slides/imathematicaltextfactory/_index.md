---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /vi/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Cho phép tạo một phần tử MathematicalText

--------------------

Để tương thích COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Tạo phần tử MathematicalText trống |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Tạo phần tử MathematicalText với giá trị được chỉ định |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Tạo phần tử MathematicalText trống với giá trị được chỉ định |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Tạo phần tử MathematicalText trống với giá trị được chỉ định và các thuộc tính định dạng |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

Tạo phần tử MathematicalText trống

**Trả về:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - Mathematical Text mới
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

Tạo phần tử MathematicalText với giá trị được chỉ định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathSymbol | char | ký hiệu duy nhất để dùng làm giá trị văn bản |

**Trả về:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - Mathematical Text mới
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

Tạo phần tử MathematicalText trống với giá trị được chỉ định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathText | java.lang.String | giá trị văn bản |

**Trả về:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - Mathematical Text mới
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Tạo phần tử MathematicalText trống với giá trị được chỉ định và các thuộc tính định dạng

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathText | java.lang.String | giá trị văn bản |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | cài đặt định dạng văn bản |

**Trả về:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - Mathematical Text mới