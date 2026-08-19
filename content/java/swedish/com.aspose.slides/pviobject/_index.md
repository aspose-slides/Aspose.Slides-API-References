---
title: PVIObject
second_title: Aspose.Slides för Java API-referens
description: Inkapslar grundläggande serviceinfrastruktur för objekt som kan vara föremål för arv av egenskapsvärden.
type: docs
url: /sv/com.aspose.slides/pviobject/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Inkapslar grundläggande serviceinfrastruktur för objekt som kan vara föremål för arv av egenskapsvärden.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Jämför med specificerat objekt. |
| [hashCode()](#hashCode--) | Returnerar hash-kod. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Endast läsning IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Endast läsning long.

**Returnerar:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

Returnerar överordnad IPresentationComponent. Endast läsning [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returnerar:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```


**Returnerar:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

Returnerar grundsliden. Endast läsning [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returnerar:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

Returnerar presentationen. Endast läsning [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Jämför med specificerat objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objekt att jämföra. |

**Returnerar:**
boolean - Sant om objekten är lika, annars falskt.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Returnerar hash-kod.

**Returnerar:**
int - Hash-kod.