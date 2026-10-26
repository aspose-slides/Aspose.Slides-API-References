---
title: MathFunctionFactory
second_title: Référence de l’API Aspose.Slides pour Java
description: Permet de créer une fonction mathématique
type: docs
url: /fr/com.aspose.slides/mathfunctionfactory/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)  
```
public class MathFunctionFactory implements IMathFunctionFactory
```

Permet de créer une fonction mathématique

--------------------

Pour la compatibilité COM
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crée une fonction mathématique |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Crée une fonction mathématique |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Crée une fonction mathématique

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Élément utilisé comme nom de fonction |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Élément utilisé comme argument de fonction |

**Valeur de retour:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nouvelle fonction mathématique
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Crée une fonction mathématique

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| funcName | java.lang.String | Nom de la fonction |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Élément utilisé comme argument de fonction |

**Valeur de retour:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nouvelle fonction mathématique