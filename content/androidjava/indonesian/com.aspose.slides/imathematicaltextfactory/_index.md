---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /id/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Memungkinkan pembuatan elemen MathematicalText

--------------------

Untuk kompatibilitas COM
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Membuat elemen teks matematis kosong |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Membuat elemen teks matematis dengan nilai yang ditentukan |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Membuat elemen teks matematis kosong dengan nilai yang ditentukan |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Membuat elemen teks matematis kosong dengan nilai yang ditentukan dan properti pemformatan |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


Membuat elemen teks matematis kosong

**Mengembalikan:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - Mathematical Text baru
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


Membuat elemen teks matematis dengan nilai yang ditentukan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathSymbol | char | simbol tunggal yang digunakan sebagai nilai teks |

**Mengembalikan:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - Mathematical Text baru
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


Membuat elemen teks matematis kosong dengan nilai yang ditentukan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | java.lang.String | nilai teks |

**Mengembalikan:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - Mathematical Text baru
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Membuat elemen teks matematis kosong dengan nilai yang ditentukan dan properti pemformatan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathText | java.lang.String | nilai teks |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | pengaturan format teks |

**Mengembalikan:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - Mathematical Text baru