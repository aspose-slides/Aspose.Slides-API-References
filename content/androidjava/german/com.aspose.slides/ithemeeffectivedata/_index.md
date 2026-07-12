---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective theme properties.
type: docs
url: /de/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Unveränderliches Objekt, das effektive Theme-Eigenschaften enthält.

--------------------

Dieses Interface wird zusammen mit dem [ITheme](../../com.aspose.slides/itheme) Interface verwendet, um effektive Formatierungswerte mit angewandter Vererbung zurückzugeben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Gibt das Farbschema zurück. |
| [getFontScheme()](#getFontScheme--) | Gibt das Schriftartenschema zurück. |
| [getFormatScheme()](#getFormatScheme--) | Gibt das Formatschema für Formen zurück. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```


Gibt das Farbschema zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| styleColor | java.lang.Integer | Farbe java.lang.Integer |

**Rückgabewert:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Farbschema [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Gibt das Schriftartenschema zurück. Nur-Lesen [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Rückgabewert:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Gibt das Formatschema für Formen zurück. Nur-Lesen [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Rückgabewert:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)