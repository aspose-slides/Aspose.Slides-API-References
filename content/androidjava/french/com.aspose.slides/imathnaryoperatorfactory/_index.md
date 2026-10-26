---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Permet de créer IMathNaryOperator
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
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crée IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crée IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Crée IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Crée IMathNaryOperator

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Le signe de l'opérateur |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument de base auquel appliquer l'opérateur |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inférieure |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite supérieure |

**Retour:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nouveau IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Crée IMathNaryOperator

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Le signe de l'opérateur |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument de base auquel appliquer l'opérateur |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inférieure |

**Retour:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nouveau IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Crée IMathNaryOperator

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Le signe de l'opérateur |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument de base auquel appliquer l'opérateur |

**Retour:**  
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nouveau IMathNaryOperator