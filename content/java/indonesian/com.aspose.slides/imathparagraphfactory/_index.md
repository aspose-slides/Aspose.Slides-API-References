---
title: IMathParagraphFactory
second_title: Aspose.Slides for Java API Reference
description: Memungkinkan membuat paragraf matematika
type: docs
url: /id/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

Memungkinkan membuat paragraf matematika

--------------------

Untuk kompatibilitas COM
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Buat paragraf matematika kosong |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Membuat paragraf matematika dan menempatkan blok matematika yang ditentukan di dalamnya |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```


Buat paragraf matematika kosong

**Mengembalikan:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - paragraf matematika baru
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Membuat paragraf matematika dan menempatkan blok matematika yang ditentukan di dalamnya

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | blok matematika untuk ditempatkan dalam paragraf |

**Mengembalikan:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - paragraf matematika baru