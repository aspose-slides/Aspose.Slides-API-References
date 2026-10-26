---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: Zapewnia plikowe i pamięciowe źródła dla zewnętrznych czcionek.
type: docs
url: /pl/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Zapewnia plikowe i pamięciowe źródła dla zewnętrznych czcionek.
## Metody

| Method | Description |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Foldery zawierające pliki czcionek. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Foldery zawierające pliki czcionek. |
| [getMemoryFonts()](#getMemoryFonts--) | Zbiór czcionek reprezentowanych jako tablice bajtów. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Zbiór czcionek reprezentowanych jako tablice bajtów. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


Foldery zawierające pliki czcionek. Wszystkie pliki czcionek znajdujące się w tych folderach są uwzględniane w kolekcji. Foldery przeszukiwane rekurencyjnie.

**Zwraca:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


Foldery zawierające pliki czcionek. Wszystkie pliki czcionek znajdujące się w tych folderach są uwzględniane w kolekcji. Foldery przeszukiwane rekurencyjnie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


Zbiór czcionek reprezentowanych jako tablice bajtów.

**Zwraca:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


Zbiór czcionek reprezentowanych jako tablice bajtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte[][] |  |