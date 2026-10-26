---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Klasa kontrolera formatowania używana do osadzania wszystkich czcionek prezentacji w formacie WOFF.
type: docs
url: /pl/com.aspose.slides/embedallfontshtmlcontroller/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

Klasa kontrolera formatowania używana do osadzania wszystkich czcionek prezentacji w formacie WOFF.
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Tworzy nową instancję |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Tworzy nową instancję |
## Metody

| Metoda | Opis |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Wywoływane w celu zapisania nagłówka dokumentu HTML. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Wywoływane w celu zapisania stopki dokumentu HTML. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Wywoływane w celu zapisania nagłówka slajdu HTML. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Wywoływane w celu zapisania stopki slajdu HTML. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wywoływane przed renderowaniem kształtu. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wywoływane przed renderowaniem kształtu. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Zapisz wszystkie czcionki zawarte w [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Zapisuje dane jako base64 bezpośrednio w dokumencie HTML |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```


Tworzy nową instancję

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```


Tworzy nową instancję

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Czcionki, które mają być wyłączone z osadzania |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Wywoływane w celu zapisania nagłówka dokumentu HTML. Wywoływane raz na konwersję prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentacja, która jest aktualnie renderowana. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Wywoływane w celu zapisania stopki dokumentu HTML. Wywoływane raz na konwersję prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentacja, która jest aktualnie renderowana. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Wywoływane w celu zapisania nagłówka slajdu HTML. Wywoływane raz na każdy slajd.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd, który jest aktualnie renderowany. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Wywoływane w celu zapisania stopki slajdu HTML. Wywoływane raz na każdy slajd.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd, który jest aktualnie renderowany. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Wywoływane przed renderowaniem kształtu. Wywoływane raz na każdy kształt. Jeśli ta funkcja zapisze coś do generatora, generowanie obrazu bieżącego slajdu zostanie zakończone, dodany fragment HTML zostanie wstawiony, a nowy obraz zostanie rozpoczęty na wierzchu poprzedniego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt, który ma zostać wyrenderowany. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Wywoływane przed renderowaniem kształtu. Wywoływane raz na każdy kształt. Jeśli ta funkcja zapisze coś do generatora, generowanie obrazu bieżącego slajdu zostanie zakończone, dodany fragment HTML zostanie wstawiony, a nowy obraz zostanie rozpoczęty na wierzchu poprzedniego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt, który został wyrenderowany jako ostatni. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```


Zapisz wszystkie czcionki zawarte w [Presentation](../../com.aspose.slides/presentation).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentacja, która jest aktualnie renderowana. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```


Zapisuje dane jako base64 bezpośrednio w dokumencie HTML

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Generator HTML |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Czcionka do serializacji |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Zastąpiona czcionka (jeśli nastąpiła zamiana czcionki), null w innym wypadku |
| fontStyle | java.lang.String | Styl czcionki |
| fontWeight | java.lang.String | Waga czcionki |
| fontData | byte[] | Dane czcionki |