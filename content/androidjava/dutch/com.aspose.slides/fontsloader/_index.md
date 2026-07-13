---
title: FontsLoader
second_title: Aspose.Slides voor Android via Java API-referentie
description: Klasse voor het laden van aangepaste lettertypen die door de gebruiker zijn gedefinieerd.
type: docs
url: /nl/com.aspose.slides/fontsloader/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Klasse voor het laden van aangepaste lettertypen die door de gebruiker zijn gedefinieerd. Moet worden gebruikt voordat er presentatie-objecten worden aangemaakt.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Voegt extra mappen toe om lettertypen te zoeken. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Voegt een lettertype toe vanuit de binaire gegevens |
| [getFontFolders()](#getFontFolders--) | Haalt lettertype-mappen op. |
| [clearCache()](#clearCache--) | Verwijdert alle door de gebruiker gedefinieerde aangepaste lettertypen |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Voegt extra mappen toe om lettertypen te zoeken.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // mappen om lettertypen te zoeken
>  String[] folders = new String[] { dataDir };
>  // Laad de lettertypen uit de aangepaste fontmap
>  FontsLoader.loadExternalFonts(folders);
>  // Doe wat werk en voer presentatie-/dia-rendering uit
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Wis lettertypecache
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| directories | java.lang.String[] | Mappen om extra lettertypen te lezen. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


Voegt een lettertype toe vanuit de binaire gegevens

**Parameters**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] | Gegevens van het lettertype |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Haalt lettertype-mappen op. Retourneert mappen die zijn toegevoegd met de LoadExternalFonts-methode evenals systeem-lettertype-mappen

**Retour**
java.lang.String[] - array met mapnamen
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Verwijdert alle door de gebruiker gedefinieerde aangepaste lettertypen

--------------------

Deze methode moet de cache wissen met door de gebruiker gedefinieerde aangepaste lettertypen.