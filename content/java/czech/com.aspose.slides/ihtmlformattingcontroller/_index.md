---
title: IHtmlFormattingController
second_title: Aspose.Slides for Java API Reference
description: Řídí generování html souboru.
type: docs
url: /cs/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Řídí generování html souboru.
## Metody

| Metoda | Popis |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Voláno pro zápis hlavičky html dokumentu. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Voláno pro zápis patičky html dokumentu. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Voláno pro zápis hlavičky html snímku. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Voláno pro zápis patičky html snímku. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Voláno před vykreslením tvaru. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Voláno před vykreslením tvaru. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Voláno pro zápis hlavičky html dokumentu. Voláno jednou při převodu prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentace, která je aktuálně vykreslována. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Voláno pro zápis patičky html dokumentu. Voláno jednou při převodu prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentace, která je aktuálně vykreslována. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Voláno pro zápis hlavičky html snímku. Voláno jednou pro každý snímek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek, který je aktuálně vykreslován. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Voláno pro zápis patičky html snímku. Voláno jednou pro každý snímek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek, který je aktuálně vykreslován. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Voláno před vykreslením tvaru. Voláno jednou pro každý tvar. Pokud tato funkce zapíše cokoliv do generátoru, bude aktuální generování obrázku snímku ukončeno, přidaný html fragment vložen a nový obrázek bude zahájen nad předchozím.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Tvar, který se bude vykreslovat. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Voláno před vykreslením tvaru. Voláno jednou pro každý tvar. Pokud tato funkce zapíše cokoliv do generátoru, bude aktuální generování obrázku snímku ukončeno, přidaný html fragment vložen a nový obrázek bude zahájen nad předchozím.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Tvar, který byl vykreslen jako poslední. |