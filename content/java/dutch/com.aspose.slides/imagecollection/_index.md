---
title: ImageCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een verzameling van PPImage voor.
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

Stelt een verzameling PPImage voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Retourneert het aantal afbeeldingen in de collectie. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op bij de opgegeven index. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Voegt een kopie van een afbeelding toe vanuit een andere presentatie. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Voegt een afbeelding toe aan een presentatie. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Voegt een afbeelding toe aan een presentatie vanuit een stream. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Maakt een afbeelding aan en voegt deze toe aan een presentatie vanuit een stream. |
| [addImage(byte[] buffer)](#addImage-byte---) | Voegt een afbeelding toe aan een presentatie vanuit een opgegeven buffer. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Voegt een afbeelding toe aan een presentatie vanuit een Svg-object. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
### size() {#size--}
```
public final int size()
```


Retourneert het aantal afbeeldingen in de collectie. Alleen-lezen  int .

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```


Haalt het element op bij de opgegeven index. Alleen-lezen [IPPImage](../../com.aspose.slides/ippimage).

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


Voegt een kopie van een afbeelding toe vanuit een andere presentatie.

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


Voegt een afbeelding toe aan een presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Afbeelding om toe te voegen.

--------------------

Deze methode converteert WMF/EMF-metabestanden naar raster PNG-afbeelding voordat ze in een presentatie worden ingevoegd. |
**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```


Voegt een afbeelding toe aan een presentatie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Stream om afbeelding vanuit toe te voegen.

--------------------

Deze methode kan WMF/EMF-metabestanden aan een presentatie toevoegen zonder ze te converteren naar raster PNG-afbeelding. |
**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde afbeelding.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Maakt een afbeelding aan en voegt deze toe aan een presentatie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Stream om afbeeldingbestand van toe te voegen. |
| loadingStreamBehavior | int | Het gedrag dat op de stream zal worden toegepast. |

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Toegevoegde [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```


Voegt een afbeelding toe aan een presentatie vanuit een opgegeven buffer.

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


Voegt een afbeelding toe aan een presentatie vanuit een Svg-object.

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


Retourneert een enumerator die door de collectie iterereert.

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


Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doel-array. |
| index | int | Beginindex in de doel-array. |

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