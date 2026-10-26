---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides pro Java API referenci
description: Formátovací řadičová třída používaná k vložení všech písem prezentace ve formátu WOFF.
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

Třída řadiče formátování používaná pro vložení všech písem prezentace ve formátu WOFF.

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Vytvoří novou instanci |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Vytvoří novou instanci |

## Metody

| Metoda | Popis |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Volá se k zápisu hlavičky HTML dokumentu. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Volá se k zápisu patičky HTML dokumentu. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Volá se k zápisu hlavičky HTML snímku. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Volá se k zápisu patičky HTML snímku. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Volá se před vykreslením tvaru. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Volá se před vykreslením tvaru. |
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
| fontNameExcludeList | java.lang.String[] | Písma, která mají být vyloučena z embedování |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Volá se k zápisu hlavičky HTML dokumentu. Volá se jednou na konverzi prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentace, která se právě vykresluje. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Volá se k zápisu patičky HTML dokumentu. Volá se jednou na konverzi prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentace, která se právě vykresluje. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Volá se k zápisu hlavičky HTML snímku. Volá se jednou na každý snímek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek, který se právě vykresluje. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Volá se k zápisu patičky HTML snímku. Volá se jednou na každý snímek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek, který se právě vykresluje. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Volá se před vykreslením tvaru. Volá se jednou na každý tvar. Pokud tato funkce zapíše něco do generátoru, aktuální generování obrázku snímku bude ukončeno, přidá fragment HTML a nový obrázek bude zahájen nad předchozím.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Tvar, který se chystá vykreslit. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Volá se před vykreslením tvaru. Volá se jednou na každý tvar. Pokud tato funkce zapíše něco do generátoru, aktuální generování obrázku snímku bude ukončeno, přidá fragment HTML a nový obrázek bude zahájen nad předchozím.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| shape | [IShape](../../com.aspose.slides/ishape) | Tvar, který byl vykreslen jako poslední. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

Zapíše všechna písma obsažená v [Presentation](../../com.aspose.slides/presentation).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Výstupní objekt. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentace, která se právě vykresluje. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

Zapíše data jako base64 přímo do HTML dokumentu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML generátor |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Písmo k serializaci |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Nahrazené písmo (pokud došlo k nahrazení písma), jinak null |
| fontStyle | java.lang.String | Styl písma |
| fontWeight | java.lang.String | Tloušťka písma |
| fontData | byte[] | Data písma |