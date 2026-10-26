---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create IMathNaryOperator
type: docs
url: /fr/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Permet de créer IMathNaryOperator

--------------------

Pour la compatibilité COM
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Crée IMathNaryOperator

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | The operator sign |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Base argument to apply operator |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit |

**Renvoie:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nouveau IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Crée IMathNaryOperator

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | The operator sign |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Base argument to apply operator |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit |

**Renvoie:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nouveau IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Crée IMathNaryOperator

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | The operator sign |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Base argument to apply operator |

**Renvoie:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nouveau IMathNaryOperator