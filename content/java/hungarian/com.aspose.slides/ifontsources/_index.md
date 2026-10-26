---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: Külső betűtípusok fájl- és memóriaforrásait biztosítja.
type: docs
url: /hu/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Külső betűtípusok fájl- és memóriaforrásait biztosítja.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Betűtípus-fájlokat tartalmazó mappák. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Betűtípus-fájlokat tartalmazó mappák. |
| [getMemoryFonts()](#getMemoryFonts--) | Byte tömbök formájában ábrázolt betűtípusok gyűjteménye. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Byte tömbök formájában ábrázolt betűtípusok gyűjteménye. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

Betűtípus-fájlokat tartalmazó mappák. Az összes ebben a mappában található betűtípusfájl a gyűjteménybe kerül. Rekurzívan keresett mappák.

**Visszaadja:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

Betűtípus-fájlokat tartalmazó mappák. Az összes ebben a mappában található betűtípusfájl a gyűjteménybe kerül. Rekurzívan keresett mappák.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

Byte tömbök formájában ábrázolt betűtípusok gyűjteménye.

**Visszaadja:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

Byte tömbök formájában ábrázolt betűtípusok gyűjteménye.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte[][] |  |