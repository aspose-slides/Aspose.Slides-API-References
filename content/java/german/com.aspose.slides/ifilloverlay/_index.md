---
title: IFillOverlay
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Fill Overlay-Effekt dar.
type: docs
url: /de/com.aspose.slides/ifilloverlay/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Stellt einen Fill Overlay-Effekt dar. Ein Fill Overlay kann verwendet werden, um eine zusätzliche Füllung für ein Objekt anzugeben und die beiden Füllungen miteinander zu mischen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. Lese/Schreib [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Rückgabe:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. Lese/Schreib [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Fill format. Nur-Lesen [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)