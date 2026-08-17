---
title: MasterTheme
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un thème principal.
type: docs
url: /fr/com.aspose.slides/mastertheme/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Représente un thème principal.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Renvoie le schéma de couleurs. |
| [getFontScheme()](#getFontScheme--) | Renvoie le schéma de polices. |
| [getFormatScheme()](#getFormatScheme--) | Renvoie le schéma de format de forme. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Renvoie la collection de schémas de couleurs supplémentaires. |
| [getName()](#getName--) | Renvoie le nom d'un thème. |
| [setName(String value)](#setName-java.lang.String-) | Renvoie le nom d'un thème. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

Renvoie le schéma de couleurs. Lecture seule [IColorScheme](../../com.aspose.slides/icolorscheme).

**Renvoie :**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

Renvoie le schéma de polices. Lecture seule [IFontScheme](../../com.aspose.slides/ifontscheme).

**Renvoie :**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

Renvoie le schéma de format de forme. Lecture seule [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Renvoie :**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

Renvoie la collection de schémas de couleurs supplémentaires. Ces schémas n'affectent pas l'apparence de la présentation, ils peuvent être sélectionnés comme schéma de couleurs principal pour une diapositive. Lecture seule [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Renvoie :**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```

Renvoie le nom d'un thème. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Renvoie le nom d'un thème. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**
long