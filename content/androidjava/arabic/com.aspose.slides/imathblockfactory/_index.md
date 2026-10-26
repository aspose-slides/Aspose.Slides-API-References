---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: يسمح بإنشاء كتلة رياضية
type: docs
url: /ar/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

يسمح بإنشاء كتلة رياضية

--------------------

للتوافق مع COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | إنشاء كتلة رياضية |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | إنشاء كتلة رياضية ووضع العنصر فيها |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | إنشاء كتلة رياضية ووضع العناصر فيها |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

إنشاء كتلة رياضية

**الإرجاع:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة رياضية جديدة
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

إنشاء كتلة رياضية ووضع العنصر فيها

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي |

**الإرجاع:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة ريالية جديدة
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

إنشاء كتلة رياضية ووضع العناصر فيها

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | عناصر رياضية |

**الإرجاع:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة رياضية جديدة