---
title: IImage
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en raster- eller vektorbild.
type: docs
url: /sv/com.aspose.slides/iimage/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Representerar en raster- eller vektorbild.

--------------------

Detta gränssnitt tillhandahåller en gemensam abstraktion för att hantera både raster- och vektorbilder. Implementationer kan variera beroende på den underliggande bildtypen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Sparar bilden till en fil. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Sparar bilden till en fil i angivet format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Sparar bilden till en ström i angivet format. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Sparar bilden till en fil i angivet format och kvalitet. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Sparar bilden till en ström i angivet format och kvalitet. |
| [getSize()](#getSize--) | Hämtar bildens storlek. |
| [getWidth()](#getWidth--) | Hämtar bildens bredd i pixlar. |
| [getHeight()](#getHeight--) | Hämtar bildens höjd i pixlar. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Sparar bilden till en fil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | java.lang.String | Sökvägen till den fil där bilden kommer att sparas. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Sparar bilden till en fil i det angivna formatet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | java.lang.String | Sökvägen till den fil där bilden kommer att sparas. |
| format | int | Bildformatet. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Sparar bilden till en ström i det angivna formatet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Strömmen där bilden kommer att sparas. |
| format | int | Bildformatet. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Sparar bilden till en fil i det angivna formatet och kvaliteten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | java.lang.String | Sökvägen till den fil där bilden kommer att sparas. |
| format | int | Bildformatet. |
| quality | int | Kvaliteten på den sparade bilden (0 till 100). Denna parameter påverkar endast sparande i [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); för alla andra format ignoreras den. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Sparar bilden till en ström i det angivna formatet och kvaliteten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Strömmen där bilden kommer att sparas. |
| format | int | Bildformatet. |
| quality | int | Kvaliteten på den sparade bilden (0 till 100). Denna parameter påverkar endast sparande i [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); för alla andra format ignoreras den. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

Hämtar bildens storlek.

**Returnerar:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Hämtar bildens bredd i pixlar.

**Returnerar:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Hämtar bildens höjd i pixlar.

**Returnerar:**
int