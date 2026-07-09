---
title: IMathLimitFactory
second_title: Aspose.Slides for Android via la référence API Java
description: Permet de créer IMathLimit
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
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Crée IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crée IMathLimit avec la limite en bas |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Crée IMathLimit

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argument de base pour appliquer la limite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Élément de limite |
| upperLimit | boolean | Définit le placement de la limite en haut |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nouvelle limite mathématique
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Crée IMathLimit avec la limite en bas

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argument de base pour appliquer la limite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Élément de limite |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nouvelle limite mathématique