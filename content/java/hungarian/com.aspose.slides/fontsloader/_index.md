---
title: FontsLoader
second_title: Aspose.Slides Java API hivatkozás
description: Osztály egyedi, felhasználó által definiált betűtípusok betöltéséhez.
type: docs
url: /hu/com.aspose.slides/fontsloader/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Osztály egyedi, felhasználó által definiált betűtípusok betöltéséhez. A prezentációobjektumok létrehozása előtt kell használni.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | További mappákat ad hozzá a betűtípusok kereséséhez. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Betűtípust ad hozzá a bináris adatokból |
| [getFontFolders()](#getFontFolders--) | A betűtípus mappákat lekéri. |
| [clearCache()](#clearCache--) | A felhasználó által definiált összes egyedi betűtípust felszabadítja. |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


További mappákat ad hozzá a betűtípusok kereséséhez.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // a betűtípusok kereséséhez szükséges mappák
>  String[] folders = new String[] { dataDir };
>  // Tölti be a saját betűtípuskönyvtár betűtípusait
>  FontsLoader.loadExternalFonts(folders);
>  // Végrehajt némi munkát és megjeleníti a prezentációt/diát
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Törli a betűtípus-gyorsítótárat
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| directories | java.lang.String[] | A további betűtípusok olvasásához használt könyvtárak. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


Betűtípust ad hozzá a bináris adatokból

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] | A betűtípus adatai |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Lekéri a betűtípus mappákat. Visszaadja azokat a mappákat, amelyeket a LoadExternalFonts metódussal adtak hozzá, valamint a rendszer betűtípus mappákat.

**Visszatérési érték:**
java.lang.String[] - array containing folder names
### clearCache() {#clearCache--}
```
public static void clearCache()
```


A felhasználó által definiált összes egyedi betűtípust felszabadítja.

--------------------

Ennek a metódusnak törölnie kell a felhasználó által definiált egyedi betűtípusok gyorsítótárát.