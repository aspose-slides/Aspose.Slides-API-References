---
title: FontsLoader
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Klasa do ładowania niestandardowych czcionek zdefiniowanych przez użytkownika.
type: docs
url: /pl/com.aspose.slides/fontsloader/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Klasa do ładowania niestandardowych czcionek zdefiniowanych przez użytkownika. Należy jej używać przed tworzeniem jakichkolwiek obiektów prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Dodaje dodatkowe foldery w poszukiwaniu czcionek. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Dodaje czcionkę z danych binarnych |
| [getFontFolders()](#getFontFolders--) | Gets font folders. |
| [clearCache()](#clearCache--) | Releases all custom fonts defined by user |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Dodaje dodatkowe foldery w poszukiwaniu czcionek.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // foldery do wyszukiwania czcionek
>  String[] folders = new String[] { dataDir };
>  // Załaduj czcionki z własnego katalogu czcionek
>  FontsLoader.loadExternalFonts(folders);
>  // Wykonaj pewne operacje i renderowanie prezentacji/slajdów
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Wyczyść pamięć podręczną czcionek
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| directories | java.lang.String[] | Foldery do odczytywania dodatkowych czcionek. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


Dodaje czcionkę z danych binarnych

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| data | byte[] | Dane czcionki |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Pobiera foldery czcionek. Zwraca foldery, które zostały dodane metodą LoadExternalFonts, a także systemowe foldery czcionek

**Zwraca:**
java.lang.String[] - tablica zawierająca nazwy folderów
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Zwalnia wszystkie niestandardowe czcionki zdefiniowane przez użytkownika

--------------------

Ta metoda wymaga wyczyszczenia pamięci podręcznej z niestandardowymi czjękami zdefiniowanymi przez użytkownika.