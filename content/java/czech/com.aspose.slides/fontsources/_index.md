---
title: FontSources
second_title: Aspose.Slides pro Java – referenční příručka API
description: Poskytuje soubory a paměťové zdroje pro externí fonty.
type: docs
url: /cs/com.aspose.slides/fontsources/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

Poskytuje soubory a paměťové zdroje pro externí fonty.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [FontSources()](#FontSources--) | Vytvoří nové výchozí nastavení fontů. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Složky obsahující soubory fontů. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Složky obsahující soubory fontů. |
| [getMemoryFonts()](#getMemoryFonts--) | Kolekce fontů představovaných jako pole bajtů. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Kolekce fontů představovaných jako pole bajtů. |
### FontSources() {#FontSources--}
```
public FontSources()
```


Vytvoří nové výchozí nastavení fontů.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```


Složky obsahující soubory fontů. Všechny soubory fontů umístěné v těchto složkách jsou zahrnuty do kolekce. Složky jsou prohledávány rekurzivně.

**Vrací:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```


Složky obsahující soubory fontů. Všechny soubory fontů umístěné v těchto složkách jsou zahrnuty do kolekce. Složky jsou prohledávány rekurzivně.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```


Kolekce fontů představovaných jako pole bajtů.

**Vrací:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```


Kolekce fontů představovaných jako pole bajtů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte[][] |  |