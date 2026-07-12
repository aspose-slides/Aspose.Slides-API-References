---
title: IMathParagraphFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math paragraph
type: docs
url: /tr/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

Bir matematik paragrafı oluşturmanıza olanak tanır

For COM comparibility

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Create empty math paragraph |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Creates a math paragraph and places the specified math block in it |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```

Boş bir matematik paragrafı oluşturur

**Döndürür:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - yeni matematik paragrafı
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

Bir matematik paragrafı oluşturur ve belirtilen matematik bloğunu içine koyar

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | paragrafta yer alacak matematik bloğu |

**Döndürür:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - yeni matematik paragrafı