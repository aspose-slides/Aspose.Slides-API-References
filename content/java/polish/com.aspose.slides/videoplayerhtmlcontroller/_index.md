---
title: VideoPlayerHtmlController
second_title: Aspose.Slides dla Java – odniesienie API
description: Ta klasa umożliwia eksport plików wideo i audio do HTML
type: docs
url: /pl/com.aspose.slides/videoplayerhtmlcontroller/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

Ta klasa umożliwia eksport plików wideo i audio do HTML
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | Tworzy nową instancję kontrolera |
## Metody

| Metoda | Opis |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) |  |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) |  |
| [getUrl(int id, int referrer)](#getUrl-int-int-) |  |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) |  |
### VideoPlayerHtmlController(String path, String fileName, String baseUri) {#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-}
```
public VideoPlayerHtmlController(String path, String fileName, String baseUri)
```


Tworzy nową instancję kontrolera

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka, w której zostaną wygenerowane pliki wideo i audio |
| fileName | java.lang.String | Nazwa pliku HTML |
| baseUri | java.lang.String | Podstawowy URI używany do generowania odnośników |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Wywoływana w celu zapisania nagłówka dokumentu HTML. Wywoływana raz na konwersję prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Wywoływana w celu zapisania stopki dokumentu HTML. Wywoływana raz na konwersję prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Wywoływana w celu zapisania nagłówka slajdu HTML. Wywoływana raz dla każdego slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Wywoływana w celu zapisania stopki slajdu HTML. Wywoływana raz dla każdego slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Wywoływana przed renderowaniem kształtu. Wywoływana raz dla każdego kształtu. Jeśli ta funkcja zapisze coś do generatora, generowanie obrazu bieżącego slajdu zostanie zakończone, dodany fragment HTML zostanie wstawiony, a nowy obraz zostanie rozpoczęty nad poprzednim.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Wywoływana przed renderowaniem kształtu. Wywoływana raz dla każdego kształtu. Jeśli ta funkcja zapisze coś do generatora, generowanie obrazu bieżącego slajdu zostanie zakończone, dodany fragment HTML zostanie wstawiony, a nowy obraz zostanie rozpoczęty nad poprzednim.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```


Ta funkcja jest wywoływana przed renderowaniem kształtu do SVG, aby umożliwić użytkownikowi kontrolę nad wynikowym SVG.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Określa, gdzie obiekt powinien być przechowywany. Ta metoda jest wywoływana raz dla każdego identyfikatora obiektu. Nie ma gwarancji, że nie będzie dwóch obiektów o tych samych danych, semanticName i contentType, ale o różnych identyfikatorach.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**Zwraca:**
int
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```


**Zwraca:** URL do obiektu zewnętrznego. Ta metoda jest zawsze wywoływana, jeśli \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) zwróciło [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) i może być wywołana, jeśli \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) zwróciło [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed), ale osadzenie jest niemożliwe. Może być wywoływana wielokrotnie dla tego samego identyfikatora obiektu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**Zwraca:**
java.lang.String
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```


Zapisuje obiekt zewnętrzny.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |