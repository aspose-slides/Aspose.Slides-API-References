---
title: MathAccentFactory
second_title: Aspose.Slides pour Android via la référence API Java
description: Permet de créer un accent mathématique
type: docs
url: /fr/com.aspose.slides/mathaccentfactory/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Permet de créer un accent mathématique

--------------------

Pour la compatibilité COM
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Crée un accent mathématique appliqué à un élément mathématique spécifié avec la valeur de caractère d'accent par défaut |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Crée un accent mathématique appliqué à un élément mathématique spécifié |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


Crée un accent mathématique appliqué à un élément mathématique spécifié avec la valeur de caractère d'accent par défaut

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | élément mathématique auquel appliquer l'accent |

**Renvoie:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nouvel accent mathématique
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Crée un accent mathématique appliqué à un élément mathématique spécifié

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | élément mathématique auquel appliquer l'accent |
| accentCharacter | char | caractère d'accent |

**Renvoie:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nouvel accent mathématique