---
title: ITheme
second_title: Aspose.Slides Java API-referencia
description: Egy témát képvisel.
type: docs
url: /hu/com.aspose.slides/itheme/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Egy témát képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Visszaadja a színsémát. |
| [getFontScheme()](#getFontScheme--) | Visszaadja a betűsémát. |
| [getFormatScheme()](#getFormatScheme--) | Visszaadja az alakzat formátumsémát. |
| [getEffective()](#getEffective--) | Lekéri a hatékony téma adatokat az öröklődés alkalmazásával. |
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

Visszaadja a betűsémát. Csak olvasható [IFontScheme](../../com.aspose.slides/ifontscheme).

**Visszatér:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Visszaadja az alakzat formátumsémát. Csak olvasható [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Visszatér:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```

Lekéri a hatékony téma adatokat az öröklődés alkalmazásával.

**Visszatér:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).