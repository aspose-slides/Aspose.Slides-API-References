---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
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
| [getFontFolders()](#getFontFolders--) | Složky obsahující soubory písem. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Složky obsahující soubory písem. |
| [getMemoryFonts()](#getMemoryFonts--) | Kolekce písem reprezentovaných jako pole bajtů. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Kolekce písem reprezentovaných jako pole bajtů. |
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