---
title: MathNaryOperatorFactory
second_title: Aspose.Slides for Android عبر مرجع API Java
description: يسمح بإنشاء IMathNaryOperator
type: docs
url: /ar/com.aspose.slides/mathnaryoperatorfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

يسمح بإنشاء IMathNaryOperator

--------------------

لتوافق COM
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | ينشئ IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```

### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

ينشئ IMathNaryOperator

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| operatorSymbol | char | رمز المشغل |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | الحجة الأساسية لتطبيق المشغل |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأعلى |

**القيمة المرجعة:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - جديد IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

ينشئ IMathNaryOperator

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| operatorSymbol | char | رمز المشغل |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | الحجة الأساسية لتطبيق المشغل |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى |

**القيمة المرجعة:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - جديد IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

ينشئ IMathNaryOperator

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| operatorSymbol | char | رمز المشغل |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | الحجة الأساسية لتطبيق المشغل |

**القيمة المرجعة:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - جديد IMathNaryOperator