---
title: Output
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av utdataelement för IWebDocument.
type: docs
url: /sv/com.aspose.slides/output/
---
**Arv:**
java.lang.Object
```
public final class Output
```

Representerar en samling av utdataelement för IWebDocument.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Adds an output element for the context object. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Adds an output element for the image. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Adds an output element for the image. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Adds an output element for the video. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | Adds an output element for the audio. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Creates and adds an output file element for the specified font. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Adds an output element for the text content. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Binds resource to output file. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Returns the path for a given resource. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```


Lägger till ett utdataelement för kontextobjektet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Utdataväg. |
| templateKey | java.lang.String | Nyckeln för mallen som används för kontextobjektstransformation före utskrift. |
| contextObject | TContextObject | Kontextobjekt. |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the context object.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```


Lägger till ett utdataelement för bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Utdataväg. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Bild att skriva ut. |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt för bilden.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```


Lägger till ett utdataelement för bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Utdataväg. |
| image | [IImage](../../com.aspose.slides/iimage) | Bild att skriva ut. |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt för bilden.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```


Lägger till ett utdataelement för videon.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Utdataväg. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video att skriva ut. |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt för videon.
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```


Lägger till ett utdataelement för ljudet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Utdataväg. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Ljud att skriva ut. |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt för ljudet.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```


Skapar och lägger till ett utdatafilselement för den angivna fonten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Filsökvägen där fontutdata kommer att sparas. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Fontdata som ska skrivas till utdata. |
| fontStyle | int | Stilen på fonten (e.g., Regular, Bold, Italic). |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - En [IOutputFile](../../com.aspose.slides/ioutputfile) instans för den genererade fonten.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```


Lägger till ett utdataelement för textinnehållet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Utdataväg. |
| textContent | java.lang.String | Innehåll att skriva ut. |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt för textinnehållet.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```


Binder resurs till utdatafil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Utdatafil. |
| obj | java.lang.Object | Resursobjekt. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```


Returnerar sökvägen för en given resurs.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Resursobjekt. |

**Returnerar:**
java.lang.String - Resursväg.