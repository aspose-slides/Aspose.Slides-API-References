---
title: IImage
second_title: Aspose.Slides für Java API-Referenz
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

Dieses Interface bietet eine gemeinsame Abstraktion zur Verarbeitung von Raster- und Vektorbildern. Implementierungen können je nach zugrunde liegendem Bildtyp variieren.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Speichert das Bild in einer Datei. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Speichert das Bild in einer Datei im angegebenen Format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Speichert das Bild in einem Stream im angegebenen Format. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Speichert das Bild in einer Datei im angegebenen Format und mit Qualität. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Speichert das Bild in einem Stream im angegebenen Format und mit Qualität. |
| [getSize()](#getSize--) | Ermittelt die Größe des Bildes. |
| [getWidth()](#getWidth--) | Ermittelt die Breite des Bildes in Pixeln. |
| [getHeight()](#getHeight--) | Ermittelt die Höhe des Bildes in Pixeln. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Speichert das Bild in einer Datei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | java.lang.String | Der Pfad zur Datei, in die das Bild gespeichert wird. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Speichert das Bild in einer Datei im angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | java.lang.String | Der Pfad zur Datei, in die das Bild gespeichert wird. |
| format | int | Das Bildformat. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Speichert das Bild in einem Stream im angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Stream, in den das Bild gespeichert wird. |
| format | int | Das Bildformat. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Speichert das Bild in einer Datei im angegebenen Format und mit Qualität.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | java.lang.String | Der Pfad zur Datei, in die das Bild gespeichert wird. |
| format | int | Das Bildformat. |
| quality | int | Die Qualität des gespeicherten Bildes (0 bis 100). Dieser Parameter wirkt sich nur auf das Speichern in [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) aus; für alle anderen Formate wird er ignoriert. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Speichert das Bild in einem Stream im angegebenen Format und mit Qualität.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Stream, in den das Bild gespeichert wird. |
| format | int | Das Bildformat. |
| quality | int | Die Qualität des gespeicherten Bildes (0 bis 100). Dieser Parameter wirkt sich nur auf das Speichern in [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) aus; für alle anderen Formate wird er ignoriert. |

### getSize() {#getSize--}
```
public abstract Dimension getSize()
```

Ermittelt die Größe des Bildes.

**Rückgabe:**
java.awt.Dimension
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Ermittelt die Breite des Bildes in Pixeln.

**Rückgabe:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Ermittelt die Höhe des Bildes in Pixeln.

**Rückgabe:**
int