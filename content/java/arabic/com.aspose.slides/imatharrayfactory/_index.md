---
title: IMathArrayFactory
second_title: Aspose.Slides for Java API Reference
description: يسمح بإنشاء مصفوفة رياضية
type: docs
url: /ar/com.aspose.slides/imatharrayfactory/
---```
public interface IMathArrayFactory
```

يسمح بإنشاء مصفوفة رياضية

للتوافق مع COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | ينشئ مصفوفة رياضية ويضع العنصر المحدد فيها |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | ينشئ مصفوفة رياضية ويضع العناصر المحددة فيها |
### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```


ينشئ مصفوفة رياضية ويضع العنصر المحدد فيها

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الرياضي الذي يوضع في المصفوفة |

**القيمة المرجعة:**
[IMathArray](../../com.aspose.slides/imatharray) - مصفوفة رياضية جديدة
### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathArray createMathArray(IMathElementCollection elements)
```


ينشئ مصفوفة رياضية ويضع العناصر المحددة فيها

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | العناصر الرياضية التي توضع في المصفوفة |

**القيمة المرجعة:**
[IMathArray](../../com.aspose.slides/imatharray) - مصفوفة رياضية جديدة