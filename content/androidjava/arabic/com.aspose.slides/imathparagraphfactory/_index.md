---
title: IMathParagraphFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math paragraph
type: docs
url: /ar/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

يسمح بإنشاء فقرة رياضية

--------------------

لتوافق COM
## الطرق

| Method | Description |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | إنشاء فقرة رياضية فارغة |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | إنشاء فقرة رياضية ووضع الكتلة الرياضية المحددة فيها |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```

إنشاء فقرة رياضية فارغة

**الإرجاع:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph) - فقرة رياضية جديدة
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

إنشاء فقرة رياضية ووضع الكتلة الرياضية المحددة فيها

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | كتلة رياضية لوضعها في الفقرة |

**الإرجاع:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph) - فقرة رياضية جديدة