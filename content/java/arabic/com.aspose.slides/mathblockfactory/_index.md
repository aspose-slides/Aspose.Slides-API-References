---
title: MathBlockFactory
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يسمح بإنشاء كتلة رياضية
type: docs
url: /ar/com.aspose.slides/mathblockfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفَّذة:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

السماح بإنشاء كتلة رياضية

--------------------

للتوافق مع COM
## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | إنشاء كتلة رياضية |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | إنشاء كتلة رياضية ووضع العنصر فيها |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | إنشاء كتلة رياضية ووضع العناصر فيها |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


إنشاء كتلة رياضية

**الإرجاع:**
[IMathBlock](../../com.aspose.slides/imathblock) - new math block
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```


إنشاء كتلة رياضية ووضع العنصر فيها

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي |

**الإرجاع:**
[IMathBlock](../../com.aspose.slides/imathblock) - new math block
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


إنشاء كتلة رياضية ووضع العناصر فيها

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | عناصر رياضية |

**الإرجاع:**
[IMathBlock](../../com.aspose.slides/imathblock) - new math block