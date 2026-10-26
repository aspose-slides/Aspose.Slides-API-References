---
title: FontSources
second_title: Aspose.Slides Androidra Java API-referencia
description: Fájlt és memóriaforrásokat biztosít külső betűtípusokhoz.
type: docs
url: /hu/com.aspose.slides/fontsources/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

Fájl- és memóriaforrásokat biztosít külső betűtípusokhoz.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [FontSources()](#FontSources--) | Új alapértelmezett betűtípus-beállításokat hoz létre. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Betűtípus-fájlokat tartalmazó mappák. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Betűtípus-fájlokat tartalmazó mappák. |
| [getMemoryFonts()](#getMemoryFonts--) | A betűtípusok byte-tömbökként megjelenített gyűjteménye. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | A betűtípusok byte-tömbökként megjelenített gyűjteménye. |
### FontSources() {#FontSources--}
```
public FontSources()
```

Új alapértelmezett betűtípus-beállításokat hoz létre.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```

Betűtípus-fájlokat tartalmazó mappák. Az összes ebben a mappában található betűtípus-fájl be van vonva a gyűjteménybe. Rekurzívan keresett mappák.

**Visszatérési érték:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```

Betűtípus-fájlokat tartalmazó mappák. Az összes ebben a mappában található betűtípus-fájl be van vonva a gyűjteménybe. Rekurzívan keresett mappák.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```

A betűtípusok byte-tömbökként megjelenített gyűjteménye.

**Visszatérési érték:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```

A betűtípusok byte-tömbökként megjelenített gyűjteménye.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte[][] |  |