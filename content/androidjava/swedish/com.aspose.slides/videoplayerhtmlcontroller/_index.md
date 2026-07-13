---
title: VideoPlayerHtmlController
second_title: Aspose.Slides för Android via Java API-referens
description: Denna klass möjliggör export av video- och ljudfiler till en HTML
type: docs
url: /sv/com.aspose.slides/videoplayerhtmlcontroller/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

Denna klass möjliggör export av video- och ljudfiler till en HTML
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | Skapar en ny instans av kontroller |
## Metoder

| Metod | Beskrivning |
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


Skapar en ny instans av kontroller

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Sökvägen där video- och ljudfiler kommer att genereras |
| fileName | java.lang.String | Namnet på HTML-filen |
| baseUri | java.lang.String | Den bas-URI som kommer att användas för att generera länkar |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Kallas för att skriva HTML-dokumentets rubrik. Kallas en gång per presentationkonvertering.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Kallas för att skriva HTML-dokumentets fot. Kallas en gång per presentationkonvertering.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Kallas för att skriva HTML-bildens rubrik. Kallas en gång för varje bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Kallas för att skriva HTML-bildens fot. Kallas en gång för varje bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Kallas före shape's rendering. Kallas en gång för varje shape. Om denna funktion skriver något till generator, avslutas den aktuella bildens bildgenerering, det tillagda HTML-fragmentet infogas och en ny bild startas ovanpå den föregående.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Kallas före shape's rendering. Kallas en gång för varje shape. Om denna funktion skriver något till generator, avslutas den aktuella bildens bildgenerering, det tillagda HTML-fragmentet infogas och en ny bild startas ovanpå den föregående.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```


Denna funktion kallas före rendering av shape till SVG för att låta användaren styra den resulterande SVG:n.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Fastställer var objektet ska lagras. Denna metod kallas en gång för varje objekt-id. Det garanteras inte att det inte finns två objekt med samma data, semanticName och contentType men med olika id.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**Returnerar:**
int
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```


Returnerar en URL till ett externt objekt. Denna metod kallas alltid om \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) returnerade [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) och kan kallas om \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) returnerade [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) men inbäddning är omöjlig. Kan kallas flera gånger för samma objekt-id.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**Returnerar:**
java.lang.String
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```


Sparar ett externt objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |