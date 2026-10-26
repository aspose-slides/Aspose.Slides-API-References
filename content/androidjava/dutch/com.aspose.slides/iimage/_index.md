---
title: IImage
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een raster- of vectorafbeelding voor.
type: docs
url: /nl/com.aspose.slides/iimage/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Stelt een raster- of vectorafbeelding voor.

--------------------

Deze interface biedt een algemene abstractie voor het verwerken van zowel raster- als vectorafbeeldingen. Implementaties kunnen variëren afhankelijk van het onderliggende afbeeldings type.
## Methods

| Methode | Beschrijving |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Slaat de afbeelding op in een bestand. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Slaat de afbeelding op in een bestand in het opgegeven formaat. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Slaat de afbeelding op in een stream in het opgegeven formaat. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Slaat de afbeelding op in een bestand in het opgegeven formaat en kwaliteit. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Slaat de afbeelding op in een stream in het opgegeven formaat en kwaliteit. |
| [getSize()](#getSize--) | Haalt de grootte van de afbeelding op. |
| [getWidth()](#getWidth--) | Haalt de breedte van de afbeelding op in pixels. |
| [getHeight()](#getHeight--) | Haalt de hoogte van de afbeelding op in pixels. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```


Slaat de afbeelding op in een bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | java.lang.String | Het pad naar het bestand waarin de afbeelding wordt opgeslagen. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```


Slaat de afbeelding op in een bestand in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | java.lang.String | Het pad naar het bestand waarin de afbeelding wordt opgeslagen. |
| format | int | Het afbeeldingsformaat. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```


Slaat de afbeelding op in een stream in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | De stream waarin de afbeelding wordt opgeslagen. |
| format | int | Het afbeeldingsformaat. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```


Slaat de afbeelding op in een bestand in het opgegeven formaat en kwaliteit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | java.lang.String | Het pad naar het bestand waarin de afbeelding wordt opgeslagen. |
| format | int | Het afbeeldingsformaat. |
| quality | int | De kwaliteit van de opgeslagen afbeelding (0 tot 100). Deze parameter heeft alleen invloed op het opslaan in [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); voor alle andere formaten wordt deze genegeerd. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```


Slaat de afbeelding op in een stream in het opgegeven formaat en kwaliteit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | De stream waarin de afbeelding wordt opgeslagen. |
| format | int | Het afbeeldingsformaat. |
| quality | int | De kwaliteit van de opgeslagen afbeelding (0 tot 100). Deze parameter heeft alleen invloed op het opslaan in [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); voor alle andere formaten wordt deze genegeerd. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```


Haalt de grootte van de afbeelding op.

**Retourneert:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Haalt de breedte van de afbeelding op in pixels.

**Retourneert:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Haalt de hoogte van de afbeelding op in pixels.

**Retourneert:**
int