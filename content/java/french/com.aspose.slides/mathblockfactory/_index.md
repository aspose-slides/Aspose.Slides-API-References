---
title: MathBlockFactory
second_title: Référence de l'API Aspose.Slides pour Java
description: Permet de créer un bloc mathématique
type: docs
url: /fr/com.aspose.slides/mathblockfactory/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

Permet de créer un bloc mathématique

--------------------

Pour la compatibilité COM
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Créer un bloc mathématique |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Créer un bloc mathématique et placer l'élément dedans |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Créer un bloc mathématique et placer les éléments dedans |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


Créer un bloc mathématique

**Retour :**
[IMathBlock](../../com.aspose.slides/imathblock) - nouveau bloc mathématique
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```


Créer un bloc mathématique et placer l'élément dedans

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Un élément mathématique |

**Retour :**
[IMathBlock](../../com.aspose.slides/imathblock) - nouveau bloc mathématique
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Créer un bloc mathématique et placer les éléments dedans

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | éléments mathématiques |

**Retour :**
[IMathBlock](../../com.aspose.slides/imathblock) - nouveau bloc mathématique