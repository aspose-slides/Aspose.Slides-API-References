---
title: IMathParagraphFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math paragraph
type: docs
url: /ar/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

يسمح بإنشاء فقرة رياضية

--------------------

للتوافق مع COM
## Methods

| Method | Description |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Create empty math paragraph |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Creates a math paragraph and places the specified math block in it |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```


إنشاء فقرة رياضية فارغة

**Returns:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - new math paragraph
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


إنشاء فقرة رياضية ووضع الكتلة الرياضية المحددة فيها

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | math block to place in the paragraph |

**Returns:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - new math paragraph