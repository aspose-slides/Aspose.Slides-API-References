---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /hu/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Betűtípus-fájlokat tartalmazó források biztosítanak fájl- és memóriaalapú betűtípusokhoz.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Betűtípus-fájlokat tartalmazó mappák. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Betűtípus-fájlokat tartalmazó mappák. |
| [getMemoryFonts()](#getMemoryFonts--) | Byte tömbökkel ábrázolt betűtípusok gyűjteménye. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Byte tömbökkel ábrázolt betűtípusok gyűjteménye. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


Betűtípus-fájlokat tartalmazó mappák. Az összes betűtípus-fájl, amely ezekben a mappákban található, bele van foglalva a gyűjteménybe. A mappák rekurzívan keresendők.

**Visszatérési érték:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


Betűtípus-fájlokat tartalmazó mappák. Az összes betűtípus-fájl, amely ezekben a mappákban található, bele van foglalva a gyűjteménybe. A mappák rekurzívan keresendők.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


Byte tömbökkel ábrázolt betűtípusok gyűjteménye.

**Visszatérési érték:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


Byte tömbökkel ábrázolt betűtípusok gyűjteménye.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte[][] |  |