---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objet immuable qui contient les propriétés de style de texte effectives.
type: docs
url: /fr/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Objet immuable qui contient les propriétés de style de texte effectives.

--------------------

Cette interface est utilisée avec l'interface [ITextStyle](../../com.aspose.slides/itextstyle) pour renvoyer les valeurs de formatage effectives avec héritage appliqué.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Renvoie le niveau du style effectif. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Renvoie les propriétés de paragraphe par défaut effectives. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Renvoie le niveau du style effectif.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de niveau basé à zéro. Doit se situer dans l'intervalle 0..8. |

**Renvoie :**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Formatage effectif du niveau [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Renvoie les propriétés de paragraphe par défaut effectives. Lecture seule [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Renvoie :**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)