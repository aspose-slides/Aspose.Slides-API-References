---
title: IThemeEffectiveData
second_title: Aspose.Slides für Java API Referenz
description: Unveränderliches Objekt, das wirksame Theme-Eigenschaften enthält.
type: docs
url: /de/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Unveränderliches Objekt, das wirksame Theme-Eigenschaften enthält.

--------------------

Dieses Interface wird zusammen mit dem [ITheme](../../com.aspose.slides/itheme) Interface verwendet, um wirksame Formatierungswerte mit angewandter Vererbung zurückzugeben.
## Methods

| Methode | Beschreibung |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Gibt das Farbschema zurück. |
| [getFontScheme()](#getFontScheme--) | Gibt das Schriftartschema zurück. |
| [getFormatScheme()](#getFormatScheme--) | Gibt das Shape-Format-Schema zurück. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```


Gibt das Farbschema zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Rückgabewert:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Color scheme [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Gibt das Schriftartschema zurück. Nur lesbar [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Rückgabewert:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Gibt das Shape-Format-Schema zurück. Nur lesbar [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Rückgabewert:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)