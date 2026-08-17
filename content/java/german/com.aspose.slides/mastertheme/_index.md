---
title: MasterTheme
second_title: Aspose.Slides für Java API-Referenz
description: Stellt ein Master-Design dar.
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

Stellt ein Master-Design dar.
## Methoden

| Method | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Gibt das Farbschema zurück. |
| [getFontScheme()](#getFontScheme--) | Gibt das Schriftartschema zurück. |
| [getFormatScheme()](#getFormatScheme--) | Gibt das Formformatschema zurück. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Gibt die Sammlung zusätzlicher Farbschemas zurück. |
| [getName()](#getName--) | Gibt den Namen eines Designs zurück. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen eines Designs zurück. |
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

Gibt das Schriftartschema zurück. Nur lesbar [IFontScheme](../../com.aspose.slides/ifontscheme).

**Rückgabe:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

Gibt das Formformatschema zurück. Nur lesbar [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Rückgabe:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

Gibt die Sammlung zusätzlicher Farbschemas zurück. Diese Schemata beeinflussen das Aussehen der Präsentation nicht, sie können als Hauptfarbschema für eine Folie ausgewählt werden. Nur lesbar [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Rückgabe:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```

Gibt den Namen eines Designs zurück. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Gibt den Namen eines Designs zurück. Lesen/Schreiben String.

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