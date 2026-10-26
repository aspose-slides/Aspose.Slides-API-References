---
title: IFillOverlay
second_title: Odwołanie API Aspose.Slides dla Javy
description: Reprezentuje efekt nakładki wypełnienia.
type: docs
url: /pl/com.aspose.slides/ifilloverlay/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Reprezentuje efekt nakładki wypełnienia. Nakładka wypełnienia może być użyta do określenia dodatkowego wypełnienia dla obiektu i połączenia obu wypełnień.
## Metody

| Metoda | Opis |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Format wypełnienia. |
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


Format wypełnienia. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)