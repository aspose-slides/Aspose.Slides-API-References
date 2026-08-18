---
title: FontsLoader
second_title: Aspose.Slides dla Java – odniesienie API
description: Klasa służąca do ładowania niestandardowych czcionek zdefiniowanych przez użytkownika.
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

Klasa służąca do ładowania niestandardowych czcionek zdefiniowanych przez użytkownika. Należy używać przed tworzeniem jakichkolwiek obiektów prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Dodaje dodatkowe foldery do wyszukiwania czcionek. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Dodaje czcionkę z danych binarnych |
| [getFontFolders()](#getFontFolders--) | Pobiera foldery czcionek. |
| [clearCache()](#clearCache--) | Zwalnia wszystkie niestandardowe czcionki zdefiniowane przez użytkownika |

### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Dodaje dodatkowe foldery do wyszukiwania czcionek.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // folders to seek fonts
>  String[] folders = new String[] { dataDir };
>  // Load the custom font directory fonts
>  FontsLoader.loadExternalFonts(folders);
>  // Do Some work and perform presentation/slides rendering
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Clear Font Cachce
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| directories | java.lang.String[] | Katalogi do odczytu dodatkowych czcionek. |

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


Pobiera foldery czcionek. Zwraca foldery, które zostały dodane metodą LoadExternalFonts, oraz systemowe foldery czcionek

**Zwraca:**
java.lang.String[] - tablica zawierająca nazwy folderów
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Zwalnia wszystkie niestandardowe czcionki zdefiniowane przez użytkownika

--------------------

Ta metoda musi wyczyścić pamięć podręczną z niestandardowymi czcionkami zdefiniowanymi przez użytkownika.