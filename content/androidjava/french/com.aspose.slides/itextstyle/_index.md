---
title: ITextStyle
second_title: Aspose.Slides pour Android via Java API Reference
description: Propriétés de mise en forme du style de texte.
type: docs
url: /fr/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Propriétés de mise en forme du style de texte.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Si le niveau du style existe, le renvoie, sinon renvoie null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Propriétés par défaut du paragraphe. |
| [getEffective()](#getEffective--) | Obtient les données de mise en forme du style de texte effectif avec l'héritage appliqué. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Si le niveau du style existe, le renvoie, sinon renvoie null.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice de niveau basé sur zéro. Doit être compris dans l'intervalle 0..8. |

**Renvoie :**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Mise en forme du niveau [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Propriétés par défaut du paragraphe. Lecture seule [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Renvoie :**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Obtient les données de mise en forme du style de texte effectif avec l'héritage appliqué.

**Renvoie :**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Un [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).