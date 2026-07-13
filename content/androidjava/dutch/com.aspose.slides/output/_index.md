---
title: Output
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie output-elementen voor IWebDocument voor.
type: docs
url: /nl/com.aspose.slides/output/
---
**Inheritance:**
java.lang.Object
```
public final class Output
```

Stelt een collectie output-elementen voor IWebDocument voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Voegt een output-element toe voor het contextobject. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Voegt een output-element toe voor de afbeelding. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Voegt een output-element toe voor de afbeelding. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Voegt een output-element toe voor de video. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Creëert en voegt een output-bestandselement toe voor het opgegeven lettertype. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Voegt een output-element toe voor de tekstinhoud. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Bindt resource aan output-bestand. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Geeft het pad terug voor een opgegeven resource. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```


Voegt een output-element toe voor het contextobject.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Uitvoerpad. |
| templateKey | java.lang.String | De sleutel van de sjabloon die wordt gebruikt voor de transformatie van het contextobject vóór de uitvoer. |
| contextObject | TContextObject | Contextobject. |

**Retourwaarde:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object voor het contextobject.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```


Voegt een output-element toe voor de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Uitvoerpad. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Afbeelding voor uitvoer. |

**Retourwaarde:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object voor de afbeelding.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```


Voegt een output-element toe voor de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Uitvoerpad. |
| image | [IImage](../../com.aspose.slides/iimage) | Afbeelding voor uitvoer. |

**Retourwaarde:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object voor de afbeelding.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```


Voegt een output-element toe voor de video.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Uitvoerpad. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video voor uitvoer. |

**Retourwaarde:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object voor de video.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```


Creëert en voegt een output-bestandselement toe voor het opgegeven lettertype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Het bestandspad waar de font-uitvoer wordt opgeslagen. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | De font-gegevens die naar de uitvoer moeten worden geschreven. |
| fontStyle | int | De stijl van het lettertype (bijv. Regular, Bold, Italic). |

**Retourwaarde:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - een [IOutputFile](../../com.aspose.slides/ioutputfile)-instantie voor het gegenereerde lettertype.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```


Voegt een output-element toe voor de tekstinhoud.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Uitvoerpad. |
| textContent | java.lang.String | Inhoud om uit te voeren. |

**Retourwaarde:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object voor de tekstinhoud.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```


Bindt resource aan output-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Output-bestand. |
| obj | java.lang.Object | Resource-object. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```


Geeft het pad terug voor een opgegeven resource.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Resource-object. |

**Retourwaarde:**
java.lang.String - Resource-pad.