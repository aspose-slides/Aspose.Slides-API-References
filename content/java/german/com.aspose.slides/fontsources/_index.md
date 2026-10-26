---
title: FontSources
second_title: Aspose.Slides für Java API-Referenz
description: Bietet Datei- und Speicherquellen für externe Schriftarten.
type: docs
url: /de/com.aspose.slides/fontsources/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

Stellt Datei- und Speicherquellen für externe Schriftarten bereit.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontSources()](#FontSources--) | Erstellt neue Standard-Schriftartoptionen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Ordner, die Schriftdateien enthalten. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Ordner, die Schriftdateien enthalten. |
| [getMemoryFonts()](#getMemoryFonts--) | Eine Sammlung von Schriftarten, dargestellt als Byte-Arrays. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Eine Sammlung von Schriftarten, dargestellt als Byte-Arrays. |
### FontSources() {#FontSources--}
```
public FontSources()
```


Erstellt neue Standard-Schriftartoptionen.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```


Ordner, die Schriftdateien enthalten. Alle in diesen Ordnern befindlichen Schriftdateien werden in die Sammlung aufgenommen. Ordner, die rekursiv durchsucht werden.

**Rückgabewert:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```


Ordner, die Schriftdateien enthalten. Alle in diesen Ordnern befindlichen Schriftdateien werden in die Sammlung aufgenommen. Ordner, die rekursiv durchsucht werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```


Eine Sammlung von Schriftarten, dargestellt als Byte-Arrays.

**Rückgabewert:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```


Eine Sammlung von Schriftarten, dargestellt als Byte-Arrays.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte[][] |  |