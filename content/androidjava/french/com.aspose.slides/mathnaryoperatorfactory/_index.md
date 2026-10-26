---
title: MathNaryOperatorFactory
second_title: Aspose.Slides pour Android via la Référence de l'API Java
description: Permet de créer IMathNaryOperator
type: docs
url: /fr/com.aspose.slides/mathnaryoperatorfactory/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Permet de créer IMathNaryOperator

--------------------

Pour la compatibilité COM
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crée IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crée IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Crée IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Crée IMathNaryOperator

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Le signe de l'opérateur |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument de base pour appliquer l'opérateur |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inférieure |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite supérieure |

**Renvoie :**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nouvel IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Crée IMathNaryOperator

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Le signe de l'opérateur |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument de base pour appliquer l'opérateur |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inférieure |

**Renvoie :**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nouvel IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Crée IMathNaryOperator

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Le signe de l'opérateur |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument de base pour appliquer l'opérateur |

**Renvoie :**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - nouvel IMathNaryOperator