---
title: IImage
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt ein Raster- oder Vektorbild dar.
type: docs
url: /de/com.aspose.slides/iimage/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Stellt ein Raster- oder Vektorbild dar.

--------------------

Dieses Interface bietet eine gemeinsame Abstraktion für die Handhabung von Raster- und Vektor-Bildern. Implementierungen können je nach zugrunde liegendem Bildtyp variieren.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Saves the image to a file. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Saves the image to a file in the specified format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Saves the image to a stream in the specified format. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Saves the image to a file in the specified format and quality. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Saves the image to a stream in the specified format and quality. |
| [getSize()](#getSize--) | Gets the size of the image. |
| [getWidth()](#getWidth--) | Gets the width of the image in pixels. |
| [getHeight()](#getHeight--) | Gets the height of the image in pixels. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Speichert das Bild in einer Datei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | java.lang.String | Der Pfad zu der Datei, in der das Bild gespeichert wird. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Speichert das Bild in einer Datei im angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | java.lang.String | Der Pfad zu der Datei, in der das Bild gespeichert wird. |
| format | int | Das Bildformat. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Speichert das Bild in einem Stream im angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Stream, in dem das Bild gespeichert wird. |
| format | int | Das Bildformat. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Speichert das Bild in einer Datei im angegebenen Format und Qualität.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | java.lang.String | Der Pfad zu der Datei, in der das Bild gespeichert wird. |
| format | int | Das Bildformat. |
| quality | int | Die Qualität des gespeicherten Bildes (0 bis 100). Dieser Parameter wirkt sich nur auf das Speichern in [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) aus; für alle anderen Formate wird er ignoriert. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Speichert das Bild in einem Stream im angegebenen Format und Qualität.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Stream, in dem das Bild gespeichert wird. |
| format | int | Das Bildformat. |
| quality | int | Die Qualität des gespeicherten Bildes (0 bis 100). Dieser Parameter wirkt sich nur auf das Speichern in [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) aus; für alle anderen Formate wird er ignoriert. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

Ermittelt die Größe des Bildes.

**Rückgabewert:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Ermittelt die Breite des Bildes in Pixeln.

**Rückgabewert:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Ermittelt die Höhe des Bildes in Pixeln.

**Rückgabewert:**
int