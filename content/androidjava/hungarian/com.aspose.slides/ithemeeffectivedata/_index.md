---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Megváltoztathatatlan objektum, amely tartalmazza a hatékony téma tulajdonságait.
type: docs
url: /hu/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Megváltoztathatatlan objektum, amely tartalmazza a hatékony téma tulajdonságait.

--------------------

Ez az interfész a [ITheme](../../com.aspose.slides/itheme) interfésszel együtt használatos, hogy a öröklődéssel alkalmazott hatékony formázási értékeket adja vissza.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Returns the color scheme. |
| [getFontScheme()](#getFontScheme--) | Returns the font scheme. |
| [getFormatScheme()](#getFormatScheme--) | Returns the shape format scheme. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```

Visszaadja a színsémát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| styleColor | java.lang.Integer | Color java.lang.Integer |

**Visszatér:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Color scheme [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

Visszaadja a betűtípus sémát. Írásvédett [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Visszatér:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

Visszaadja az alakzat formátumsémát. Írásvédett [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Visszatér:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)