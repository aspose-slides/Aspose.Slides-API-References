---
title: MasterTheme
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett huvudtema.
type: docs
url: /sv/com.aspose.slides/mastertheme/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Representerar ett huvudtema.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Returnerar färgschemat. |
| [getFontScheme()](#getFontScheme--) | Returnerar typsnittsschemat. |
| [getFormatScheme()](#getFormatScheme--) | Returnerar formateringsschemat för former. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Returnerar samlingen av ytterligare färgscheman. |
| [getName()](#getName--) | Returnerar namnet på ett tema. |
| [setName(String value)](#setName-java.lang.String-) | Returnerar namnet på ett tema. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

Returnerar färgschemat. Skrivskyddad [IColorScheme](../../com.aspose.slides/icolorscheme).

**Returnerar:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

Returnerar typsnittsschemat. Skrivskyddad [IFontScheme](../../com.aspose.slides/ifontscheme).

**Returnerar:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

Returnerar formateringsschemat för former. Skrivskyddad [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Returnerar:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

Returnerar samlingen av ytterligare färgscheman. Dessa scheman påverkar inte presentationens utseende, de kan väljas som huvudfärgschema för en bild. Skrivskyddad [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Returnerar:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```

Returnerar namnet på ett tema. Läs/skriv String.

**Returnerar:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Returnerar namnet på ett tema. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Skrivskyddad long.

**Returnerar:**
long