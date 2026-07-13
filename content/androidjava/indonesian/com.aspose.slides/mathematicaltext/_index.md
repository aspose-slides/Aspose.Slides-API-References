---
title: MathematicalText
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Teks matematika
type: docs
url: /id/com.aspose.slides/mathematicaltext/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Teks Matematika

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Konstruktor default (buat String.Empty Value) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Buat MathText dengan satu simbol |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Buat MathematicalText dari teks |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Buat MathematicalText dari teks dan pengaturan format |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getValue()](#getValue--) | Nilai teks |
| [setValue(String value)](#setValue-java.lang.String-) | Nilai teks |
| [getFormat()](#getFormat--) | Properti pemformatan teks |
| [getChildren()](#getChildren--) | Dapatkan elemen anak |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


Konstruktor default (buat String.Empty Value)

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


Buat MathText dengan satu simbol

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathSymbol | char | satu simbol |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


Buat MathematicalText dari teks

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | java.lang.String | nilai teks |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


Buat MathematicalText dari teks dan pengaturan format

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | java.lang.String | nilai teks |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | pengaturan format teks |

### getValue() {#getValue--}
```
public final String getValue()
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
public final void setValue(String value)
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
public final IPortionFormat getFormat()
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
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Dapatkan elemen anak

**Mengembalikan:**
com.aspose.slides.IMathElement[]