---
title: MathNaryOperatorFactory
second_title: Aspose.Slides لمرجع API للـ Java
description: يسمح بإنشاء IMathNaryOperator
type: docs
url: /ar/com.aspose.slides/mathnaryoperatorfactory/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)  
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

يسمح بإنشاء IMathNaryOperator

--------------------

للتوافق مع COM  
## المنشئات

| Constructor | الوصف |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## الطرق

| Method | الوصف |
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

**المعاملات:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| operatorSymbol | char | إشارة العامل |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | المعامل الأساسي لتطبيق العامل |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأقصى |

**القيمة المرجعة:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - جديد IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


ينشئ IMathNaryOperator

**المعاملات:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| operatorSymbol | char | إشارة العامل |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | المعامل الأساسي لتطبيق العامل |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد الأدنى |

**القيمة المرجعة:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - جديد IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


ينشئ IMathNaryOperator

**المعاملات:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| operatorSymbol | char | إشارة العامل |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | المعامل الأساسي لتطبيق العامل |

**القيمة المرجعة:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - جديد IMathNaryOperator