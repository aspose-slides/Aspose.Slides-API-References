---
title: FontsLoader
second_title: Aspose.Slides Androidhoz a Java API referencia
description: Osztály egyedi, felhasználó által definiált betűkészletek betöltésére.
type: docs
url: /hu/com.aspose.slides/fontsloader/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Osztály egyedi, felhasználó által definiált betűkészletek betöltésére. A prezentációobjektumok létrehozása előtt kell használni.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | További mappákat ad hozzá a betűkészletek kereséséhez. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Betűkészletet ad hozzá a bináris adatokból |
| [getFontFolders()](#getFontFolders--) | Megkapja a betűkészlet mappákat. |
| [clearCache()](#clearCache--) | Felszabadítja a felhasználó által definiált összes egyedi betűkészletet |

### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```

További mappákat ad hozzá a betűkészletek kereséséhez.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // mappák a betűkészletek kereséséhez
>  String[] folders = new String[] { dataDir };
>  // Betölti az egyedi betűkészlet könyvtárban lévő betűkészleteket
>  FontsLoader.loadExternalFonts(folders);
>  // Végrehajt némi munkát és elvégzi a prezentáció/slajdok renderelését
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Betűkészlet gyorsítótár törlése
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| directories | java.lang.String[] | A további betűkészletek beolvasásához használt könyvtárak. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```

Betűkészletet ad hozzá a bináris adatokból

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] | A betűkészlet adatai |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```

Megkapja a betűkészlet mappákat. Visszaadja azokat a mappákat, amelyeket a LoadExternalFonts metódussal adtak hozzá, illetve a rendszer betűkészlet mappákat

**Visszatérési érték:**
java.lang.String[] - tömb, amely a mappaneveket tartalmazza

### clearCache() {#clearCache--}
```
public static void clearCache()
```

Felszabadítja a felhasználó által definiált összes egyedi betűkészletet

--------------------

Ennek a metódusnak törölnie kell a felhasználó által definiált egyedi betűkészletek gyorsítótárát.