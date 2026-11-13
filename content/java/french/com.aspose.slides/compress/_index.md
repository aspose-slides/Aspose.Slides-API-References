---
title: Compress
second_title: Référence API Aspose.Slides pour Java
description: Représente un groupe de méthodes destiné à compresser .
type: docs
url: /fr/com.aspose.slides/compress/
---
**Héritage :**
java.lang.Object
```
public class Compress
```

Représente un groupe de méthodes destinées à compresser [Presentation](../../com.aspose.slides/presentation).

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
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Compress()](#Compress--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Réduit la taille d'une présentation en appliquant toutes les étapes de compression disponibles :

 *  Supprime les diapositives maîtres inutilisées \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Supprime les diapositives de mise en page inutilisées \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Conserve uniquement les glyphes réellement utilisés dans les polices incorporées \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Réduit la résolution des images à 150 DPI et supprime les zones découpées des images \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Effectue la compression du [Presentation](../../com.aspose.slides/presentation) en supprimant les diapositives maîtres inutilisées. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Effectue la compression du [Presentation](../../com.aspose.slides/presentation) en supprimant les diapositives de mise en page inutilisées. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Effectue la compression du [Presentation](../../com.aspose.slides/presentation) en supprimant les caractères inutilisés des polices incorporées. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Réduit la résolution des images dans la présentation et supprime leurs zones découpées, similaire à « Compress Pictures » de PowerPoint appliqué à toutes les images. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Réduit la taille d'une présentation en appliquant toutes les étapes de compression disponibles :

 *  Supprime les diapositives maîtres inutilisées \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Supprime les diapositives de mise en page inutilisées \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Conserve uniquement les glyphes réellement utilisés dans les polices incorporées \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Réduit la résolution des images à 150 DPI et supprime les zones découpées des images \#compressImages(IPresentation,int).compressImages(IPresentation,int).

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | La présentation à compresser.

--------------------

Pour personnaliser la compression, par exemple pour utiliser une résolution d'image différente ou pour ignorer une étape, appelez les méthodes listées ci-dessus individuellement au lieu de celle-ci. Les zones découpées des images sont supprimées de façon permanente et ne peuvent pas être restaurées dans PowerPoint. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Effectue la compression du [Presentation](../../com.aspose.slides/presentation) en supprimant les diapositives maîtres inutilisées.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | L'instance de présentation |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Effectue la compression du [Presentation](../../com.aspose.slides/presentation) en supprimant les diapositives de mise en page inutilisées.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | L'instance de présentation |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Effectue la compression du [Presentation](../../com.aspose.slides/presentation) en supprimant les caractères inutilisés des polices incorporées.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | L'instance de présentation |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```


Réduit la résolution des images dans la présentation et supprime leurs zones découpées, similaire à « Compress Pictures » de PowerPoint appliqué à toutes les images. Les images sur les diapositives, les diapositives de mise en page et les diapositives maîtres sont traitées, y compris les images à l'intérieur des formes groupées et les remplissages d'images des formes.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | La présentation à traiter. |
| resolution | int | Résolution cible relative à la taille à laquelle chaque image est affichée. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) laisse les images inchangées.

--------------------

Les images déjà à la résolution cible ou en dessous restent inchangées ; les images ne sont jamais agrandies.

Non traitées : arrière-plans de diapositives, remplissages de cellules de tableau, graphiques, SmartArt, images GIF (pour préserver l'animation), images SVG et métafichiers (EMF/WMF).

Les zones découpées sont supprimées de façon permanente et ne peuvent pas être restaurées dans PowerPoint. |