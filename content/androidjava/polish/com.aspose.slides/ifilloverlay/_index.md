---
title: IFillOverlay
second_title: Aspose.Slides dla Androida za pośrednictwem Java API
description: Reprezentuje efekt Fill Overlay.
type: docs
url: /pl/com.aspose.slides/ifilloverlay/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Reprezentuje efekt Fill Overlay. Fill overlay może być użyty do określenia dodatkowego wypełnienia dla obiektu i połączenia obu wypełnień razem.
## Metody

| Metoda | Opis |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. Odczyt/zapis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Zwraca:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```


FillBlendMode. Odczyt/zapis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Fill format. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)