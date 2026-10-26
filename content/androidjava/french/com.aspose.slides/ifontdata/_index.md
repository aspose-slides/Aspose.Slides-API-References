---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: Représente une définition de police.
type: docs
url: /fr/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Représente une définition de police.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFontName()](#getFontName--) | Renvoie le nom de la police. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Renvoie le nom de la police, en remplaçant la référence du thème par la police réellement utilisée. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

Renvoie le nom de la police. Lecture seule String.

**Retour :**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

Renvoie le nom de la police, en remplaçant la référence du thème par la police réellement utilisée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Thème dont le nom de police thématisé doit être récupéré. Il incombe à l’appelant de fournir une valeur correcte. |

**Retour :**
java.lang.String - Nom de la police.