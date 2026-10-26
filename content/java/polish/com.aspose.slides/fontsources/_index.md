---
title: FontSources
second_title: Aspose.Slides dla Java – odniesienie API
description: Zapewnia plikowe i pamięciowe źródła dla czcionek zewnętrznych.
type: docs
url: /pl/com.aspose.slides/fontsources/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

Zapewnia plikowe i pamięciowe źródła dla czcionek zewnętrznych.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [FontSources()](#FontSources--) | Tworzy nowe domyślne opcje czcionki. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Foldery zawierające pliki czcionek. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Foldery zawierające pliki czcionek. |
| [getMemoryFonts()](#getMemoryFonts--) | Zbiór czcionek reprezentowanych jako tablice bajtów. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Zbiór czcionek reprezentowanych jako tablice bajtów. |
### FontSources() {#FontSources--}
```
public FontSources()
```

Tworzy nowe domyślne opcje czcionki.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```

Foldery zawierające pliki czcionek. Wszystkie pliki czcionek znajdujące się w tych folderach są włączone do kolekcji. Foldery przeszukiwane rekurencyjnie.

**Zwraca:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```

Foldery zawierające pliki czcionek. Wszystkie pliki czcionek znajdujące się w tych folderach są włączone do kolekcji. Foldery przeszukiwane rekurencyjnie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```

Zbiór czcionek reprezentowanych jako tablice bajtów.

**Zwraca:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```

Zbiór czcionek reprezentowanych jako tablice bajtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte[][] |  |