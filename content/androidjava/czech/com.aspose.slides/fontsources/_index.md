---
title: FontSources
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Poskytuje souborové a paměťové zdroje pro externí písma.
type: docs
url: /cs/com.aspose.slides/fontsources/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

Poskytuje souborové a paměťové zdroje pro externí písma.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [FontSources()](#FontSources--) | Vytvoří nová výchozí nastavení písma. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Složky obsahující soubory písem. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Složky obsahující soubory písem. |
| [getMemoryFonts()](#getMemoryFonts--) | Kolekce písem reprezentovaných jako pole bajtů. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Kolekce písem reprezentovaných jako pole bajtů. |
### FontSources() {#FontSources--}
```
public FontSources()
```


Vytvoří nová výchozí nastavení písma.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```


Složky obsahující soubory písem. Všechny soubory písem umístěné v těchto složkách jsou zahrnuty do kolekce. Složky, které jsou rekurzivně prohledávány.

**Vrací:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```


Složky obsahující soubory písem. Všechny soubory písem umístěné v těchto složkách jsou zahrnuty do kolekce. Složky, které jsou rekurzivně prohledávány.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```


Kolekce písem reprezentovaných jako pole bajtů.

**Vrací:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```


Kolekce písem reprezentovaných jako pole bajtů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte[][] |  |