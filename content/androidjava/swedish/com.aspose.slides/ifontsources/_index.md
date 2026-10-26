---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /sv/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Tillhandahåller fil- och minneskällor för externa teckensnitt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Mappar som innehåller teckensnittsfiler. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Mappar som innehåller teckensnittsfiler. |
| [getMemoryFonts()](#getMemoryFonts--) | En samling teckensnitt representerade som byte-arrayer. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | En samling teckensnitt representerade som byte-arrayer. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


Mappar som innehåller teckensnittsfiler. Alla teckensnittsfiler som finns i dessa mappar inkluderas i samlingen. Mappar som söks rekursivt.

**Returnerar:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


Mappar som innehåller teckensnittsfiler. Alla teckensnittsfiler som finns i dessa mappar inkluderas i samlingen. Mappar som söks rekursivt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


En samling teckensnitt representerade som byte-arrayer.

**Returnerar:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


En samling teckensnitt representerade som byte-arrayer.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte[][] |  |