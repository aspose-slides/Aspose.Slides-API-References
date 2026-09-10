---
title: Output
second_title: Aspose.Slides för Android via Java API-referens
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
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Lägger till ett utdataelement för kontextobjektet. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Lägger till ett utdataelement för bilden. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Lägger till ett utdataelement för bilden. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Lägger till ett utdataelement för videon. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | Lägger till ett utdataelement för ljudet. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Skapar och lägger till ett utdatafilselement för det angivna teckensnittet. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Lägger till ett utdataelement för textinnehållet. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Binder resurs till utdatafil. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Returnerar sökvägen för en given resurs. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Lägger till ett utdataelement för kontextobjektet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Sökväg för utdata. |
| templateKey | java.lang.String | Nyckeln för mallen som används för kontextobjektstransformation före utdata. |
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
| path | java.lang.String | Sökväg för utdata. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Bild att outputa. |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the image.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

Lägger till ett utdataelement för bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Sökväg för utdata. |
| image | [IImage](../../com.aspose.slides/iimage) | Bild att outputa. |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the image.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

Lägger till ett utdataelement för videon.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Sökväg för utdata. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video att outputa. |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the video.
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```

Lägger till ett utdataelement för ljudet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Sökväg för utdata. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Ljud att outputa. |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the audio.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Skapar och lägger till ett utdatafilselement för det angivna teckensnittet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Filens sökväg där teckensnittets utdata kommer att sparas. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Teckensnittsdata som ska skrivas till utdata. |
| fontStyle | int | Stilen för teckensnittet (t.ex. Regular, Bold, Italic). |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - En [IOutputFile](../../com.aspose.slides/ioutputfile) instans för det genererade teckensnittet.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Lägger till ett utdataelement för textinnehållet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Sökväg för utdata. |
| textContent | java.lang.String | Innehåll att outputa. |

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
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Utdatasfil. |
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
java.lang.String - Resursens sökväg.