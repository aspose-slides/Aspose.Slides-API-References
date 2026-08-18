---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Változtathatatlan objektum, amely a hatékony téma tulajdonságokat tartalmazza.
type: docs
url: /hu/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Változtathatatlan objektum, amely a hatékony téma tulajdonságokat tartalmazza.

--------------------

Ez az interfész a [ITheme](../../com.aspose.slides/itheme) interfésszel együtt használható a hatékony formázási értékek öröklődéssel alkalmazott visszaadásához.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Visszaadja a színsémát. |
| [getFontScheme()](#getFontScheme--) | Visszaadja a betűkészlet-sémát. |
| [getFormatScheme()](#getFormatScheme--) | Visszaadja az alakzat formátumsémáját. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```


Visszaadja a színsémát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Visszatér:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Színséma [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Visszaadja a betűkészlet-sémát. Csak olvasható [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Visszatér:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Visszaadja az alakzat formátumsémáját. Csak olvasható [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Visszatér:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)