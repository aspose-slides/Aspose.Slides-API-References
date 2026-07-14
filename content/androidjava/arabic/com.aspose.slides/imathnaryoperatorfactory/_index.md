---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create IMathNaryOperator
type: docs
url: /ar/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

يسمح بإنشاء IMathNaryOperator

--------------------

للتوافق مع COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | ينشئ IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

ينشئ IMathNaryOperator

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| operatorSymbol | char | رمز العامل |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | الوسيط الأساسي لتطبيق العامل |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأعلى |

**القيمة المرجعة:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - IMathNaryOperator جديد
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

ينشئ IMathNaryOperator

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| operatorSymbol | char | رمز العامل |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | الوسيط الأساسي لتطبيق العامل |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى |

**القيمة المرجعة:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - IMathNaryOperator جديد
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

ينشئ IMathNaryOperator

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| operatorSymbol | char | رمز العامل |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | الوسيط الأساسي لتطبيق العامل |

**القيمة المرجعة:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - IMathNaryOperator جديد