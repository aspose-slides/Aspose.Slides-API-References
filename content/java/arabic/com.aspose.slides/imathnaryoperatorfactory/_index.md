---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create IMathNaryOperator
type: docs
url: /ar/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

يسمح بإنشاء IMathNaryOperator

لتوافق COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

ينشئ IMathNaryOperator

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| operatorSymbol | char | رمز العامل |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | الحجة الأساسية لتطبيق العامل |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأقصى |

**القيمة المرجعة:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - جديد IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

ينشئ IMathNaryOperator

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| operatorSymbol | char | رمز العامل |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | الحجة الأساسية لتطبيق العامل |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى |

**القيمة المرجعة:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - جديد IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

ينشئ IMathNaryOperator

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| operatorSymbol | char | رمز العامل |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | الحجة الأساسية لتطبيق العامل |

**القيمة المرجعة:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - جديد IMathNaryOperator