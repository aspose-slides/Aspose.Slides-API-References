---
title: ITheme
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un thème.
type: docs
url: /fr/com.aspose.slides/itheme/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Représente un thème.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Renvoie le jeu de couleurs. |
| [getFontScheme()](#getFontScheme--) | Renvoie le jeu de polices. |
| [getFormatScheme()](#getFormatScheme--) | Renvoie le jeu de formats de forme. |
| [getEffective()](#getEffective--) | Obtient les données de thème effectives avec l'héritage appliqué. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


Renvoie le jeu de couleurs. Lecture seule [IColorScheme](../../com.aspose.slides/icolorscheme).

**Renvoie :**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


Renvoie le jeu de polices. Lecture seule [IFontScheme](../../com.aspose.slides/ifontscheme).

**Renvoie :**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


Renvoie le jeu de formats de forme. Lecture seule [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Renvoie :**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


Obtient les données de thème effectives avec l'héritage appliqué.

**Renvoie :**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Un [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).