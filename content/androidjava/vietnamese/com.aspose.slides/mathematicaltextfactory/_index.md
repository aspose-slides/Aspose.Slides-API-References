---
title: MathematicalTextFactory
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Cho phép tạo một phần tử MathematicalText
type: docs
url: /vi/com.aspose.slides/mathematicaltextfactory/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)  
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

Cho phép tạo một phần tử MathematicalText

--------------------

Đối với tính tương thích COM
## Constructors

| Constructor | Description |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Tạo phần tử MathematicalText trống |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Tạo phần tử MathematicalText với giá trị đã chỉ định |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Tạo phần tử MathematicalText trống với giá trị đã chỉ định |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Tạo phần tử MathematicalText trống với giá trị đã chỉ định và thuộc tính định dạng |

### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```

### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```

Tạo phần tử MathematicalText trống

**Returns:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - đối tượng **Mathematical Text** mới

### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```

Tạo phần tử MathematicalText với giá trị đã chỉ định

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char | ký hiệu đơn để dùng làm giá trị văn bản |

**Returns:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - đối tượng **Mathematical Text** mới

### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```

Tạo phần tử MathematicalText trống với giá trị đã chỉ định

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | giá trị văn bản |

**Returns:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - đối tượng **Mathematical Text** mới

### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Tạo phần tử MathematicalText trống với giá trị đã chỉ định và thuộc tính định dạng

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | giá trị văn bản |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | cài đặt định dạng văn bản |

**Returns:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - đối tượng **Mathematical Text** mới