---
title: IMathBlockFactory
second_title: مرجع API لـ Aspose.Slides للـ Java
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

| Method | Description |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | إنشاء كتلة رياضية |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | إنشاء كتلة رياضية ووضع العنصر فيها |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | إنشاء كتلة رياضية ووضع العناصر فيها |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

إنشاء كتلة رياضية

**القيمة المرجعة:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة رياضية جديدة
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

إنشاء كتلة رياضية ووضع العنصر فيها

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي |

**القيمة المرجعة:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة رياضية جديدة
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

إنشاء كتلة رياضية ووضع العناصر فيها

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | عناصر رياضية |

**القيمة المرجعة:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة رياضية جديدة