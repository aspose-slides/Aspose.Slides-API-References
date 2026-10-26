---
title: IFillOverlay
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje efekt Fill Overlay.
type: docs
url: /cs/com.aspose.slides/ifilloverlay/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Reprezentuje efekt Fill Overlay. Fill overlay může být použito k určení další výplně pro objekt a sloučit dvě výplně dohromady.
## Metody

| Metoda | Popis |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill formát. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. Čtení/zápis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Vrací:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```


FillBlendMode. Čtení/zápis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Fill formát. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)