---
title: IFillOverlay
second_title: Aspose.Slides a Java API referenciához
description: Egy Fill Overlay hatást reprezentál.
type: docs
url: /hu/com.aspose.slides/ifilloverlay/
---
**Összes megvalósított interfész:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Egy Fill Overlay hatást reprezentál. A Fill Overlay használható egy objektum további kitöltésének megadására, és a két kitöltést összekeverni.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. Olvasás/írás [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Visszatér:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```


FillBlendMode. Olvasás/írás [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Fill format. Csak olvasás [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)