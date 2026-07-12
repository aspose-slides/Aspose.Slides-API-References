---
title: ITheme
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt ein Theme dar.
type: docs
url: /de/com.aspose.slides/itheme/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Stellt ein Theme dar.
## Methoden

| Method | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Gibt das Farbschema zurück. |
| [getFontScheme()](#getFontScheme--) | Gibt das Schriftartenschema zurück. |
| [getFormatScheme()](#getFormatScheme--) | Gibt das Shape-Format-Schema zurück. |
| [getEffective()](#getEffective--) | Gibt effektive Theme-Daten mit angewandter Vererbung zurück. |
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

Gibt das Schriftartenschema zurück. Nur lesbar [IFontScheme](../../com.aspose.slides/ifontscheme).

**Rückgabe:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Gibt das Shape-Format-Schema zurück. Nur lesbar [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Rückgabe:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```

Gibt effektive Theme-Daten mit angewandter Vererbung zurück.

**Rückgabe:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).