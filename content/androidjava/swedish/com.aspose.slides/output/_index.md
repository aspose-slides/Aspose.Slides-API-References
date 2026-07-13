---
title: Output
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av utdataelement för IWebDocument.
type: docs
url: /sv/com.aspose.slides/output/
---
**Inheritance:**
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
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Skapar och lägger till ett utdatafil-element för det angivna teckensnittet. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Lägger till ett utdataelement för textinnehållet. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Kopplar resurs till utdatafil. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Returnerar sökvägen för en given resurs. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Lägger till ett utdataelement för kontextobjektet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Utdataväg. |
| templateKey | java.lang.String | Nyckeln för mallen som används för transformation av kontextobjektet före utdata. |
| contextObject | TContextObject | Kontekstobjekt. |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt för kontextobjektet.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

Lägger till ett utdataelement för bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Utdataväg. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Bild för utdata. |

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
| image | [IImage](../../com.aspose.slides/iimage) | Bild för utdata. |

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
| video | [IVideo](../../com.aspose.slides/ivideo) | Video för utdata. |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt för videon.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Skapar och lägger till ett utdatafil-element för det angivna teckensnittet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Filvägen där teckensnittets utdata kommer att sparas. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Teckensnittsdata som ska skrivas till utdata. |
| fontStyle | int | Stilen för teckensnittet (t.ex. Regular, Bold, Italic). |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - En [IOutputFile](../../com.aspose.slides/ioutputfile)-instans för det genererade teckensnittet.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Lägger till ett utdataelement för textinnehållet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Utdataväg. |
| textContent | java.lang.String | Innehåll för utdata. |

**Returnerar:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt för textinnehållet.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

Kopplar resurs till utdatasfil.

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
java.lang.String - Resurssökväg.