---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Permet de créer un bloc de mathématiques
type: docs
url: /fr/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Permet de créer un bloc de mathématiques

--------------------

Pour la compatibilité COM
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Créer un bloc de mathématiques |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Créer un bloc de mathématiques et placer l'élément dedans |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Créer un bloc de mathématiques et placer des éléments dedans |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

Créer un bloc de mathématiques

**Retour :**
[IMathBlock](../../com.aspose.slides/imathblock) - nouveau bloc de mathématiques
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

Créer un bloc de mathématiques et placer l'élément dedans

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Un élément mathématique |

**Retour :**
[IMathBlock](../../com.aspose.slides/imathblock) - nouveau bloc de mathématiques
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Créer un bloc de mathématiques et placer des éléments dedans

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | éléments mathématiques |

**Retour :**
[IMathBlock](../../com.aspose.slides/imathblock) - nouveau bloc de mathématiques