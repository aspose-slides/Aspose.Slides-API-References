---
title: MathLimitFactory
second_title: Aspose.Slides pour Android via la référence API Java
description: Permet de créer IMathLimit
type: docs
url: /fr/com.aspose.slides/mathlimitfactory/
---
**Héritage :**  
java.lang.Object

**Toutes les interfaces implémentées :**  
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)  
```
public class MathLimitFactory implements IMathLimitFactory
```

Permet de créer IMathLimit

--------------------

Pour la compatibilité COM  
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Crée IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crée IMathLimit avec une limite en bas |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```

### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

Crée IMathLimit

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argument de base pour appliquer la limite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Élément de limite |
| upperLimit | boolean | Définit le placement de la limite en haut |

**Renvoie :**
[IMathLimit](../../com.aspose.slides/imathlimit) – nouvelle limite mathématique
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

Crée IMathLimit avec une limite en bas

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argument de base pour appliquer la limite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Élément de limite |

**Renvoie :**
[IMathLimit](../../com.aspose.slides/imathlimit) – nouvelle limite mathématique