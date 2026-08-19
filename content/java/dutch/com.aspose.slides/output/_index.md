---
title: Output
second_title: Aspose.Slides voor Java API-referentie
description: Geeft een verzameling uitvoerelementen weer voor IWebDocument.
type: docs
url: /nl/com.aspose.slides/output/
---
**Erfenis:**
java.lang.Object
```
public final class Output
```

Geeft een verzameling uitvoerelementen weer voor IWebDocument.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Voegt een uitvoerelement toe voor het contextobject. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Voegt een uitvoerelement toe voor de afbeelding. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Voegt een uitvoerelement toe voor de afbeelding. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Voegt een uitvoerelement toe voor de video. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | Voegt een uitvoerelement toe voor de audio. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Creëert en voegt een uitvoerbestandselement toe voor het opgegeven lettertype. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Voegt een uitvoerelement toe voor de tekstinhoud. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Bindt resource aan uitvoerbestand. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Retourneert het pad voor een gegeven resource. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Voegt een uitvoerelement toe voor het contextobject.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Uitvoerpad. |
| templateKey | java.lang.String | De sleutel van de sjabloon die wordt gebruikt voor contextobjecttransformatie vóór output. |
| contextObject | TContextObject | Contextobject. |

**Retourneert:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object voor het contextobject.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

Voegt een uitvoerelement toe voor de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Uitvoerpad. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Afbeelding voor uitvoer. |

**Retourneert:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object voor de afbeelding.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

Voegt een uitvoerelement toe voor de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Uitvoerpad. |
| image | [IImage](../../com.aspose.slides/iimage) | Afbeelding voor uitvoer. |

**Retourneert:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object voor de afbeelding.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

Voegt een uitvoerelement toe voor de video.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Uitvoerpad. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video voor uitvoer. |

**Retourneert:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object voor de video.
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```

Voegt een uitvoerelement toe voor de audio.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Uitvoerpad. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio voor uitvoer. |

**Retourneert:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object voor de audio.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Creëert en voegt een uitvoerbestandselement toe voor het opgegeven lettertype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Het bestandspad waar de lettertype-output zal worden opgeslagen. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | De lettertypegegevens die naar de uitvoer moeten worden geschreven. |
| fontStyle | int | De stijl van het lettertype (bijv. Regular, Bold, Italic). |

**Retourneert:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Een [IOutputFile](../../com.aspose.slides/ioutputfile) instantie voor het gegenereerde lettertype.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Voegt een uitvoerelement toe voor de tekstinhoud.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Uitvoerpad. |
| textContent | java.lang.String | Inhoud om uit te voeren. |

**Retourneert:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object voor de tekstinhoud.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

Bindt resource aan uitvoerbestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Uitvoerbestand. |
| obj | java.lang.Object | Resource-object. |
### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

Retourneert het pad voor een gegeven resource.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Resource-object. |

**Retourneert:**
java.lang.String - Resourcepad.