---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Objet immuable contenant les propriétés de thème effectives.
type: docs
url: /fr/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Objet immuable contenant les propriétés de thème effectives.

--------------------

Cette interface est utilisée avec l'interface [ITheme](../../com.aspose.slides/itheme) pour renvoyer les valeurs de formatage effectives avec l'héritage appliqué.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Renvoie le schéma de couleurs. |
| [getFontScheme()](#getFontScheme--) | Renvoie le schéma de police. |
| [getFormatScheme()](#getFormatScheme--) | Renvoie le schéma de format de forme. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```


Renvoie le schéma de couleurs.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | Couleur java.awt.Color |

**Renvoie :**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Schéma de couleurs [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Renvoie le schéma de police. Lecture seule [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Renvoie :**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Renvoie le schéma de format de forme. Lecture seule [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Renvoie :**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)