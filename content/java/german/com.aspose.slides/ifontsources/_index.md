---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: Stellt Datei- und Speicherquellen für externe Schriftarten bereit.
type: docs
url: /de/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Stellt Datei- und Speicherquellen für externe Schriftarten bereit.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Ordner, die Schriftdateien enthalten. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Ordner, die Schriftdateien enthalten. |
| [getMemoryFonts()](#getMemoryFonts--) | Eine Sammlung von Schriftarten, dargestellt als Byte-Arrays. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Eine Sammlung von Schriftarten, dargestellt als Byte-Arrays. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

Ordner, die Schriftdateien enthalten. Alle Schriftdateien, die sich in diesen Ordnern befinden, sind in der Sammlung enthalten. Ordner, die rekursiv durchsucht werden.

**Rückgabewert:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

Ordner, die Schriftdateien enthalten. Alle Schriftdateien, die sich in diesen Ordnern befinden, sind in der Sammlung enthalten. Ordner, die rekursiv durchsucht werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

Eine Sammlung von Schriftarten, dargestellt als Byte-Arrays.

**Rückgabewert:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

Eine Sammlung von Schriftarten, dargestellt als Byte-Arrays.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte[][] |  |