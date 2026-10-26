---
title: Format
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: A diagram formátum tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/format/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Az összes megvalósított interfész:**
[com.aspose.slides.IFormat](../../com.aspose.slides/iformat)
``` 
public final class Format extends PVIObject implements IFormat
```

A diagram formátum tulajdonságait képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFill()](#getFill--) | Visszaadja egy diagram kitöltési stílusának tulajdonságait. |
| [getLine()](#getLine--) | Visszaadja egy diagram vonalstílusának tulajdonságait. |
| [getEffect()](#getEffect--) | Visszaadja a diagramhoz használt effektusokat. |
| [getEffect3D()](#getEffect3D--) | Visszaadja egy diagram 3D formátumát. |
### getVersion() {#getVersion--}
``` 
public long getVersion()
```


Verzió. Csak olvasható long.

**Visszatér:**
long
### getFill() {#getFill--}
```
public final IFillFormat getFill()
```


Visszaadja egy diagram kitöltési stílusának tulajdonságait. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getLine() {#getLine--}
```
public final ILineFormat getLine()
```


Visszaadja egy diagram vonalstílusának tulajdonságait. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffect() {#getEffect--}
```
public final IEffectFormat getEffect()
```


Visszaadja a diagramhoz használt effektusokat. Csak olvasható [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Visszatér:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getEffect3D() {#getEffect3D--}
```
public final IThreeDFormat getEffect3D()
```


Visszaadja egy diagram 3D formátumát. Csak olvasható [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Visszatér:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)