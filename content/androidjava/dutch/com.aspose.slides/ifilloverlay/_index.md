---
title: IFillOverlay
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Fill Overlay-effect voor.
type: docs
url: /nl/com.aspose.slides/ifilloverlay/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Stelt een Fill Overlay-effect voor. Een fill overlay kan worden gebruikt om een extra vulling voor een object op te geven en de twee vullingen te mengen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Vulformaat. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. Lezen/schrijven [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Retour:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```


FillBlendMode. Lezen/schrijven [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Fill format. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**
[IFillFormat](../../com.aspose.slides/ifillformat)