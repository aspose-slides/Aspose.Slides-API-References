---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Controls a html file generation.
type: docs
url: /fr/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Contrôle la génération d’un fichier HTML.
## Méthodes

| Méthode | Description |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Called to write html document header. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Called to write html document footer. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Called to write html slide header. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Called to write html slide footer. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Called before shape's rendering. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Called before shape's rendering. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Appelé pour écrire l’en-tête du document HTML. Appelé une fois par conversion de présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Output object. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation which being currently rendered. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Appelé pour écrire le pied de page du document HTML. Appelé une fois par conversion de présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Output object. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation which being currently rendered. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Appelé pour écrire l’en-tête de la diapositive HTML. Appelé une fois pour chaque diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Output object. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide which being currently rendered. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Appelé pour écrire le pied de page de la diapositive HTML. Appelé une fois pour chaque diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Output object. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide which being currently rendered. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l’image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image commencera au-dessus de la précédente.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Output object. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape which is about to render. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l’image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image commencera au-dessus de la précédente.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Output object. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape which is rendered last. |