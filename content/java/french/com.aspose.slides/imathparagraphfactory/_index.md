---
title: IMathParagraphFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math paragraph
type: docs
url: /fr/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

Permet de créer un paragraphe mathématique

--------------------

Pour la compatibilité COM
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Crée un paragraphe mathématique vide |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Crée un paragraphe mathématique et place le bloc mathématique spécifié dans celui-ci |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```

Créer un paragraphe mathématique vide

**Retour :**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nouveau paragraphe mathématique
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

Crée un paragraphe mathématique et place le bloc mathématique spécifié dans celui-ci

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | bloc mathématique à placer dans le paragraphe |

**Retour :**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nouveau paragraphe mathématique