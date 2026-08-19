---
title: FontsLoader
second_title: Aspose.Slides voor Java API-referentie
description: Klasse voor het laden van door de gebruiker gedefinieerde aangepaste lettertypen.
type: docs
url: /nl/com.aspose.slides/fontsloader/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Klasse voor het laden van door de gebruiker gedefinieerde aangepaste lettertypen. Moet worden gebruikt vóór het maken van presentatie-objecten.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Voegt extra mappen toe om lettertypen te zoeken. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Voegt een lettertype toe vanuit de binaire gegevens |
| [getFontFolders()](#getFontFolders--) | Haalt maplocaties voor lettertypen op. |
| [clearCache()](#clearCache--) | Geeft alle door de gebruiker gedefinieerde aangepaste lettertypen vrij |
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
>  // Laad de aangepaste lettertype map
>  FontsLoader.loadExternalFonts(folders);
>  // Voer wat werk uit en rendere presentatie/slides rendering
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Wis lettertypecache
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| directories | java.lang.String[] | Mappen om extra lettertypen te lezen. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```

Voegt een lettertype toe vanuit de binaire gegevens

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] | Lettertype-gegevens |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```

Haalt maplocaties voor lettertypen op. Retourneert mappen die zijn toegevoegd met de LoadExternalFonts-methode, evenals systeembrede lettertype-mappen

**Retour:**
java.lang.String[] - array met mapnamen
### clearCache() {#clearCache--}
```
public static void clearCache()
```

Geeft alle door de gebruiker gedefinieerde aangepaste lettertypen vrij

--------------------

Deze methode moet de cache wissen voor door de gebruiker gedefinieerde aangepaste lettertypen.