---
title: IImageCollection
second_title: Aspose.Slides voor Android via Java API-referentie
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
| [get_Item(int index)](#get-Item-int-) | Returns image by its index. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Add an image to a presentation. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Add an image to a presentation from stream. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Creates and adds an image to a presentation from stream. |
| [addImage(byte[] buffer)](#addImage-byte---) | Adds an image to a presentation from specified buffer. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Adds a copy of an image from an another presentation. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Add an image to a presentation from SVG object. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

Retourneert de afbeelding op zijn index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index. |

**Retourneert:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
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

Deze methode converteert WMF/EMF-metabestanden naar een raster-PNG-afbeelding voordat deze aan een presentatie wordt toegevoegd. |

**Retourneert:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

Voeg een afbeelding toe aan een presentatie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Stream waaruit de afbeelding wordt toegevoegd.

--------------------

Deze methode kan WMF/EMF-metabestanden aan een presentatie toevoegen zonder ze om te zetten naar een raster-PNG-afbeelding. |

**Retourneert:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Creëert en voegt een afbeelding toe aan een presentatie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Stream waaruit het afbeeldingsbestand wordt toegevoegd. |
| loadingStreamBehavior | int | Het gedrag dat op de stream wordt toegepast. |

**Retourneert:**
[IPPImage](../../com.aspose.slides/ippimage) - Added [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

Voegt een afbeelding toe aan een presentatie vanuit een opgegeven buffer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Retourneert:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

Voegt een kopie van een afbeelding toe uit een andere presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Bronafbeelding. |

**Retourneert:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

Voeg een afbeelding toe aan een presentatie vanuit een SVG-object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG-afbeeldingsobject [ISvgImage](../../com.aspose.slides/isvgimage) |

**Retourneert:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.