---
title: Compress
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een groep methoden voor die bedoeld zijn om te comprimeren.
type: docs
url: /nl/com.aspose.slides/compress/
---
**Erfenis:**
java.lang.Object
```
public class Compress
```

Stelt een groep methoden voor die bedoeld zijn om [Presentation](../../com.aspose.slides/presentation) te comprimeren.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructoren

| Constructor | Omschrijving |
| --- | --- |
| [Compress()](#Compress--) |  |
## Methoden

| Methode | Omschrijving |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Vermindert de grootte van een presentatie door alle beschikbare compressiestappen toe te passen:

 *  Verwijdert ongebruikte masterslides \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Verwijdert ongebruikte layoutslides \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Behoudt alleen de glyphs die daadwerkelijk worden gebruikt in ingebedde lettertypen \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Vermindert de afbeeldingsresolutie tot 150 DPI en verwijdert bijgesneden gebieden van afbeeldingen \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Voert compressie uit op de [Presentation](../../com.aspose.slides/presentation) door ongebruikte masterslides te verwijderen. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Voert compressie uit op de [Presentation](../../com.aspose.slides/presentation) door ongebruikte layoutslides te verwijderen. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Voert compressie uit op de [Presentation](../../com.aspose.slides/presentation) door ongebruikte tekens uit ingebedde lettertypen te verwijderen. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Vermindert de resolutie van afbeeldingen in de presentatie en verwijdert hun bijgesneden gebieden, vergelijkbaar met PowerPoint's "Compress Pictures" toegepast op alle afbeeldingen. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Vermindert de grootte van een presentatie door alle beschikbare compressiestappen toe te passen:

 *  Verwijdert ongebruikte masterslides \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Verwijdert ongebruikte layoutslides \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Behoudt alleen de glyphs die daadwerkelijk worden gebruikt in ingebedde lettertypen \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Vermindert de afbeeldingsresolutie tot 150 DPI en verwijdert bijgesneden gebieden van afbeeldingen \#compressImages(IPresentation,int).compressImages(IPresentation,int).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressPresentation(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | De te comprimeren presentatie. |

Om compressie aan te passen, bijvoorbeeld om een andere afbeeldingsresolutie te gebruiken of een stap over te slaan, roep de hierboven vermelde methoden individueel aan in plaats van deze. Bijgesneden gebieden van afbeeldingen worden permanent verwijderd en kunnen niet worden hersteld in PowerPoint. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

Voert compressie uit op de [Presentation](../../com.aspose.slides/presentation) door ongebruikte masterslides te verwijderen.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | De presentatie-instantie |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

Voert compressie uit op de [Presentation](../../com.aspose.slides/presentation) door ongebruikte layoutslides te verwijderen.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedLayoutSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | De presentatie-instantie |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

Voert compressie uit op de [Presentation](../../com.aspose.slides/presentation) door ongebruikte tekens uit ingebedde lettertypen te verwijderen.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressEmbeddedFonts(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | De presentatie-instantie |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```

Vermindert de resolutie van afbeeldingen in de presentatie en verwijdert hun bijgesneden gebieden, vergelijkbaar met PowerPoint's "Compress Pictures" toegepast op alle afbeeldingen. Afbeeldingen op dia's, layoutdia's en masterslides worden verwerkt, inclusief afbeeldingen binnen groepvormen en afbeeldingvullingen van vormen.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressImages(pres, PicturesCompression.Dpi150);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | De te verwerken presentatie. |
| resolution | int | Doelresolutie relatief ten opzichte van de grootte waarop elke afbeelding wordt weergegeven. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) laat afbeeldingen ongewijzigd. |

Afbeeldingen die al op of onder de doelresolutie zitten, blijven ongewijzigd; afbeeldingen worden nooit opgeschaald.

Niet verwerkt: dia-achtergronden, tabelcelvullingen, grafieken, SmartArt, GIF-afbeeldingen (om animatie te behouden), SVG- en metafile-afbeeldingen (EMF/WMF).

Bijgesneden gebieden worden permanent verwijderd en kunnen niet worden hersteld in PowerPoint.