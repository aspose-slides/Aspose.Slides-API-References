---
title: FontSources
second_title: Aspose.Slides for Java API Referencia
description: Fájl- és memóriaforrásokat biztosít külső betűtípusokhoz.
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
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Mappák, amelyek betűtípusfájlokat tartalmaznak. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Mappák, amelyek betűtípusfájlokat tartalmaznak. |
| [getMemoryFonts()](#getMemoryFonts--) | Betűtípusok gyűjteménye, amelyek byte-tömbként vannak ábrázolva. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Betűtípusok gyűjteménye, amelyek byte-tömbként vannak ábrázolva. |
### FontSources() {#FontSources--}
```
public FontSources()
```

Új alapértelmezett betűtípus-beállításokat hoz létre.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```

Mappák, amelyek betűtípusfájlokat tartalmaznak. Az ebben a mappában található összes betűtípus-fájl a gyűjteménybe kerül. A mappákat rekurzívan keresik.

**Visszatérési érték:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```

Mappák, amelyek betűtípusfájlokat tartalmaznak. Az ebben a mappában található összes betűtípus-fájl a gyűjteménybe kerül. A mappákat rekurzívan keresik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```

Betűtípusok gyűjteménye, amelyek byte-tömbként vannak ábrázolva.

**Visszatérési érték:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```

Betűtípusok gyűjteménye, amelyek byte-tömbként vannak ábrázolva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte[][] |  |