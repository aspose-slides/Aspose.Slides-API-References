---
title: FontSources
second_title: Aspose.Slides för Java API-referens
description: Tillhandahåller fil- och minneskällor för externa typsnitt.
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

Tillhandahåller fil- och minneskällor för externa typsnitt.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontSources()](#FontSources--) | Skapar nya standardalternativ för typsnitt. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Mappar som innehåller typsnittsfiler. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Mappar som innehåller typsnittsfiler. |
| [getMemoryFonts()](#getMemoryFonts--) | En samling typsnitt representerade som byte-arrayer. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | En samling typsnitt representerade som byte-arrayer. |
### FontSources() {#FontSources--}
```
public FontSources()
```


Skapar nya standardalternativ för typsnitt.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```


Mappar som innehåller typsnittsfiler. Alla typsnittsfiler som finns i dessa mappar ingår i samlingen. Mappar som söks rekursivt.

**Returnerar:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```


Mappar som innehåller typsnittsfiler. Alla typsnittsfiler som finns i dessa mappar ingår i samlingen. Mappar som söks rekursivt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```


En samling typsnitt representerade som byte-arrayer.

**Returnerar:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```


En samling typsnitt representerade som byte-arrayer.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte[][] |  |