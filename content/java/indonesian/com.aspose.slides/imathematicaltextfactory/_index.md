---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /id/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Memungkinkan membuat elemen MathematicalText

--------------------

Untuk kompatibilitas COM
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


Buat elemen MathematicalText kosong

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - baru Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


Buat elemen MathematicalText dengan nilai yang ditentukan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathSymbol | char | simbol tunggal untuk digunakan sebagai nilai teks |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - baru Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


Buat elemen MathematicalText kosong dengan nilai yang ditentukan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | java.lang.String | nilai teks |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - baru Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Buat elemen MathematicalText kosong dengan nilai yang ditentukan dan properti pemformatan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | java.lang.String | nilai teks |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | pengaturan format teks |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - baru Mathematical Text