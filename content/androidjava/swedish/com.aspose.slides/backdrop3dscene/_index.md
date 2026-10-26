---
title: Backdrop3DScene
second_title: Aspose.Slides för Android via Java API-referens
description: Definierar ett plan där effekter såsom glöd och skugga appliceras i förhållande till den form de appliceras på.
type: docs
url: /sv/com.aspose.slides/backdrop3dscene/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Definierar ett plan där effekter, såsom glöd och skugga, appliceras i förhållande till den form de appliceras på.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Returnerar eller anger en normalvektor. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Returnerar eller anger en normalvektor. |
| [getAnchorPoint()](#getAnchorPoint--) | Returnerar eller anger en punkt i 3D-rymden. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Returnerar eller anger en punkt i 3D-rymden. |
| [getUpVector()](#getUpVector--) | Returnerar eller anger en vektor som representerar upp. |
| [setUpVector(float[] value)](#setUpVector-float---) | Returnerar eller anger en vektor som representerar upp. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Läs-endast long.

**Returnerar:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```


Returnerar eller anger en normalvektor. För att vara mer exakt definierar detta attribut en vektor som är normal mot ytan på bakgrundsplanet. Vektorn representeras av en array med 3 float-värden som definierar X-, Y- och Z-koordinater. Läs/skriv float[].

**Returnerar:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```


Returnerar eller anger en normalvektor. För att vara mer exakt definierar detta attribut en vektor som är normal mot ytan på bakgrundsplanet. Vektorn representeras av en array med 3 float-värden som definierar X-, Y- och Z-koordinater. Läs/skriv float[].

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```


Returnerar eller anger en punkt i 3D-rymden. Denna punkt är den punkt i rymden som förankrar bakgrundsplanet. 3D-punkten representeras av en array med 3 float-värden som definierar X-, Y- och Z-koordinater. Läs/skriv float[].

**Returnerar:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```


Returnerar eller anger en punkt i 3D-rymden. Denna punkt är den punkt i rymden som förankrar bakgrundsplanet. 3D-punkten representeras av en array med 3 float-värden som definierar X-, Y- och Z-koordinater. Läs/skriv float[].

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```


Returnerar eller anger en vektor som representerar upp. För att vara mer exakt definierar detta attribut en vektor som representerar upp i förhållande till ytan på bakgrundsplanet. Vektorn representeras av en array med 3 float-värden som definierar X-, Y- och Z-koordinater. Läs/skriv float[].

**Returnerar:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```


Returnerar eller anger en vektor som representerar upp. För att vara mer exakt definierar detta attribut en vektor som representerar upp i förhållande till ytan på bakgrundsplanet. Vektorn representeras av en array med 3 float-värden som definierar X-, Y- och Z-koordinater. Läs/skriv float[].

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float[] |  |