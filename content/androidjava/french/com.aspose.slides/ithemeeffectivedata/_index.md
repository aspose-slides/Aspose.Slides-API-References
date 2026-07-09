---
title: IThemeEffectiveData
second_title: Aspose.Slides pour Android via la référence API Java
description: Objet immuable contenant les propriétés de thème effectives.
type: docs
url: /fr/com.aspose.slides/ithemeeffectivedata/
---
```
public interface IThemeEffectiveData
```

Objet immuable contenant les propriétés de thème effectives.

--------------------

Cette interface est utilisée conjointement avec l'interface [ITheme](../../com.aspose.slides/itheme) pour renvoyer les valeurs de formatage effectives avec héritage appliqué.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Renvoie le jeu de couleurs. |
| [getFontScheme()](#getFontScheme--) | Renvoie le jeu de polices. |
| [getFormatScheme()](#getFormatScheme--) | Renvoie le jeu de format de forme. |

### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```

Renvoie le jeu de couleurs.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| styleColor | java.lang.Integer | Couleur java.lang.Integer |

**Renvoie :**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Jeu de couleurs [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)

### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

Renvoie le jeu de polices. Lecture seule [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Renvoie :**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)

### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

Renvoie le jeu de format de forme. Lecture seule [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Renvoie :**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)