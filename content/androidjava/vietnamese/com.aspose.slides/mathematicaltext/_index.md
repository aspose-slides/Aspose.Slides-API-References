---
title: MathematicalText
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Văn bản toán học
type: docs
url: /vi/com.aspose.slides/mathematicaltext/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Văn bản toán học

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Hàm tạo mặc định (tạo giá trị String.Empty) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Tạo MathText với một ký hiệu đơn |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Tạo MathematicalText từ văn bản |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Tạo MathematicalText từ văn bản và cài đặt định dạng |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getValue()](#getValue--) | Giá trị văn bản |
| [setValue(String value)](#setValue-java.lang.String-) | Giá trị văn bản |
| [getFormat()](#getFormat--) | Các thuộc tính định dạng văn bản |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


Hàm tạo mặc định (tạo giá trị String.Empty)

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText();
> ```

### MathematicalText(char mathSymbol) {#MathematicalText-char-}
```
public MathematicalText(char mathSymbol)
```


Tạo MathText với một ký hiệu đơn

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathSymbol | char | ký hiệu đơn |
### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


Tạo MathematicalText từ văn bản

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathText | java.lang.String | giá trị văn bản |
### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


Tạo MathematicalText từ văn bản và cài đặt định dạng

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathText | java.lang.String | giá trị văn bản |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | cài đặt định dạng văn bản |
### getValue() {#getValue--}
```
public final String getValue()
```


Giá trị văn bản

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Trả về:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Giá trị văn bản

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


Các thuộc tính định dạng văn bản

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Trả về:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Lấy các phần tử con

**Trả về:**
com.aspose.slides.IMathElement[]