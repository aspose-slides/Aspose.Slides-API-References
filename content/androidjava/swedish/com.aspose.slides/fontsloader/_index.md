---
title: FontsLoader
second_title: Aspose.Slides för Android via Java API-referens
description: Klass för att ladda anpassade teckensnitt som definierats av användaren.
type: docs
url: /sv/com.aspose.slides/fontsloader/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Klass för att ladda anpassade teckensnitt som definierats av användaren. Bör användas innan några presentationsobjekt skapas.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Lägger till ytterligare mappar för att söka efter teckensnitt. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Lägger till teckensnitt från de binära data |
| [getFontFolders()](#getFontFolders--) | Hämtar teckensnittsmappor. |
| [clearCache()](#clearCache--) | Frigör alla anpassade teckensnitt som definierats av användaren |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Lägger till ytterligare mappar för att söka efter teckensnitt.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // mappar för att söka teckensnitt
>  String[] folders = new String[] { dataDir };
>  // Ladda de anpassade teckensnittsmapporna
>  FontsLoader.loadExternalFonts(folders);
>  // Utför lite arbete och rendera presentation/slide
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Rensa teckensnittscache
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| directories | java.lang.String[] | Kataloger att läsa ytterligare teckensnitt från. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


Lägger till teckensnitt från de binära data

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Teckensnittets data |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Hämtar teckensnittsmappor. Returnerar mappar som har lagts till med metoden LoadExternalFonts samt systemteckensnittsmappar

**Returnerar:**
java.lang.String[] - array som innehåller mappnamn
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Frigör alla anpassade teckensnitt som definierats av användaren

--------------------

Denna metod måste rensa cache med anpassade teckensnitt som definierats av användaren.