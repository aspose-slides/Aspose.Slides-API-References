---
title: IHtmlFormattingController
second_title: Aspose.Slides for Java API Reference
description: Kontroluje generowanie pliku html.
type: docs
url: /pl/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Kontroluje generowanie pliku html.
## Metody

| Metoda | Opis |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Wywoływana w celu zapisania nagłówka dokumentu html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Wywoływana w celu zapisania stopki dokumentu html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Wywoływana w celu zapisania nagłówka slajdu html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Wywoływana w celu zapisania stopki slajdu html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wywoływana przed renderowaniem kształtu. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wywoływana przed renderowaniem kształtu. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Wywoływana w celu zapisania nagłówka dokumentu html. Wywoływana raz dla każdej konwersji prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentacja, która jest aktualnie renderowana. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Wywoływana w celu zapisania stopki dokumentu html. Wywoływana raz dla każdej konwersji prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentacja, która jest aktualnie renderowana. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Wywoływana w celu zapisania nagłówka slajdu html. Wywoływana raz dla każdego slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd, który jest aktualnie renderowany. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Wywoływana w celu zapisania stopki slajdu html. Wywoływana raz dla każdego slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd, który jest aktualnie renderowany. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Wywoływana przed renderowaniem kształtu. Wywoływana raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, generowanie obrazu bieżącego slajdu zostanie zakończone, dodany fragment html zostanie wstawiony, a nowy obraz zostanie rozpoczęty na wierzchu poprzedniego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt, który ma być renderowany. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Wywoływana przed renderowaniem kształtu. Wywoływana raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, generowanie obrazu bieżącego slajdu zostanie zakończone, dodany fragment html zostanie wstawiony, a nowy obraz zostanie rozpoczęty na wierzchu poprzedniego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt, który został renderowany jako ostatni. |