---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Poskytuje souborové a paměťové zdroje pro externí písma.
type: docs
url: /cs/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Poskytuje souborové a paměťové zdroje pro externí písma.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Folders containing font files. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Folders containing font files. |
| [getMemoryFonts()](#getMemoryFonts--) | A collection of fonts represented as byte arrays. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | A collection of fonts represented as byte arrays. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

Složky obsahující soubory písem. Všechny soubory písem nacházející se v těchto složkách jsou zahrnuty do kolekce. Složky jsou prohledávány rekurzivně.

**Vrací:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

Složky obsahující soubory písem. Všechny soubory písem nacházející se v těchto složkách jsou zahrnuty do kolekce. Složky jsou prohledávány rekurzivně.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

Kolekce písem reprezentovaných jako pole bajtů.

**Vrací:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

Kolekce písem reprezentovaných jako pole bajtů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte[][] |  |