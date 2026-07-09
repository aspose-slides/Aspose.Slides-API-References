---
title: MathParagraphFactory
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Permet de créer un paragraphe mathématique
type: docs
url: /fr/com.aspose.slides/mathparagraphfactory/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

Permet de créer un paragraphe mathématique

--------------------

Pour la compatibilité COM
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Créer un paragraphe mathématique vide |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Crée un paragraphe mathématique et place le bloc mathématique spécifié dans celui-ci |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```


### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```


Créer un paragraphe mathématique vide

**Renvoie :**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nouveau paragraphe mathématique
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Crée un paragraphe mathématique et place le bloc mathématique spécifié dans celui-ci

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | bloc mathématique à placer dans le paragraphe |

**Renvoie :**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nouveau paragraphe mathématique