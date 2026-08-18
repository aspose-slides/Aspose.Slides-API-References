---
title: ITheme
second_title: Aspose.Slides für Java API-Referenz
description: Stellt ein Thema dar.
type: docs
url: /de/com.aspose.slides/itheme/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Stellt ein Thema dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Gibt das Farbschema zurück. |
| [getFontScheme()](#getFontScheme--) | Gibt das Schriftschema zurück. |
| [getFormatScheme()](#getFormatScheme--) | Gibt das Formatschema für Formen zurück. |
| [getEffective()](#getEffective--) | Ruft effektive Theme-Daten mit angewandter Vererbung ab. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


Gibt das Farbschema zurück. Nur lesbar [IColorScheme](../../com.aspose.slides/icolorscheme).

**Rückgabe:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


Gibt das Schriftschema zurück. Nur lesbar [IFontScheme](../../com.aspose.slides/ifontscheme).

**Rückgabe:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


Gibt das Formatschema für Formen zurück. Nur lesbar [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Rückgabe:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


Ruft effektive Theme-Daten mit angewandter Vererbung ab.

**Rückgabe:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Ein [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).