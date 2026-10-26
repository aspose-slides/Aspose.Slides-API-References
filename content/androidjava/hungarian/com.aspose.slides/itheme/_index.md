---
title: ITheme
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Egy témát reprezentál.
type: docs
url: /hu/com.aspose.slides/itheme/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Egy témát reprezentál.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Visszaadja a színsémát. |
| [getFontScheme()](#getFontScheme--) | Visszaadja a betűtípus-sémát. |
| [getFormatScheme()](#getFormatScheme--) | Visszaadja az alakzatformátum-sémát. |
| [getEffective()](#getEffective--) | Lekérdezi a hatékony témaadatokat az öröklődés alkalmazásával. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Visszaadja a színsémát. Csak olvasható [IColorScheme](../../com.aspose.slides/icolorscheme).

**Visszatér:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Visszaadja a betűtípus-sémát. Csak olvasható [IFontScheme](../../com.aspose.slides/ifontscheme).

**Visszatér:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Visszaadja az alakzatformátum-sémát. Csak olvasható [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Visszatér:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```

Lekérdezi a hatékony témaadatokat az öröklődés alkalmazásával.

**Visszatér:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).