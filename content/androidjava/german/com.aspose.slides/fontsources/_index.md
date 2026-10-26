---
title: FontSources
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt Datei- und Speicherquellen für externe Schriftarten bereit.
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
| [FontSources()](#FontSources--) | Erstellt neue Standard-Font-Optionen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Ordner, die Schriftdateien enthalten. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Ordner, die Schriftdateien enthalten. |
| [getMemoryFonts()](#getMemoryFonts--) | Eine Sammlung von Schriftarten, die als Byte-Arrays dargestellt werden. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Eine Sammlung von Schriftarten, die als Byte-Arrays dargestellt werden. |
### FontSources() {#FontSources--}
```
public FontSources()
```


Erstellt neue Standard-Font-Optionen.

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


Eine Sammlung von Schriftarten, die als Byte-Arrays dargestellt werden.

**Rückgabewert:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```


Eine Sammlung von Schriftarten, die als Byte-Arrays dargestellt werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte[][] |  |