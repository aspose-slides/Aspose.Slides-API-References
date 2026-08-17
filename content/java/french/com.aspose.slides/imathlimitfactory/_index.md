---
title: IMathLimitFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create IMathLimit
type: docs
url: /fr/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Permet de créer IMathLimit

--------------------

Pour la compatibilité COM
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Creates IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathLimit with limit at the bottom |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Crée IMathLimit

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Base argument to apply the limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit element |
| upperLimit | boolean | Sets the placement of the limit on top |

**Renvoie :**
[IMathLimit](../../com.aspose.slides/imathlimit) - nouvelle limite mathématique
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Crée IMathLimit avec une limite en bas

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Base argument to apply the limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit element |

**Renvoie :**
[IMathLimit](../../com.aspose.slides/imathlimit) - nouvelle limite mathématique