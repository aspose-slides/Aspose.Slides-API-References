---
title: MathAccentFactory
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mengizinkan membuat aksen matematika
type: docs
url: /id/com.aspose.slides/mathaccentfactory/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Mengizinkan membuat aksen matematika

--------------------

Untuk kompatibilitas COM
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Membuat aksen matematika yang diterapkan pada elemen matematika yang ditentukan dengan nilai karakter aksen default |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Membuat aksen matematika yang diterapkan pada elemen matematika yang ditentukan |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


Membuat aksen matematika yang diterapkan pada elemen matematika yang ditentukan dengan nilai karakter aksen default

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemen matematika untuk menerapkan aksen |

**Mengembalikan:**
[IMathAccent](../../com.aspose.slides/imathaccent) - aksen matematika baru
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Membuat aksen matematika yang diterapkan pada elemen matematika yang ditentukan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemen matematika untuk menerapkan aksen |
| accentCharacter | char | karakter aksen |

**Mengembalikan:**
[IMathAccent](../../com.aspose.slides/imathaccent) - aksen matematika baru