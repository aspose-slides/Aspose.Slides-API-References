---
title: EmbedAllFontsHtmlController
second_title: Référence API Java d'Aspose.Slides pour Android
description: La classe de contrôleur de mise en forme à utiliser pour intégrer toutes les polices de la présentation au format WOFF.
type: docs
url: /fr/com.aspose.slides/embedallfontshtmlcontroller/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

La classe de contrôleur de mise en forme à utiliser pour intégrer toutes les polices de la présentation au format WOFF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Crée une nouvelle instance |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Crée une nouvelle instance |
## Méthodes

| Méthode | Description |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Appelé pour écrire l’en-tête du document html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Appelé pour écrire le pied de page du document html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Appelé pour écrire l’en-tête de la diapositive html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Appelé pour écrire le pied de page de la diapositive html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Appelé avant le rendu de la forme. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Appelé avant le rendu de la forme. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Écrire toutes les polices contenues dans [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Écrit les données en base64 dans le document HTML lui-même |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```


Crée une nouvelle instance

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```


Crée une nouvelle instance

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Polices à exclure de l’intégration |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Appelé pour écrire l’en-tête du document html. Appelé une fois par conversion de présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objet de sortie. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Présentation en cours de rendu. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Appelé pour écrire le pied de page du document html. Appelé une fois par conversion de présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objet de sortie. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Présentation en cours de rendu. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Appelé pour écrire l’en-tête de la diapositive html. Appelé une fois par chaque diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objet de sortie. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive en cours de rendu. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Appelé pour écrire le pied de page de la diapositive html. Appelé une fois par chaque diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objet de sortie. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive en cours de rendu. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Appelé avant le rendu de la forme. Appelé une fois par chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l’image de la diapositive courante sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objet de sortie. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forme sur le point d’être rendue. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Appelé avant le rendu de la forme. Appelé une fois par chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l’image de la diapositive courante sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objet de sortie. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forme rendue en dernier. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```


Écrire toutes les polices contenues dans [Presentation](../../com.aspose.slides/presentation).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objet de sortie. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Présentation en cours de rendu. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```


Écrit les données en base64 dans le document HTML lui-même

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Générateur HTML |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Police à sérialiser |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Police substituée (si substitution de police a eu lieu), sinon null |
| fontStyle | java.lang.String | Style de police |
| fontWeight | java.lang.String | Épaisseur de police |
| fontData | byte[] | Données de police |