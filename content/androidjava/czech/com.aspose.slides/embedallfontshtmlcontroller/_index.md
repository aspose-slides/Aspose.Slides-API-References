---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Formátovací řídící třída používaná pro vložení všech písem prezentace ve formátu WOFF.
type: docs
url: /cs/com.aspose.slides/embedallfontshtmlcontroller/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

Formátovací řídící třída používaná pro vložení všech písem prezentace ve formátu WOFF.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Vytvoří novou instanci |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Vytvoří novou instanci |
## Metody

| Metoda | Popis |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Voláno pro zápis hlavičky html dokumentu. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Voláno pro zápis patičky html dokumentu. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Voláno pro zápis hlavičky html snímku. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Voláno pro zápis patičky html snímku. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Voláno před vykreslením tvaru. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Voláno před vykreslením tvaru. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Zapíše všechna písma obsažená v [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Zapíše data jako base64 přímo do HTML dokumentu |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```


Vytvoří novou instanci

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```


Vytvoří novou instanci

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Písma, která mají být vynechána při vkládání |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Voláno pro zápis hlavičky html dokumentu. Voláno jednou během konverze prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentace, která je právě vykreslována. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Voláno pro zápis patičky html dokumentu. Voláno jednou během konverze prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentace, která je právě vykreslována. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Voláno pro zápis hlavičky html snímku. Voláno jednou pro každý snímek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek, který je právě vykreslován. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Voláno pro zápis patičky html snímku. Voláno jednou pro každý snímek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek, který je právě vykreslován. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Voláno před vykreslením tvaru. Voláno jednou pro každý tvar. Pokud tato funkce zapíše něco do generátoru, generování obrázku aktuálního snímku bude ukončeno, přidaný html fragment vložen a nový obrázek bude zahájen nad předchozím.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Tvar, který se má vykreslit. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Voláno před vykreslením tvaru. Voláno jednou pro každý tvar. Pokud tato funkce zapíše něco do generátoru, generování obrázku aktuálního snímku bude ukončeno, přidaný html fragment vložen a nový obrázek bude zahájen nad předchozím.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Tvar, který byl vykreslen naposledy. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```


Zapíše všechna písma obsažená v [Presentation](../../com.aspose.slides/presentation).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentace, která je právě vykreslována. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```


Zapíše data jako base64 přímo do HTML dokumentu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML generátor |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Písmo k serializaci |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Substituované písmo (pokud došlo k substituci písma), null jinak |
| fontStyle | java.lang.String | Styl písma |
| fontWeight | java.lang.String | Váha písma |
| fontData | byte[] | Data písma |