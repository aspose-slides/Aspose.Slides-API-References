---
title: MasterTheme
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt ein Master-Theme dar.
type: docs
url: /de/com.aspose.slides/mastertheme/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Stellt ein Master-Theme dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Gibt das Farbschema zurück. |
| [getFontScheme()](#getFontScheme--) | Gibt das Schriftartenschema zurück. |
| [getFormatScheme()](#getFormatScheme--) | Gibt das Shape-Format-Schema zurück. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Gibt die Sammlung zusätzlicher Farbschemata zurück. |
| [getName()](#getName--) | Gibt den Namen eines Themes zurück. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen eines Themes zurück. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

Gibt das Farbschema zurück. Nur lesbar [IColorScheme](../../com.aspose.slides/icolorscheme).

**Rückgabe:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

Gibt das Schriftartenschema zurück. Nur lesbar [IFontScheme](../../com.aspose.slides/ifontscheme).

**Rückgabe:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

Gibt das Shape-Format-Schema zurück. Nur lesbar [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Rückgabe:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

Gibt die Sammlung zusätzlicher Farbschemata zurück. Diese Schemata beeinflussen das Aussehen der Präsentation nicht, sie können als Hauptfarbschema für eine Folie ausgewählt werden. Nur lesbar [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Rückgabe:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```

Gibt den Namen eines Themes zurück. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Gibt den Namen eines Themes zurück. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesbar long.

**Rückgabe:**
long