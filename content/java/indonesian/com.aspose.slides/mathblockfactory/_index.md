---
title: MathBlockFactory
second_title: Referensi API Aspose.Slides untuk Java
description: Mengizinkan membuat blok matematika
type: docs
url: /id/com.aspose.slides/mathblockfactory/
---
**Warisan:**
java.lang.Object

**Semua Interface yang Diimplementasikan:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

Mengizinkan membuat blok matematika

--------------------

Untuk kompatibilitas COM
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Buat blok matematika |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Buat blok matematika dan letakkan elemen di dalamnya |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Buat blok matematika dan letakkan elemen-elemen di dalamnya |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```

### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```

Buat blok matematika

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - blok matematika baru
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```

Buat blok matematika dan letakkan elemen di dalamnya

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Elemen matematika |

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - blok matematika baru
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Buat blok matematika dan letakkan elemen-elemen di dalamnya

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elemen matematika |

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - blok matematika baru