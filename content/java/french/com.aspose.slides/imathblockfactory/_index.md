---
title: IMathBlockFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math block
type: docs
url: /fr/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Permet de créer un bloc mathématique

--------------------

Pour la compatibilité COM
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Créer un bloc mathématique |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Créer un bloc mathématique et y placer l'élément |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Créer un bloc mathématique et y placer les éléments |

### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

Créer un bloc mathématique

**Valeur retournée :**
[IMathBlock](../../com.aspose.slides/imathblock) - nouveau bloc mathématique

### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

Créer un bloc mathématique et y placer l'élément

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Un élément mathématique |

**Valeur retournée :**
[IMathBlock](../../com.aspose.slides/imathblock) - nouveau bloc mathématique

### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Créer un bloc mathématique et y placer les éléments

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | éléments mathématiques |

**Valeur retournée :**
[IMathBlock](../../com.aspose.slides/imathblock) - nouveau bloc mathématique