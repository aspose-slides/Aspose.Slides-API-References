---
title: FontsLoader
second_title: Aspose.Slides för Java API-referens
description: Klass för att ladda anpassade typsnitt som definierats av användaren.
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

Klass för att ladda anpassade typsnitt som definierats av användaren. Ska användas innan några presentationsobjekt skapas.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Lägger till ytterligare mappar för att söka typsnitt. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Lägger till typsnitt från de binära data |
| [getFontFolders()](#getFontFolders--) | Hämtar typsnittsmappar. |
| [clearCache()](#clearCache--) | Frigör alla anpassade typsnitt som definierats av användaren |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Lägger till ytterligare mappar för att söka typsnitt.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // mappar för att söka typsnitt
>  String[] folders = new String[] { dataDir };
>  // Ladda den anpassade typsnittsmappens typsnitt
>  FontsLoader.loadExternalFonts(folders);
>  // Utför något arbete och rendera presentation/slides rendering
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Rensa typsnittscache
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| directories | java.lang.String[] | Kataloger för att läsa in ytterligare typsnitt. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


Lägger till typsnitt från de binära data

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Typsnittets data |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Hämtar typsnittsmappar. Returnerar mappar som har lagts till med LoadExternalFonts-metoden samt systemets typsnittsmappar

**Returnerar:**
java.lang.String[] - array containing folder names
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Frigör alla anpassade typsnitt som definierats av användaren

--------------------

Denna metod måste rensa cache med anpassade typsnitt som definierats av användaren.