---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API Reference
description: Cho phép tạo một phần tử MathematicalText
type: docs
url: /vi/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Cho phép tạo một phần tử MathematicalText

--------------------

Đối với tính tương thích COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Tạo phần tử văn bản toán học rỗng |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Tạo phần tử văn bản toán học với giá trị được chỉ định |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Tạo phần tử văn bản toán học rỗng với giá trị được chỉ định |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Tạo phần tử văn bản toán học rỗng với giá trị và các thuộc tính định dạng được chỉ định |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


Tạo phần tử văn bản toán học rỗng

**Trả về:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


Tạo phần tử văn bản toán học với giá trị được chỉ định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathSymbol | char | single symbol to use as text value |

**Trả về:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


Tạo phần tử văn bản toán học rỗng với giá trị được chỉ định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathText | java.lang.String | text value |

**Trả về:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Tạo phần tử văn bản toán học rỗng với giá trị và các thuộc tính định dạng được chỉ định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathText | java.lang.String | text value |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | text format settings |

**Trả về:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text