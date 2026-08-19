---
title: IImageCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een collectie van PPImage voor.
type: docs
url: /nl/com.aspose.slides/iimagecollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Stelt een collectie van PPImage voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert afbeelding op basis van zijn index. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Voeg een afbeelding toe aan een presentatie. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Voeg een afbeelding toe aan een presentatie vanuit een stream. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Maakt en voegt een afbeelding toe aan een presentatie vanuit een stream. |
| [addImage(byte[] buffer)](#addImage-byte---) | Voegt een afbeelding toe aan een presentatie vanuit een opgegeven buffer. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Voegt een kopie van een afbeelding toe van een andere presentatie. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Voeg een afbeelding toe aan een presentatie vanuit SVG-object. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


Retourneert afbeelding op basis van zijn index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index. |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Afbeelding.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


Voeg een afbeelding toe aan een presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Toe te voegen afbeelding.

--------------------

Deze methode converteert WMF/EMF-metabestanden naar raster-PNG-afbeelding voordat ze in een presentatie worden ingevoegd. |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


Voeg een afbeelding toe aan een presentatie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Stream waaruit de afbeelding moet worden toegevoegd.

--------------------

Deze methode kan WMF/EMF-metabestanden toevoegen aan een presentatie zonder ze te converteren naar een raster-PNG-afbeelding. |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Maakt en voegt een afbeelding toe aan een presentatie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Stream waaruit het afbeeldingsbestand moet worden toegevoegd. |
| loadingStreamBehavior | int | Het gedrag dat op de stream wordt toegepast. |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


Voegt een afbeelding toe aan een presentatie vanuit een opgegeven buffer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


Voegt een kopie van een afbeelding toe van een andere presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Bronafbeelding. |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


Voeg een afbeelding toe aan een presentatie vanuit SVG-object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG-afbeeldingsobject [ISvgImage](../../com.aspose.slides/isvgimage) |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.