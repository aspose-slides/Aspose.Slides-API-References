---
title: IFillOverlay
second_title: Aspose.Slides for Android a Java API hivatkozása
description: Egy Fill Overlay hatást ábrázol.
type: docs
url: /hu/com.aspose.slides/ifilloverlay/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Egy Fill Overlay hatást reprezentál. A fill overlay használható egy objektumhoz további kitöltés megadására, és a két kitöltés összekeverésére.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. Olvasás/írás [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Visszatérési érték:**
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

Fill format. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatérési érték:**
[IFillFormat](../../com.aspose.slides/ifillformat)