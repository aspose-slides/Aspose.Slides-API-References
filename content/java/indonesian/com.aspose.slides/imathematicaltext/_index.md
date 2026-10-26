---
title: IMathematicalText
second_title: Referensi API Aspose.Slides untuk Java
description: Teks matematika
type: docs
url: /id/com.aspose.slides/imathematicaltext/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Teks matematika

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getValue()](#getValue--) | Nilai teks |
| [setValue(String value)](#setValue-java.lang.String-) | Nilai teks |
| [getFormat()](#getFormat--) | Properti pemformatan teks |
### getValue() {#getValue--}
```
public abstract String getValue()
```


Nilai teks

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Mengembalikan:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public abstract void setValue(String value)
```


Nilai teks

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IPortionFormat getFormat()
```


Properti pemformatan teks

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Mengembalikan:**
[IPortionFormat](../../com.aspose.slides/iportionformat)