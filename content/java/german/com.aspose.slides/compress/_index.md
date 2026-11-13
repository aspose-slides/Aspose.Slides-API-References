---
title: Compress
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Gruppe von Methoden bereit, die dazu bestimmt sind, zu komprimieren.
type: docs
url: /de/com.aspose.slides/compress/
---
**Vererbung:**
java.lang.Object
```
public class Compress
```

Stellt eine Gruppe von Methoden bereit, die dazu bestimmt sind, [Presentation](../../com.aspose.slides/presentation) zu komprimieren.

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Compress()](#Compress--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Reduziert die Größe einer Präsentation, indem alle verfügbaren Komprimierungsschritte angewendet werden:

 *  Entfernt nicht verwendete Masterfolien \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Entfernt nicht verwendete Layoutfolien \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Behält nur die tatsächlich in eingebetteten Schriften verwendeten Glyphen \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Reduziert die Bildauflösung auf 150 DPI und löscht beschnittene Bildbereiche \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Komprimiert das [Presentation](../../com.aspose.slides/presentation) durch Entfernen nicht verwendeter Masterfolien. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Komprimiert das [Presentation](../../com.aspose.slides/presentation) durch Entfernen nicht verwendeter Layoutfolien. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Komprimiert das [Presentation](../../com.aspose.slides/presentation) durch Entfernen nicht verwendeter Zeichen aus eingebetteten Schriften. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Reduziert die Auflösung von Bildern in der Präsentation und löscht deren beschnittene Bereiche, ähnlich wie PowerPoint's "Compress Pictures" für alle Bilder. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Reduziert die Größe einer Präsentation, indem alle verfügbaren Komprimierungsschritte angewendet werden:

 *  Entfernt nicht verwendete Masterfolien \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Entfernt nicht verwendete Layoutfolien \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Behält nur die tatsächlich in eingebetteten Schriften verwendeten Glyphen \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Reduziert die Bildauflösung auf 150 DPI und löscht beschnittene Bildbereiche \#compressImages(IPresentation,int).compressImages(IPresentation,int).

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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | Die zu komprimierende Präsentation.

--------------------

Um die Komprimierung anzupassen, zum Beispiel um eine andere Bildauflösung zu verwenden oder einen Schritt zu überspringen, rufen Sie die oben aufgeführten Methoden einzeln anstelle dieser Methode auf. Beschnittene Bildbereiche werden dauerhaft entfernt und können in PowerPoint nicht wiederhergestellt werden. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

Komprimiert das [Presentation](../../com.aspose.slides/presentation) durch Entfernen nicht verwendeter Masterfolien.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Die Präsentationsinstanz |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

Komprimiert das [Presentation](../../com.aspose.slides/presentation) durch Entfernen nicht verwendeter Layoutfolien.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Die Präsentationsinstanz |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

Komprimiert das [Presentation](../../com.aspose.slides/presentation) durch Entfernen nicht verwendeter Zeichen aus eingebetteten Schriften.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressEmbeddedFonts(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Die Präsentationsinstanz |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```

Reduziert die Auflösung von Bildern in der Präsentation und löscht deren beschnittene Bereiche, ähnlich wie PowerPoint's "Compress Pictures" für alle Bilder. Bilder auf Folien, Layoutfolien und Masterfolien werden verarbeitet, einschließlich Bilder innerhalb von Gruppierungen und Bildfüllungen von Formen.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Die zu verarbeitende Präsentation. |
| resolution | int | Zielauflösung relativ zu der Größe, in der jedes Bild angezeigt wird. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) lässt Bilder unverändert. |

Bilder, die bereits die Zielauflösung erreichen oder darunter liegen, bleiben unverändert; Bilder werden niemals hochskaliert.

Nicht verarbeitet: Folienhintergründe, Tabellenzellenfüllungen, Diagramme, SmartArt, GIF-Bilder (zur Erhaltung der Animation), SVG- und Metadatei (EMF/WMF)-Bilder.

Beschnittene Bereiche werden dauerhaft entfernt und können in PowerPoint nicht wiederhergestellt werden. |