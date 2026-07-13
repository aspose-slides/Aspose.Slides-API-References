---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /pl/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Udostępnia pliki i źródła pamięci dla zewnętrznych czcionek.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Foldery zawierające pliki czcionek. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Foldery zawierające pliki czcionek. |
| [getMemoryFonts()](#getMemoryFonts--) | Kolekcja czcionek reprezentowanych jako tablice bajtów. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Kolekcja czcionek reprezentowanych jako tablice bajtów. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

Foldery zawierające pliki czcionek. Wszystkie pliki czcionek znajdujące się w tych folderach są włączone do kolekcji. Foldery przeszukiwane rekurencyjnie.

**Zwraca:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

Foldery zawierające pliki czcionek. Wszystkie pliki czcionek znajdujące się w tych folderach są włączone do kolekcji. Foldery przeszukiwane rekurencyjnie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

Kolekcja czcionek reprezentowanych jako tablice bajtów.

**Zwraca:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

Kolekcja czcionek reprezentowanych jako tablice bajtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte[][] |  |