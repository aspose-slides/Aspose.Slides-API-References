---
title: IMathParagraphFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Memungkinkan untuk membuat paragraf matematika
type: docs
url: /id/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

Memungkinkan untuk membuat paragraf matematika

--------------------

Untuk kompatibilitas COM
## Metode

| Method | Description |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Membuat paragraf matematika kosong |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Membuat paragraf matematika dan menempatkan blok matematika yang ditentukan di dalamnya |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```

Membuat paragraf matematika kosong

**Mengembalikan:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - paragraf matematika baru
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

Membuat paragraf matematika dan menempatkan blok matematika yang ditentukan di dalamnya

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | blok matematika untuk ditempatkan dalam paragraf |

**Mengembalikan:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - paragraf matematika baru