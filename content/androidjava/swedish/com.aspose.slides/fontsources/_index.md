---
title: FontSources
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller fil- och minneskällor för externa teckensnitt.
type: docs
url: /sv/com.aspose.slides/fontsources/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

Tillhandahåller fil- och minneskällor för externa teckensnitt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontSources()](#FontSources--) | Skapar nya standardalternativ för teckensnitt. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Mappar som innehåller teckensnittsfiler. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Mappar som innehåller teckensnittsfiler. |
| [getMemoryFonts()](#getMemoryFonts--) | En samling teckensnitt representerade som byte-arrayer. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | En samling teckensnitt representerade som byte-arrayer. |
### FontSources() {#FontSources--}
```
public FontSources()
```


Skapar nya standardalternativ för teckensnitt.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```


Mappar som innehåller teckensnittsfiler. Alla teckensnittsfiler som finns i dessa mappar inkluderas i samlingen. Mappar som söks igenom rekursivt.

**Returnerar:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```


Mappar som innehåller teckensnittsfiler. Alla teckensnittsfiler som finns i dessa mappar inkluderas i samlingen. Mappar som söks igenom rekursivt.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```


En samling teckensnitt representerade som byte-arrayer.

**Returnerar:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```


En samling teckensnitt representerade som byte-arrayer.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[][] |  |