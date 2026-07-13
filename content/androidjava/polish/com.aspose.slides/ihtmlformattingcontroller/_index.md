---
title: IHtmlFormattingController
second_title: Aspose.Slides dla Androida przez Java API
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
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wywoływana przed renderowaniem shape. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Wywoływana przed renderowaniem shape. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Wywoływana w celu zapisania nagłówka dokumentu html. Wywoływana raz na konwersję prezentacji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentacja aktualnie renderowana. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Wywoływana w celu zapisania stopki dokumentu html. Wywoływana raz na konwersję prezentacji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentacja aktualnie renderowana. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Wywoływana w celu zapisania nagłówka slajdu html. Wywoływana raz na każdy slajd.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd aktualnie renderowany. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Wywoływana w celu zapisania stopki slajdu html. Wywoływana raz na każdy slajd.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd aktualnie renderowany. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Wywoływana przed renderowaniem shape. Wywoływana raz na każdy shape. Jeśli ta funkcja zapisze cokolwiek do generatora, generowanie obrazu bieżącego slajdu zostanie zakończone, dodany fragment html zostanie wstawiony i nowy obraz zostanie rozpoczęty na wierzchu poprzedniego.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape, które ma zostać wyrenderowane. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Wywoływana przed renderowaniem shape. Wywoływana raz na każdy shape. Jeśli ta funkcja zapisze cokolwiek do generatora, generowanie obrazu bieżącego slajdu zostanie zakończone, dodany fragment html zostanie wstawiony i nowy obraz zostanie rozpoczęty na wierzchu poprzedniego.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Obiekt wyjściowy. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape, które jest renderowane jako ostatnie. |