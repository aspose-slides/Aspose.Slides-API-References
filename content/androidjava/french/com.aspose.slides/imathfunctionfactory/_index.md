---
title: IMathFunctionFactory
second_title: Aspose.Slides pour Android via la référence API Java
description: Permet de créer une fonction mathématique
type: docs
url: /fr/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Permet de créer une fonction mathématique

--------------------

Pour la compatibilité COM
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crée une fonction mathématique |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Crée une fonction mathématique |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Crée une fonction mathématique

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Élément utilisé comme nom de fonction |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Élément utilisé comme argument de fonction |

**Renvoie:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nouvelle fonction mathématique
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Crée une fonction mathématique

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| funcName | java.lang.String | Nom de la fonction |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Élément utilisé comme argument de fonction |

**Renvoie:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nouvelle fonction mathématique