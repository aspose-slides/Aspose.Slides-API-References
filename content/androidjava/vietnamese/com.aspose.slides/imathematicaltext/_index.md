---
title: IMathematicalText
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Văn bản toán học
type: docs
url: /vi/com.aspose.slides/imathematicaltext/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Văn bản toán học

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  ```

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getValue()](#getValue--) | Giá trị văn bản |
| [setValue(String value)](#setValue-java.lang.String-) | Giá trị văn bản |
| [getFormat()](#getFormat--) | Thuộc tính định dạng văn bản |
### getValue() {#getValue--}
```
public abstract String getValue()
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
public abstract void setValue(String value)
```


Giá trị văn bản

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
>  ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IPortionFormat getFormat()
```


Thuộc tính định dạng văn bản

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Trả về:**
[IPortionFormat](../../com.aspose.slides/iportionformat)