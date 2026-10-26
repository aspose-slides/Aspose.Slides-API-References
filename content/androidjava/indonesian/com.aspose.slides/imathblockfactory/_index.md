---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math block
type: docs
url: /id/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Memungkinkan membuat blok matematika

--------------------

Untuk kompatibilitas COM
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Membuat blok matematika |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Membuat blok matematika dan menempatkan elemen di dalamnya |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Membuat blok matematika dan menempatkan elemen-elemen di dalamnya |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```


Membuat blok matematika

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - blok matematika baru
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```


Membuat blok matematika dan menempatkan elemen di dalamnya

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Elemen matematika |

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - blok matematika baru
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Membuat blok matematika dan menempatkan elemen-elemen di dalamnya

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elemen matematika |

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - blok matematika baru