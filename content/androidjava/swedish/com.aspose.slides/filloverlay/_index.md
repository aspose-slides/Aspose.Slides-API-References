---
title: FillOverlay
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en Fill Overlay-effekt.
type: docs
url: /sv/com.aspose.slides/filloverlay/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Representerar en Fill Overlay-effekt. En fill overlay kan användas för att ange en extra fyllning för ett objekt och blanda de två fyllningarna tillsammans.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Fyllformat. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Hämtar den effektiva Fill Overlay-effektdatan med arv tillämpat. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om den angivna [FillOverlay](../../com.aspose.slides/filloverlay) är lika med den aktuella [FillOverlay](../../com.aspose.slides/filloverlay). |
| [hashCode()](#hashCode--) | Fungerar som en hash-funktion för en viss typ. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Fyllformat. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. Läs/skriv [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Returnerar:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. Läs/skriv [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

Hämtar den effektiva Fill Overlay-effektdatan med arv tillämpat.

**Returnerar:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - En [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Skrivskyddad long.

**Returnerar:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestämmer om den angivna [FillOverlay](../../com.aspose.slides/filloverlay) är lika med den aktuella [FillOverlay](../../com.aspose.slides/filloverlay).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [FillOverlay](../../com.aspose.slides/filloverlay) att jämföra. |

**Returnerar:**
boolean - sant om objekten är lika; annars falskt.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Fungerar som en hash-funktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.