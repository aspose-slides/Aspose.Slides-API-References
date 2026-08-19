---
title: IBackdrop3DScene
second_title: Aspose.Slides for Java API Reference
description: Definierar ett plan där effekter som glöd och skugga appliceras i förhållande till den form de appliceras på.
type: docs
url: /sv/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Definierar ett plan där effekter, som glöd och skugga, appliceras i förhållande till den form de appliceras på.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Returnerar eller anger en normalvektor. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Returnerar eller anger en normalvektor. |
| [getAnchorPoint()](#getAnchorPoint--) | Returnerar eller anger en punkt i 3D-rymden. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Returnerar eller anger en punkt i 3D-rymden. |
| [getUpVector()](#getUpVector--) | Returnerar eller anger en vektor som representerar uppåt. |
| [setUpVector(float[] value)](#setUpVector-float---) | Returnerar eller anger en vektor som representerar uppåt. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Returnerar eller anger en normalvektor. För att vara mer exakt definierar detta attribut en vektor som är normal mot bakgrundsplans yta. Vektorn representeras av en array med 3 float-värden som definierar X-, Y- och Z-koordinater. Läs/skriv float[].

**Returnerar:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Returnerar eller anger en normalvektor. För att vara mer exakt definierar detta attribut en vektor som är normal mot bakgrundsplans yta. Vektorn representeras av en array med 3 float-värden som definierar X-, Y- och Z-koordinater. Läs/skriv float[].

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Returnerar eller anger en punkt i 3D-rymden. Denna punkt är den punkt i rymden som förankrar bakgrundsplanet. 3D-punkt representeras av en array med 3 float-värden som definierar X-, Y- och Z-koordinater. Läs/skriv float[].

**Returnerar:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Returnerar eller anger en punkt i 3D-rymden. Denna punkt är den punkt i rymden som förankrar bakgrundsplanet. 3D-punkt representeras av en array med 3 float-värden som definierar X-, Y- och Z-koordinater. Läs/skriv float[].

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Returnerar eller anger en vektor som representerar uppåt. För att vara mer exakt definierar detta attribut en vektor som representerar uppåt i förhållande till bakgrundsplans yta. Vektorn representeras av en array med 3 float-värden som definierar X-, Y- och Z-koordinater. Läs/skriv float[].

**Returnerar:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Returnerar eller anger en vektor som representerar uppåt. För att vara mer exakt definierar detta attribut en vektor som representerar uppåt i förhållande till bakgrundsplans yta. Vektorn representeras av en array med 3 float-värden som definierar X-, Y- och Z-koordinater. Läs/skriv float[].

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float[] |  |