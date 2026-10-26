---
title: MathParagraphFactory
second_title: Referensi API Java Aspose.Slides untuk Android
description: Memungkinkan membuat paragraf matematika
type: docs
url: /id/com.aspose.slides/mathparagraphfactory/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

Memungkinkan membuat paragraf matematika

--------------------

Untuk kompatibilitas COM
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Buat paragraf matematika kosong |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Membuat paragraf matematika dan menempatkan blok matematika yang ditentukan di dalamnya |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```


### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```


Buat paragraf matematika kosong

**Mengembalikan:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - paragraf matematika baru
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Membuat paragraf matematika dan menempatkan blok matematika yang ditentukan di dalamnya

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | blok matematika untuk ditempatkan di paragraf |

**Mengembalikan:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - paragraf matematika baru