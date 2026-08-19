---
title: FontsLoader
second_title: Aspose.Slides pro Java – reference API
description: Třída pro načítání uživatelem definovaných vlastních fontů.
type: docs
url: /cs/com.aspose.slides/fontsloader/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Třída pro načítání vlastních fontů definovaných uživatelem. Měla by být použita před vytvořením jakýchkoli objektů prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Přidá další složky pro hledání fontů. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Přidá font z binárních dat |
| [getFontFolders()](#getFontFolders--) | Získá složky fontů. |
| [clearCache()](#clearCache--) | Uvolní všechny vlastní fonty definované uživatelem |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Přidá další složky pro hledání fontů.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // složky pro vyhledání fontů
>  String[] folders = new String[] { dataDir };
>  // Načíst fonty ze složky vlastních fontů
>  FontsLoader.loadExternalFonts(folders);
>  // Provést nějakou práci a vykreslení prezentace/slajdů
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Vymazat mezipaměť fontů
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| directories | java.lang.String[] | Složky pro načtení dalších fontů. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


Přidá font z binárních dat

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] | Data fontu |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Získá složky fontů. Vrací složky, které byly přidány metodou LoadExternalFonts, a také systémové složky fontů

**Vrací:**
java.lang.String[] - pole obsahující názvy složek
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Uvolní všechny vlastní fonty definované uživatelem

--------------------

Tato metoda musí vymazat mezipaměť s vlastními fonty definovanými uživatelem.