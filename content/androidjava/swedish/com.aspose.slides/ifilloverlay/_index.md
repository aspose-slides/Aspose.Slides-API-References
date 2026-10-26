---
title: IFillOverlay
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en Fill Overlay-effekt.
type: docs
url: /sv/com.aspose.slides/ifilloverlay/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Representerar en Fill Overlay-effekt. En fill overlay kan användas för att ange ett extra fyllningsvärde för ett objekt och blanda de två fyllningarna tillsammans.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. Läs/skriv [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Returnerar:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. Läs/skriv [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Fyllningsformat. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)