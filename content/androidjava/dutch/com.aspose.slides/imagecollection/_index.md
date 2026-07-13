---
title: ImageCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een collectie van PPImage.
type: docs
url: /nl/com.aspose.slides/imagecollection/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Stelt een collectie van PPImage voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Retourneert een aantal afbeeldingen in de collectie. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Voegt een kopie van een afbeelding uit een andere presentatie toe. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Voeg een afbeelding toe aan een presentatie. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Voeg een afbeelding toe aan een presentatie vanuit een stream. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Maakt een afbeelding en voegt deze toe aan een presentatie vanuit een stream. |
| [addImage(byte[] buffer)](#addImage-byte---) | Voeg een afbeelding toe aan een presentatie vanuit een opgegeven buffer. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Voeg een afbeelding toe aan een presentatie vanuit een Svg-object. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen uit de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
### size() {#size--}
```
public final int size()
```

Retourneert een aantal afbeeldingen in de collectie. Alleen-lezen  int .

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [IPPImage](../../com.aspose.slides/ippimage).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

Voegt een kopie van een afbeelding uit een andere presentatie toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Bronafbeelding. |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

Voeg een afbeelding toe aan een presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Afbeelding om toe te voegen.

--------------------

Deze methode converteert WMF/EMF-metabestanden naar een raster-PNG-afbeelding voordat ze in een presentatie worden ingevoegd. |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

Voeg een afbeelding toe aan een presentatie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Stream van waaruit de afbeelding wordt toegevoegd.

--------------------

Deze methode kan WMF/EMF-metabestanden aan een presentatie toevoegen zonder ze te converteren naar een raster-PNG-afbeelding. |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Maakt een afbeelding en voegt deze toe aan een presentatie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Stream van waaruit het afbeeldingsbestand wordt toegevoegd. |
| loadingStreamBehavior | int | Het gedrag dat op de stream wordt toegepast. |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

Voeg een afbeelding toe aan een presentatie vanuit een opgegeven buffer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Voeg een afbeelding toe aan een presentatie vanuit een Svg-object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Svg-afbeeldingsobject [ISvgImage](../../com.aspose.slides/isvgimage) |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

Retourneert een enumerator die door de collectie itereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Een java.util.Iterator voor de volledige collectie.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert alle elementen uit de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doel-array. |
| index | int | Start-index in de doel-array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen  boolean .

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatiewortel. Alleen-lezen  Object .

**Retour:**
java.lang.Object