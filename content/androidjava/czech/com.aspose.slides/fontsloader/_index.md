---
title: FontsLoader
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Třída pro načítání vlastních fontů definovaných uživatelem.
type: docs
url: /cs/com.aspose.slides/fontsloader/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Třída pro načítání vlastních fontů definovaných uživatelem. Má být použita před vytvořením jakýchkoliv objektů prezentace.
## Metody

| Method | Description |
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
>  // složky pro vyhledávání fontů
>  String[] folders = new String[] { dataDir };
>  // Načíst složku vlastních fontů
>  FontsLoader.loadExternalFonts(folders);
>  // Proveďte nějakou práci a vykreslete prezentaci/slides rendering
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
| directories | java.lang.String[] | Složky, ze kterých se mají načíst další fonty. |

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


Získá složky fontů. Vrací složky, které byly přidány metodou LoadExternalFonts, stejně jako systémové složky fontů.

**Vrací:**
java.lang.String[] - pole obsahující názvy složek
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Uvolní všechny vlastní fonty definované uživatelem

--------------------

Tato metoda potřebuje vymazat mezipaměť s vlastními fonty definovanými uživatelem.