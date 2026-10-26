---
title: IMathAccentFactory
second_title: Aspose.Slides for Java API Reference
description: Permet de créer un accent mathématique
type: docs
url: /fr/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Permet de créer un accent mathématique

--------------------

Pour la compatibilité COM
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Creates a math accent applying to a specified math element with the default accent character value |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Creates a math accent applying to a specified math element |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

Crée un accent mathématique appliqué à un élément mathématique spécifié avec la valeur de caractère d'accent par défaut

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | élément mathématique auquel appliquer l'accent |

**Retour:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nouvel accent mathématique
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Crée un accent mathématique appliqué à un élément mathématique spécifié

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | élément mathématique auquel appliquer l'accent |
| accentCharacter | char | caractère d'accent |

**Retour:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nouvel accent mathématique