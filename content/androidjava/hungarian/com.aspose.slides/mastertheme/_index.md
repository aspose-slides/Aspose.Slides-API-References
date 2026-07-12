---
title: MasterTheme
second_title: Aspose.Slides Android számára Java API referenciája
description: Egy mester témát reprezentál.
type: docs
url: /hu/com.aspose.slides/mastertheme/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Minden megvalósított interfész:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Egy mester témát reprezentál.
## Módszerek

| Method | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Visszaadja a színsémát. |
| [getFontScheme()](#getFontScheme--) | Visszaadja a betűsémát. |
| [getFormatScheme()](#getFormatScheme--) | Visszaadja az alakzat formátumsémát. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Visszaadja a további színsémák gyűjteményét. |
| [getName()](#getName--) | Visszaadja egy téma nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja egy téma nevét. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

Visszaadja a színsémát. Csak olvasható [IColorScheme](../../com.aspose.slides/icolorscheme).

**Visszatér:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

Visszaadja a betűsémát. Csak olvasható [IFontScheme](../../com.aspose.slides/ifontscheme).

**Visszatér:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

Visszaadja az alakzat formátumsémát. Csak olvasható [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Visszatér:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

Visszaadja a további színsémák gyűjteményét. Ezek a sémák nem befolyásolják a prezentáció megjelenését, kiválaszthatók fő színsémaként egy dián. Csak olvasható [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Visszatér:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```

Visszaadja egy téma nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Visszaadja egy téma nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**
long