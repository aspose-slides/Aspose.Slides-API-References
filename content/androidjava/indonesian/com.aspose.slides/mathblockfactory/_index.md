---
title: MathBlockFactory
second_title: Referensi API Java Aspose.Slides untuk Android
description: Memungkinkan membuat blok matematika
type: docs
url: /id/com.aspose.slides/mathblockfactory/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

Memungkinkan membuat blok matematika

--------------------

Untuk kompatibilitas COM
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Membuat blok matematika |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Membuat blok matematika dan menempatkan elemen di dalamnya |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Membuat blok matematika dan menempatkan elemen-elemen di dalamnya |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


Membuat blok matematika

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - blok matematika baru
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```


Membuat blok matematika dan menempatkan elemen di dalamnya

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Sebuah elemen matematika |

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - blok matematika baru
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Membuat blok matematika dan menempatkan elemen-elemen di dalamnya

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elemen matematika |

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - blok matematika baru